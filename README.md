```sql

-- In here we can analyze data from a sub table which filters information from the main table according to the exact catheroty we want to see


SELECT 
  year, 
    Total_sales, 
      AVG(sales) AS average
FROM ( 
  SELECT 
    year, 
      sales_month, 
        SUM(sales) AS Total_sales
  FROM retail_sales
  WHERE kind_of_business IN ("Men's clothing stores", "Women's clothing stores")
  GROUP BY 1,2
  ORDER BY 4 DESC ) AS Sub_table

GROUP BY 1, 2;    
```
