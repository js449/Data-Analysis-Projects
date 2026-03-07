# Sales Performance & Insights Dashboard (Power BI)

📌 ## Project Overview

This project involves an end-to-end data analysis of sales performance using Power BI. The goal was to transform raw sales data into actionable business intelligence, focusing on product performance, temporal trends, and profitability analysis.

I leveraged Power Query for ETL, designed a robust Star Schema for data modeling, and wrote custom DAX measures to provide dynamic, user-driven insights.

## 📊 Key Business Questions Answered

The dashboard was designed to address the following requirements:

Product Ranking: Identification of the Top 5 and Bottom 5 products based on Sales, Profit, and Quantity Sold.

Temporal Trends: Analysis of how sales trends vary across different granularities, including Daily, Monthly, Quarterly, and Annual views.

Profitability Correlation: Visualization of the relationship between Sales and Profit to identify high-value products vs. low-margin items.

Time Intelligence: A dynamic comparison tool allowing users to compare Sales, Profit, and Quantity between any two user-selected periods.

Discount Impact: Calculation of the average discount offered within each specific discount category.

Order Volume: Tracking the total number of orders processed.

Granular Drill-through: A detailed order-level view (Sales, Profit, Discount, Net Sales) with integrated visual filters for Product, Date, Customer ID, and Promotion Categories.

Geospatial Analysis: Breakdown of sales performance across different cities.

## 🛠️ Technical Stack & Skills

Tool: Power BI Desktop

Data Transformation: Power Query (M) for data cleaning, handling null values, and ensuring correct data types.

Data Modeling: Implemented a Star Schema (Fact and Dimension tables) to optimize filter propagation and report performance.

DAX (Data Analysis Expressions): \* Measures: Created calculated measures for Total Sales, Net Sales, Total Orders, and Average Discount.

Time Intelligence: Developed DAX logic for period-over-period comparisons and YTD tracking.

Ranking: Used RANKX and TOPN functions for the Top/Bottom 5 product analysis.

## 📈 Dashboard Features

Interactive Slicers: Users can filter the entire report by Date, City, or Category.

Drill-Downs: Ability to move from Annual views down to Daily transaction details.

Visual Variety: Utilized Scatter Plots (Sales vs. Profit), Decomposition Trees, and Map Visuals for geographic distribution.

📂 Repository Structure
/Data: Sample dataset or links to sources.

/Report: The .pbix file (Sales Data Analysis).

/Screenshots: Images of the final dashboard pages.
