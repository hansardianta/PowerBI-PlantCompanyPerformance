# Plant Company Performance Analysis with PowerBI

## Project Overview

This repository showcases a comprehensive **Business Intelligence (BI)** project focused on analyzing plant sales data. The goal of this project was to transform raw sales and hierarchy data into a dynamic, interactive dashboard to uncover key sales trends, measure profitability, and provide actionable insights to inform business strategy.
The analysis covers various dimensions of the sales process, including geographical performance, product popularity and profitability, and customer account metrics.

## Key Features

* **Data Modeling:** Implemented a star schema data model connecting sales facts with Product and Account dimensions.
* **Key Performance Indicators (KPIs):** Calculated and visualized core metrics such as **Total Sales (USD)**, **Quantity Sold**, and **Gross Profit**.
* **Interactive Dashboard:** A complete interactive dashboard created in **Power BI** for drill-down analysis.

## Tools

| Category | Tool/Technology | Description |
| :--- | :--- | :--- |
| **Data Source** | CSV (Simulated data) | Raw sales, product hierarchy, and account data files. |
| **Analysis & BI** | **Power BI Desktop** (`.pbix` file) | Used for data cleaning, modeling (DAX), and dashboard development. |
| **Database/Schema** | Relational Star Schema | Data was structured into **Fact** (Sales) and **Dimension** (Plant Hierarchy, Accounts) tables. |

## Data Sources

The analysis is based on three primary CSV files:

1.  `Plant_DTS.xls - Plant_FACT.csv`: The central fact table containing transactional data: `Sales_USD`, `quantity`, `Price_USD`, `COGS_USD`, and `Date_Time`.
2.  `Plant_DTS.xls - Plant_Hierarchy.csv`: A dimension table detailing product attributes like `Product_Family`, `Product_Group`, and `Produt_Type`.
3.  `Plant_DTS.xls - Accounts.csv`: A dimension table containing customer details, including `Account` name, `country_code`, and geographical coordinates.

## Key Insights and Strategic Findings

* **Geographical Performance Decline Analysis:** Identified countries exhibiting the most significant Year-to-Date (YTD) sales performance decline to strategically focus promotional and sales recovery tactics.
* **Product-Market Growth Drivers:** Determined the top-contributing products driving monthly sales growth, cross-referencing performance with geographical analysis to identify the most suitable product-country pairings for targeted market penetration.
* **High-Value Account Segmentation:** Implemented customer account segmentation to pinpoint high-value and high-profitability recurring buyers, enabling focused relationship management and maximizing company revenue.

## Getting Started

To view the interactive report:

1.  Download the `plantSalesproject.pbix` file.
2.  Ensure you have **Power BI Desktop** installed on your machine.
3.  Open the `.pbix` file with Power BI Desktop. The data sources are linked as CSV files, so they should load automatically if the CSVs are in the same directory (or you can repoint them in Power Query).

## Future Enhancements

* **Time Intelligence:** Implement more advanced time-series analysis to forecast future sales and identify year-over-year growth.
* **What-If Analysis:** Integrate Power BI parameters to allow users to simulate different pricing or COGS scenarios.
* **External Data:** Incorporate weather data or marketing spend to evaluate their correlation with sales performance.
