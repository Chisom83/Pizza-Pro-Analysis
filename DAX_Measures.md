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

## LM Revenue 
```
    CALCULATE(
        [Total Revenue],DATEADD('Calendar'[Date], -1,MONTH))
```

## LM Quantity 
```
    CALCULATE(
        [Total Quantity],DATEADD('Calendar'[Date], -1,MONTH))
```

## LM Orders 
```
    CALCULATE(
        [Total Orders],DATEADD('Calendar'[Date], -1,MONTH))
```

## DynamicTitle 
```
 VAR _TopBottom = 
 SELECTEDVALUE( 'Top/Bottom Slide'[Top/Bottom])
 VAR _ActiveTopBottom = SELECTEDVALUE('Switch Top/Bottom'[Switch Top/Bottom Order])
 VAR _Result =
    IF(_ActiveTopBottom=0,_TopBottom&"Best Performing Pizza by Revenue", 
      "Underperforming Pizza by Revenue"
    )
Return
    _Result
```
