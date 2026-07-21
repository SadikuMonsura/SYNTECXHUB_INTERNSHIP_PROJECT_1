# SYNTECXHUB_INTERNSHIP_PROJECT_1
SALES_DASHBOARD_PROJECT

# SALES PERFORMANCE ANALYSIS AND BUSINESS INTELLIGENCE DASHBOARD 

![](Dashboard_Overview.png)

## Executive Summary

This project focused on analyzing sales performance data to evaluate revenue generation, profitability, sales trends, product category performance, discount effectiveness, regional performance, payment methods, sales representatives, and customer characteristics.

The analysis was conducted using Power BI, where the dataset was transformed, modeled, analyzed, and visualized through an interactive sales performance dashboard.
The initial dataset was reviewed for data quality and found to be relatively clean, with no duplicate records and no missing/null values. During the data preparation process, an irrelevant column containing combined Sales Representative and Region information was removed because the dataset already contained separate columns for these two attributes.

Additional data preparation and modeling activities included creating a new Sales column to address an issue with the original Sales Amount field, creating a Discount Band column using DAX, and developing a dedicated Calendar table to support time-based analysis and accurate month-over-month calculations.

Several DAX measures were created to calculate key business metrics, including Total Revenue, Total Profit, Profit Margin, Sales Growth, Profit Growth, Total Cost, Total Quantity, Total Transactions, Average Discount, Previous Month Sales, and Previous  Month Profit.

The resulting dashboard provides a consolidated view of sales performance and enables stakeholders to identify business trends, evaluate profitability, compare performance across different dimensions, and make data-driven decisions. 

### Project Background

Sales data contains valuable information that organizations can use to understand how their products and sales activities are performing.

However, raw transactional data alone does not provide an immediate understanding of business performance. It must first be analyzed to answer important questions such as:

- How much revenue is the business generating?
- How profitable is the business?
- Which product categories generate the most revenue and profit?
- Which regions perform best?
- Which sales representatives contribute the most to revenue and profit?
- Which payment methods are most commonly associated with sales?
- How does sales performance change over time?
- How do discounts affect revenue and profitability?
- Are sales and profit growing or declining?

This project was therefore developed to transform transactional sales data into an interactive business intelligence dashboard that provides insights into these areas. 

### Project Objective

The primary objective of this project was to analyze sales performance and develop an interactive Power BI dashboard that provides actionable insights into revenue, profit, sales trends, product performance, discount performance, and other key business dimensions.

ount performance, and other key business dimensions.

- Evaluate overall sales and revenue performance.
- Measure total profit and profitability.
- Analyze revenue and profit trends over time.
- Identify high-performing and low-performing product categories.
- Compare sales and profit performance across regions.
- Evaluate the performance of individual sales representatives.
- Analyze sales performance by payment method.
- Understand the relationship between discounts and business performance.
- Track sales and profit growth over time.
- Provide a centralized interactive dashboard for business decision-making.

## Dataset Description

The dataset used for this project is a sales transaction dataset containing information about sales activities and business performance.

The dataset includes fields relating to areas such as:

- Product ID
- Sales Date
- Sales Representative
- Region
- Sales Amount
- Quantity Sold
- Product Category
- Unit Cost
- Unit Price
- Customer Type
- Discount
- Payment Mode
- Sales Channel

These fields provided sufficient information to analyze sales performance from multiple business perspectives, including time, product, geography, sales personnel, customer type, payment method, and sales channel.

### Data Quality Assessment
