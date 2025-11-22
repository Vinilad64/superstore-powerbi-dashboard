# Retail Sales Analysis Dashboard -- Power BI

## 📌 Project Overview

This project analyzes sales performance using the Superstore dataset. It includes interactive visualizations, KPIs, customer insights, and category-level profitability analysis.

## 📥 Dataset

Superstore Dataset (Kaggle)
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## 🔧 Tools Used

-   Power BI Desktop
-   Power Query
-   DAX
-   Excel
-   GitHub

## 📊 Dashboard Features

-   Total Sales, Total Profit, Profit Ratio, AOV
-   Sales Trend Analysis
-   Profit by Category & Sub-category
-   Regional/State Sales Map
-   Top 10 Products by Sales
-   Customer Segment Analysis
-   Discount vs Profit Impact

## 🧮 Key DAX Measures

-   Total Sales = SUM(Superstore[Sales])
-   Total Profit = SUM(Superstore[Profit])
-   Profit Ratio = DIVIDE([Total Profit], [Total Sales]) 
-   AOV = DIVIDE([Total Sales], DISTINCTCOUNT(Superstore[Order ID])) 

## 📑 Files Included

-   Retail Sales Analysis Dashboard.pbix
-   Sales_Analysis_Summary_Report.pdf
-   Dataset.csv (from Kaggle)
-   Screenshots
-   README.md

## 📈 Key Insights

-   Technology is the most profitable category.
-   West region leads in both sales and profit.
-   High discounts reduce margins significantly.
-   Top customers contribute a major share of total sales.

## 🚀 How to Use

1.  Download the ".pbix" file.
2.  Open it in Power BI Desktop.
3.  Interact with visuals to explore insights.

## 📧 Author

Data Science Portfolio Project Created using Power BI and Python for documentation.
