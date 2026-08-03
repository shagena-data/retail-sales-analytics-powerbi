# retail-sales-analytics-powerbi
A 3-page Power BI dashboard project covering Executive, Customer, and Product Analytics with DAX, Power Query, and interactive visualizations.

Retail Sales Analytics Dashboard | Power BI
Project Overview

This project is an interactive Retail Sales Analytics Dashboard built in Microsoft Power BI to analyze sales performance, customer behavior, and product profitability across multiple dimensions. The dashboard is designed for business decision-makers and provides insights through a clean dark-themed interface with synchronized filters, KPI cards, and advanced visualizations.

The project demonstrates end-to-end Power BI skills including Power Query, data modeling, DAX, time intelligence, and dashboard design.

Dashboard Pages
Executive Dashboard

Provides a high-level overview of overall business performance.

KPIs

Total Sales
Total Profit
Total Orders
Average Order Value

Visuals

Monthly Sales Trend
Sales by Product Line
Sales by City (Map)
Payment Method Distribution
Customer Type Distribution
Customer Analytics

Analyzes customer engagement, behavior, and satisfaction.

KPIs

Total Customers / Transactions
Average Customer Rating
Average Basket Size

Visuals

Customer Type Sales Trend (Ribbon Chart)
Average Customer Rating (Gauge)
Rating vs Sales by City (Scatter Chart)
Sales by Customer Location (Map)
Monthly Customer Revenue Heatmap
Product Analytics

Evaluates product performance and profitability.

KPIs

Total Sales
Total Products Sold
Average Product Price
Profit Margin %

Visuals

Product Revenue Contribution (Treemap)
Profit Contribution by Product Line (Waterfall Chart)
Sales Decomposition Explorer (Decomposition Tree)
Profit Margin Achievement (Gauge)
Monthly Product Sales Heatmap
Dataset
Rows: ~1,000
Columns: 17
Data Cleaning: No null values, no duplicate records
Date Table: Custom DimDate table created for time intelligence
Data Modeling

A Star Schema was implemented.

Fact Table

FactSales

Dimension Table

DimDate

Relationships were configured using one-to-many cardinality between DimDate and FactSales.

DAX Measures

Key measures created during the project include:

Total Sales
Total Profit
Total Orders
Total Quantity
Average Order Value
Average Product Price
Average Basket Size
Average Customer Rating
Profit Margin %
Running Total Sales
Month-to-Date (MTD) Sales
Previous Month Sales
Previous Year Sales
YoY Growth %
Key Business Insights
Food and Beverages is the highest revenue-generating product line.
Yangon contributes the largest share of sales.
Member customers generate higher revenue than Normal customers.
The current profit margin is approximately 4.76%, close to the business target.
Monthly sales fluctuate across product lines, highlighting seasonal demand patterns.
Tools & Technologies
Microsoft Power BI
Power Query
DAX (Data Analysis Expressions)
Data Modeling
Time Intelligence
KPI Cards
Ribbon Chart
Treemap
Waterfall Chart
Decomposition Tree
Heatmap
Gauge Chart
Map Visuals
Project Files

Retail-Sales-Analytics-PowerBI/
│
├── Dashboard.pbix
├── Retail_Sales_Dataset.xlsx
├── README.md
├── images/
│ ├── executive_dashboard.png
│ ├── customer_analytics.png
│ └── product_analytics.png
└── DAX_Measures.md

Dashboard Preview

Add screenshots of:

Executive Dashboard
Customer Analytics
Product Analytics

inside the images folder and display them in this README.

Author

Shagena

Aspiring Data Analyst | SQL | Excel | Python | Pandas | NumPy | Power BI | DAX

This project was created as part of my data analytics portfolio to demonstrate end-to-end business intelligence and dashboard development skills.
