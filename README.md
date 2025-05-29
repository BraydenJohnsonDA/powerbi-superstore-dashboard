# Power BI Sales Dashboard – Superstore Dataset  
*A data-driven portfolio project analyzing regional and customer sales trends*

This project is a business intelligence dashboard created in Power BI using a sample Superstore dataset. It provides key sales insights across time, customer segments, product categories, and geographic regions. The goal was to simulate the kind of data-driven storytelling expected in a business analyst or data analyst role.

## Overview

The dashboard consists of three pages:

### 1. Sales Trends Over Time
- **Visuals:** Line chart of monthly sales by year, year slicer
- **Purpose:** Identify seasonal trends and revenue growth patterns
- **Insight:** Sales increased steadily from 2014 to 2017, with November and December consistently outperforming other months.

### 2. Regional and Category Performance
- **Visuals:** Matrix of region-wise sales/profit, bar charts for product category and sub-category profitability, slicers for segment and region
- **Purpose:** Assess profitability by region and product category
- **Insight:** Technology products generated the highest profit. Certain sub-categories like Tables had negative profit margins.

### 3. Customer Overview
- **Visuals:** Top 10 customers by sales, segment-based customer count, slicers for year and region
- **Purpose:** Understand customer distribution and key accounts
- **Insight:** High-value customers are not limited to the Corporate segment, and customer count varies significantly by region and segment.

## Key Insights

- **Seasonality:** Sales increased steadily from 2014 to 2017, with November and December consistently outperforming other months. These trends suggest strong year-end buying behavior.
- **Regional Performance:** The West and East regions contributed the highest sales, while the South had the lowest profit margins.
- **Category Profitability:** Technology outperformed other categories in both sales and profit. However, sub-categories such as Tables and Bookcases showed consistent losses.
- **Customer Segmentation:** High-value customers were distributed across all segments (Consumer, Corporate, and Home Office), not just Corporate. This suggests untapped opportunities for customer loyalty initiatives.

## Tools Used

- **Power BI Desktop**
- **Superstore dataset (Kaggle)**
- **Excel** (for data checks)
- **GitHub** for version control and portfolio publication

## Folder Structure

```
sales-dashboard-superstore/
├── assets/                          # Screenshots of dashboard visuals
│   ├── sales_trends.png
│   ├── regional_performance.png
│   ├── customer_overview.png
├── Sales_Dashboard_Superstore.pbix  # Power BI dashboard file
├── README.md                        # Project documentation
```

## How to View

1. Download the `.pbix` file from this repository.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free to use, no login required).
3. Explore each tab to view interactive dashboards and key metrics.

## About This Project

This is the fifth project in my self-taught data analyst portfolio. It showcases my ability to:
- Work with real-world business data
- Build multi-page dashboards in Power BI
- Perform regional, product-level, and customer-level analysis
- Extract insights that drive business recommendations
