Project Title:
SSAS – Sales Analysis Multidimensional Model
Project Description:
As part of the Business Intelligence module in the Power BI intensive program at ITI, I developed a complete SSAS multidimensional project to analyze sales performance. The model was designed to enable deep exploration of product, customer, and channel insights over time using KPIs, calculated measures, and perspectives.

Key Features:
•	Built Three SSAS Cubes to cover various analytical needs:
-	Product Cube: to analyze product sales quantities over years.
-	Product_Customer_Cube: to explore relationships between products and customers over time.
-	OrderDetails_Cube: to provide a complete view using all available dimensions.

•	Integrated Dimensions and Facts from a star schema built on the SalesDW 
-	Dimensions included: Product, Customer, Time, Channel, SalesMan
-	Fact table: FactSales

•	Created Calculated Measures:
-	 Sales Unit Price = [Total Price] / [Qty]

•	Developed KPIs:
-	Qty KPI to evaluate product sales volume vs. a 1000-unit threshold using status indicators (faces).

•	Added Arabic Translations for dimensions and measures to support multilingual reporting.

•	Created a Perspective:
-	Channel Product Perspective for focused analysis on customer, channel location, and sales metrics.

•	Exported Pivot Tables and Charts from Excel to visualize and compare KPI values against actual performance.

Technologies Used:
SSAS Multidimensional, SQL Server, Visual Studio, Excel, SQL

