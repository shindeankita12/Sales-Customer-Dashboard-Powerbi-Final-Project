Power BI Sales & Customer Analysis Dashboard

 Dataset Description:--
* **Customer_Dim** → Customer details (Name, Segment, Region)
* **Product_Dim** → Product details (Category, Subcategory, Price)
* **Date_Dim** → Date hierarchy (Year, Month, Quarter)
* **Sales_Fact** → Sales transactions (Units Sold, Total Amount)
* **Returns_Fact** → Returned orders
* **Region_Dim** → Region details and profit
* 
  Data Model:--

A **Star Schema** is used:

* Fact Table: `Sales_Fact`
* Dimension Tables: Customer, Product, Date, Region
* Relationships created using primary and foreign keys


 Interactive dashboard with slicers (Year, Region, Category, Segment)
 KPI Cards for Total Sales, Profit, Profit Margin, Units Sold
 Time Intelligence (YTD, YOY, Monthly Trends)
 Top N analysis (Top Customers & Products)
 Drillthrough for detailed customer-level insights
 Conditional formatting and clean UI design

Report Pages:--

Main Dashboard:--

* Overview of sales performance
* Sales trend over time
* Sales by region and category

 Sales Analysis:--

* Monthly sales trend
* Top 5 products by sales
* Sales comparison using matrix (Region vs Category)

 Customer Analysis:--

* Top customers by sales and profit
* Customer segmentation analysis
* Detailed customer table with KPIs

Drillthrough Page:---

* Customer-level detailed purchase data
* Shows product-wise sales, units, and date


 DAX Measures Used:---

* Total Sales
* Total Profit
* Profit Margin
* Total Units
* Total Customers
* Avg Sales per Customer
* YTD Sales
* YOY Growth

Tools & Technologies:--

* Power BI
* DAX (Data Analysis Expressions)
* Excel (Data Source)


