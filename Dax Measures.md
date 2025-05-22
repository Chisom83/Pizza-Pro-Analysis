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
