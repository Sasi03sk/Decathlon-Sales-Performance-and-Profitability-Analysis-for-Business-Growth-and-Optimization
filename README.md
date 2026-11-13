# 📊 Decathlon Sales Performance and Profitability Analysis

## 📌 Project Overview

This project focuses on analysing Decathlon sales data using **Microsoft Excel and Power BI** to understand sales performance, product categories, store locations, regional performance, and profitability.

The main objective of this project is to identify sales trends, top-performing products and stores, and profit patterns to generate meaningful business insights and support better business decision-making.

This project demonstrates my practical learning and skills in data cleaning, data transformation, data modelling, DAX calculations, data visualization, and business analytics.

## 🎯 Project Objectives

- Analyse sales performance across different states, cities, and store locations.
- Identify top-performing and low-performing product categories and subcategories.
- Evaluate total sales, profit, quantity sold, and profit margins.
- Analyse monthly and yearly sales trends.
- Compare sales performance across different years.
- Understand business performance using Descriptive, Diagnostic, Predictive, and Prescriptive Analysis.
- Develop an interactive Power BI dashboard to present meaningful business insights.

## 📂 Dataset Information

- **Dataset Name:** Decathlon Sales Dataset
- **Data Source:** [Zoho Analytics – Sample Data Generator](https://www.zoho.com/analytics/sample-data-generator.html)
- **Domain:** Sales Analytics
- **Total Sales Records:** 493
- **Analysis Period:** January 2023 – December 2024

### Dataset Tables

The original sales dataset was organized into fact and dimension tables.

| Table Name | Description |
|---|---|
| FACT_SALES | Contains order details, quantity, sales, profit and sales targets |
| DIM_Customer | Contains customer identification and customer names |
| DIM_Product | Contains product categories and subcategories |
| DIM_Store | Contains store locations, cities and states |
| DateTable | Calendar table created for time-based analysis |

## 🛠️ Tools and Technologies

- **Microsoft Excel:** Data cleaning, data organization and initial data preparation.
- **Power Query Editor:** Data transformation, cleaning and preparation.
- **Power BI Desktop:** Data modelling, DAX calculations and interactive dashboard development.
- **DAX:** KPI calculations and business performance analysis.
- **GitHub:** Project documentation and portfolio presentation.
- **AI Tools:** Learning support and assistance in understanding DAX, data analysis and dashboard development.

## 🔄 Project Workflow

1. **Data Collection:** Imported the Decathlon sales dataset into Excel and Power BI.
2. **Data Cleaning:** Checked duplicate records, missing values, inconsistent formats and data quality.
3. **Data Transformation:** Organized the original dataset into fact and dimension tables using Power Query.
4. **Data Modelling:** Created relationships between fact and dimension tables using a Star Schema.
5. **DAX Calculations:** Developed measures to calculate sales, profit, orders, quantity and profit margins.
6. **Data Visualization:** Created charts, KPI cards, and interactive dashboard elements.
7. **Data Analysis:** Performed four types of data analysis to identify business performance and improvement opportunities.

## 🏗️ Data Modelling

The project follows a **Star Schema data model**.

- FACT_SALES – Central fact table.
- DIM_Customer – Customer dimension.
- DIM_Product – Product dimension.
- DIM_Store – Store dimension.
- DateTable – Calendar dimension.

Relationships were created using the following key columns:

| Fact Table Column | Dimension Table Column |
|---|---|
| Customer_ID | DIM_Customer[Customer_ID] |
| Product_ID | DIM_Product[Product_ID] |
| Store_ID | DIM_Store[Store_ID] |
| ORDER_DATE | DateTable[Date] |

The relationships use Many-to-One cardinality with single-direction filtering.

## 📐 Key DAX Measures

The following DAX measures were created to evaluate business performance.

| Measure | Purpose |
|---|---|
| Total Sales | Calculates total sales revenue |
| Total Profit | Calculates total profit earned |
| Total Orders | Counts unique sales orders |
| Total Quantity | Calculates total units sold |
| Average Order Value | Calculates average sales per order |
| Profit Margin % | Calculates profit as a percentage of sales |
| Sales per Unit | Calculates average sales value per unit |
| Previous Year Sales | Compares sales with the previous year |
| Sales Growth % | Calculates percentage change in sales |
| Cumulative Sales | Calculates running total sales |

## 📊 Power BI Dashboard

The Power BI report contains two main pages:

### 1. Essential KPI Measures

Displays important business performance indicators using KPI cards.

- Total Sales
- Total Profit
- Total Orders
- Total Quantity
- Average Order Value
- Profit Margin %
- Sales per Unit
- Previous Year Sales
- Cumulative Sales

### 2. Sales Performance Dashboard

The dashboard includes the following visualizations:

| Visualization | Chart Type | Analysis |
|---|---|---|
| Regional Sales Performance | Clustered Bar Chart | State-wise sales comparison |
| Product Category Performance | Pie Chart | Category-wise sales contribution |
| Product Profitability | Clustered Bar Chart | Subcategory-wise profit |
| Monthly Sales Trend | Line and Column Combo Chart | Monthly sales and profit trends |
| Store Performance | Clustered Bar Chart | Store-wise sales comparison |
| KPI Cards | Cards | Overall business performance |

Interactive filters and slicers help users explore the sales data from different perspectives.

## 🔍 Business Analysis and Insights

### 1. Descriptive Analysis – What Happened?

- Total sales reached ₹29,45,623 with a total profit of ₹5,88,973.30.
- The overall profit margin was approximately 19.99%.
- Gujarat recorded the highest state-wise sales of ₹5,08,544.
- Cycling was the highest-selling category, generating ₹5,67,298.
- Mountain Bikes generated the highest subcategory profit of ₹1,16,275.

### 2. Diagnostic Analysis – Why Did It Happen?

- Gujarat performed better than other states in total sales.
- Cycling and Camping & Hiking contributed strongly to overall sales.
- Sales decreased by approximately 10.7% in 2024 compared with 2023.
- Swimming recorded the lowest category-wise sales of ₹93,284.
- Differences in regional and product performance highlight areas that require further investigation.

### 3. Predictive Analysis – What May Happen Next?

- Cycling may continue to be an important category for future sales growth.
- Gujarat and Telangana could remain important states for business focus.
- August recorded strong sales performance in both years and should be monitored.
- Swimming may require additional attention to improve future sales.
- The sales decline in 2024 indicates the need for regular monitoring of monthly sales performance.

### 4. Prescriptive Analysis – What Should Be Done Next?

- Focus on improving sales in states with lower sales performance.
- Maintain sufficient stock availability for high-performing products such as Mountain Bikes and Tents.
- Introduce suitable offers and promotions to improve Swimming category sales.
- Investigate the reasons behind the sales decline in 2024.
- Verify store location details and sales target information to improve reporting accuracy.

## 📈 Key Business Performance Findings

| Performance Indicator | Result |
|---|---|
| Highest Sales State | Gujarat – ₹5,08,544 |
| Lowest Sales State | West Bengal – ₹1,47,092 |
| Highest Sales Category | Cycling – ₹5,67,298 |
| Lowest Sales Category | Swimming – ₹93,284 |
| Highest Profit Subcategory | Mountain Bikes – ₹1,16,275 |
| Lowest Profit Subcategory | Swim Goggles – ₹17,918.30 |
| Highest Sales Store | Decathlon Ghatkopar – ₹5,08,544 |
| Lowest Sales Store | Decathlon Anna Nagar – ₹1,47,092 |

## 💡 Conclusion

This project helped me understand how to analyse business sales data using Microsoft Excel and Power BI. I performed data cleaning, data transformation, data modelling and DAX calculations to prepare the dataset for analysis.

I developed an interactive dashboard to evaluate sales performance across different states, cities, stores and product categories. The analysis identified Gujarat and Cycling as strong sales performers and highlighted a decrease in sales during 2024.

I also explored all four types of data analysis to understand business performance and suggest possible improvements.

Overall, this project improved my practical knowledge of data analytics, Power BI, DAX, data visualization and business decision-making. I also used AI tools as learning support to understand technical concepts and complete the project.

## 📁 Project Files

The repository contains the following project materials:

- Excel dataset
- Power BI project file (.pbix)
- Final project report (PDF)
- Dashboard screenshots
- README documentation

## 👨‍💻 About Me

I am an **Aspiring Data Analyst** interested in transforming raw data into meaningful insights and supporting business decisions through data analytics.

I am continuously improving my skills in:

- Microsoft Excel
- SQL
- Python
- Power BI
- Data Visualization
- Business Analytics
- AI Tools for Data Analysis

I created this project as part of my practical learning journey to build my Data Analyst portfolio.

**Thank you for visiting my project!**

If you find this project useful, feel free to explore the repository and share your feedback.
