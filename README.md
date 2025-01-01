
# Adventure Works Bike Shop Report

https://app.powerbi.com/reportEmbed?reportId=b6bb2ae2-dc70-4397-a3d9-e2d3c809f970&autoAuth=true&ctid=0ee9b5f9-52b3-4351-8198-c4804cd66b68

## Overview
 This dashboard enables end users to track key performance indicators (KPIs) such as revenue, profit, orders, and return rates. It provides insights into customer behavior, helps identify high-value customers, and assesses the performance of individual products. Additionally, it allows for regional performance comparisons and facilitates informed decision-making, potentially contributing to increased profitability.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under 'Data' preview section, check "Column Distribution", "Column Quality" & "Column Profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Modified data types and table names as needed for improved clarity.
- Step 5 : Utilized a variety of text, numeric, and date/time tools, along with functions such as merging and appending queries, in the Power Query Editor to meet the requirements. 
- Step 6 : Created table relationships in the model view using primary & foreign keys.
- Step 7 : Utilized various data modeling options, including hierarchies, data categories, and hidden fields, as needed.
- Step 8 : Used Data Analysis Expression (DAX) to add calculated columns & measures in the model.

- Step 9 : Different categories of DAX functions applied are mentioned below:
  
  (a) Maths & Stats Functions- SUM, AVERAGE, MAX/MIN, ITERATOR, etc
  
  (b) Logical Functions- IF, AND, SWITCH, TRUE, FALSE, etc

  (c) Text Functions- CONCATENATE, FORMAT, LEFT/MID/RIGHT, etc

  (d) Filter Functions- CALCULATE, FILTER, ALL, etc

  (e) Table Functions- SUMMARIZE, ADDCOLUMNS, DISTINCT, etc

  (f) Date & Time Functions- DATE, WEEKDAY, TIME INTELLIGENCE, etc

  (g) RELATIONSHIP FUNCTIONS- RELATED, CROSSFILTER, etc

           
          
- Step 10 : Created a page named "Executive Dashboard" in the report view with the details mentioned below:

  (a) Inserted the "Adventure Works Bike Shop" logo.
  
  (b) Created various KPIs, such as revenue, profit, orders, and return rates, using 'Shapes' and 'Cards'.

  (c) Inserted a 'Line Chart' using 'Revenue' and 'Start of Month'.

  (d) Created 'KPI visuals' using 'Trend Axis' & 'Target'.

  (e) Inserted a 'Bar Chart' using 'CategoryName' & 'Orders'.

  (f) Inserted a 'Matrix' to showcase 'Top 10 Products' with 'Orders', 'Revenue' & 'Return Rate'.

  (g) Created two more card visuals to showcase 'Most Ordered Product Type' and 'Most Returned Product Type'.

Snapshot of 'Executive Dashboard' Page:

![Screenshot (58)](https://github.com/user-attachments/assets/9fd8e7fd-24d0-41d9-b67a-078a4190ae1f)

- Step 11 : Created a page named "Map" in the report view with the details mentioned below:

  (a) Inserted a 'Map' with dark style using 'Country' & 'Orders'

  (b) Added continent slicers to the page.

Snapshot of 'Map' Page :

![Screenshot (59)](https://github.com/user-attachments/assets/0709885c-1215-49f7-ab66-19d6d44c15d1)


- Step 13 :  Created a page named "Product Details" in the report view with the details mentioned below:

  (a) Created 'Gauge Charts' using 'Orders', 'Revenue' & 'Profit'.

  (b) Created 'Area Chart' using 'Date', 'Profit' and 'Adjusted Profit'.

  (c) Created two different slicers named 'Price Adjustment(%) & 'Product Metric Selection'

  (d) Inserted a 'Card' using 'ProductName' from the 'Product Lookup Table'.

  (e) Created another 'Area Chart' using 'Date' and 'Product Metric Selection'.

Snapshot of 'Product Details' Page :  

![Screenshot (60)](https://github.com/user-attachments/assets/db60c74e-63f2-4a27-a1f3-e609c77061fe)


- Step 14 :  Created a page named "Customer Details" in the report view with the details mentioned below:

  (a) Inserted a 'Card' showing 'Total Customer'.

  (b) Inserted a 'Line Chart' using 'Date' and 'Customer Metric Selection'.

  (c) Created two 'Donut Charts' using 'Income Level/Occupation' and 'Orders', respectively.

  (d) Used a 'Table' to demonstrate 'CustomerKey', 'Customer Full Name', 'Orders' & 'Revenue'.

  (e) Created Multiple Cards to showcase 'Top Customer', 'Orders' & 'Revenue'.

  (f) Inserted a 'Slicer' for 'Years'.

  (g) Inserted an 'Information' button and applied the 'Bookmark' action to showcase 'Customer Insight'.

Snapshot of 'Customer Details' Page :

![Screenshot (61)](https://github.com/user-attachments/assets/22bbe797-b006-4b85-9cae-adad4fc29191)

 
        
- Step 15 : Multiple 'Buttons' were inserted and relevant 'Actions', such as 'Bookmark' and 'Page Navigation' were applied to them.
        
 - Step 16 : Created a page named "Category Tooltip" in the report view with the details mentioned below:

   (a) Changed the page type from 'Standard' to 'Tooltip' and updated the canvas settings to 'Custom'.

   (b) Performed basic formatting adjustments for 'Height', 'Width', 'Background', etc.

   (c) Inserted a 'Multi-row card' to showcase 'Orders', 'Revenue', 'Profit', 'Total Returns' and 'Returm Rate'. 
   
   (d) Inserted an 'Area Chart' using 'Date Heirarchy' and 'Weekly Orders'.

Snapshot of 'Category Tooltip' Page :

![Screenshot (62)](https://github.com/user-attachments/assets/571c5d9a-aae7-4c35-afc3-fb8ad142f843)

 
 
  - Step 17 : Used 'AI Visuals' like 'Decomposition Tree' to 'Analyze' orders 'Explain by' CategoryName, SubCategoryName & ProductName.

    Refer the Snapshot: 

![Screenshot (57)](https://github.com/user-attachments/assets/72e7dcc5-6ae6-442a-9bf7-9956cecffdd6)

 - Step 18 : The report was then published to Power BI Service.
 
 ![Screenshot (63)](https://github.com/user-attachments/assets/c281dbdf-0461-465e-a1b7-562ab1059417)

 
