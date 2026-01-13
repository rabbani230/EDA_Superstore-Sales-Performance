Exploratory Data Analysis: Superstore Sales Performance
---
Business Overview

Retail management needs to understand how sales and profitability evolve over time, how performance differs across regions and categories, and which products drive profit consistently.
This project uses exploratory data analysis (EDA) to uncover patterns, compare segments, and identify actionable insights using historical Superstore sales data.
***
Business Questions Addressed
- How do sales trend over time, and are there recurring seasonal patterns?
- How does sales performance differ across regions and product categories?
- Which products drive profitability, and how does this vary by region and category?
***
Analytical Objectives

To address the above questions, this analysis aims to:
- Analyze monthly sales trends from 2014 to 2017 to identify growth patterns and seasonality.
- Compare total sales across regions and product categories to highlight performance disparities.
- Identify the top profit-contributing products and assess how profitability concentration changes across segments.
- Enable interactive exploration using slicers to support ad-hoc business questions.
***
EDA Approach & Visual Analysis

1️⃣ Sales Trend Analysis

Question: Are sales growing over time, and do certain months consistently outperform others?

Method:
- Aggregated sales across 2014–2017 at a monthly level
- Used a line chart to explore overall sales growth and seasonal fluctuations
- Added a time slicer (Jan 2014 – Dec 2017) to isolate specific periods

Key Insight:
- Total sales increased from 2014 to 2017, representing 51.4% overall growth as indicated clear upward trend.
- Sales peaked in fourth quarter of each year, indicating a recurring seasonal high with approximately $118K in November 2017 as the highest sales recorded.

2️⃣ Regional & Category Performance Comparison

Question: Which regions and product categories are driving sales, and where are underperforming areas?

Method:
- Compared sum of sales across regions and product categories (clustered columns)
- Enabled slicers for Region and Category to support comparative analysis

Key Insight:
- The West region generated the highest total sales at approximately $725K, while the South region recorded the lowest sales at around $391K.
- Across categories, Technology was the top-performing category, accounting for 36.4% of total sales.

3️⃣ Profitability & Product-Level Exploration

Question: Which products generate the highest profit, and how they differs according to region and category?

Method:
- Ranked products by sum of profit
- Displayed Top 5 products using a horizontal bar chart
- Dynamic filtering via Region and Category slicers

Key Insight:
- The most profitable product generated approximately $25,200 in total profit, putting it as profit leader in Technology category for all regions except for South.
- The top 5 products accounted for 17% of total profit, indicating profit concentration risk.
***
Tools & Techniques

Microsoft Excel:
- Pivot Tables & Pivot Charts
- XLOOKUP & index match
- Slicers for interactive filtering
- Exploratory data analysis principles
***
Outcome

This EDA dashboard provides management with a high-level exploratory view of sales and profitability, supporting:
- Strategic planning
- Performance benchmarking
- Hypothesis generation for deeper analysis (e.g., pricing, promotions, or supply chain efficiency)

<img width="1221" height="802" alt="Dashboard_screenshot" src="https://github.com/user-attachments/assets/1be9d019-a457-4d99-b06b-9aa1f2780756" />
