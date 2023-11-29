# Sales Dashboard

## Problem Statement

This dashboard helps to answer the following questions:
- top 5 products by sales and month
- sales by region
- number of orders by range of date
- sales by month
- sales by product



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset are four csv files. Import by folder and combine the files.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Use "extract text between delimiters" to extract region from the customer address column. Use "trim" in column format to trim unnecessary spaces.
- Step 4 : Split Order Date column by space delimiter.
- Step 5 : Visual filters (Slicers) was added for Order Date.
- Step 6 : Two card visuals were added to the canvas, one representing total number of orders & other total sales.
- Step 7 : A ribbon chart was also added to the report representing top 5 products by sales and month. Two bar charts added to represent sales by month and sales by product. A scatter chart added to show relationship between quantity sold and price of product.
- Step 8 : In another page, a map visual added to show sales by region.
