# All Dax measures used in this analysis are stored here

## Total Revenue 
```
SUMX(Fact_Table,Fact_Table[Quantity] * Fact_Table[Pizzas_Price])
```

## Total Quantity
```
SUM(Fact_Table[Quantity])
```

## Total Orders 
```
DISTINCTCOUNT(Fact_Table[Order_Id])
```
## PizzaType Dynamic Bottom 
```
    VAR _PizzaType =
    TOPN('Top/Bottom Slide'[Top/Bottom Value],
    ALL(Fact_Table[Pizza_Name]), [Total Revenue],ASC)
    VAR _ActivePizzaType = SELECTEDVALUE(Fact_Table[Pizza_Name])
    RETURN
    IF(_ActivePizzaType IN _PizzaType, [Total Revenue])
```
## PizzaType Dynamic Top
```
    VAR _PizzaType =
    TOPN('Top/Bottom Slide'[Top/Bottom Value],
    ALL(Fact_Table[Pizza_Name]), [Total Revenue],DESC)
    VAR _ActivePizzaType = SELECTEDVALUE(Fact_Table[Pizza_Name])
    RETURN
    IF(_ActivePizzaType IN _PizzaType, [Total Revenue])
```
