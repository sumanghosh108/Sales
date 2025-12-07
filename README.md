# Sales Analytics Project
This repository contains an end-to-end Sales Analytics Project using SQL, Power BI, and DAX.
The project explores sales performance across multiple regions, countries, item types, sales channels, and time periods.
It includes structured queries, DAX measures, calculated columns, and a complete Power BI dashboard design.
## 1. Project Overview
The dataset includes sales transactions with fields such as:
- Region & Country
- Item Type
- Sales Channel (Online / Offline)
- Order Priority
- Units Sold, Unit Price, Unit Cost
- Total Revenue, Total Profit
- Order Date & Ship Date

This project focuses on:
- SQL-based data exploration and analysis
- Interactive Power BI dashboard creation
- Advanced analytics using DAX
- Business insights through rich visualizations
## SQL
SQL queries addressing key business questions such as:
**Data Exploration**
- Display all records
- Retrieve unique regions
- Count total orders

**Profit & Revenue Analysis**
- Revenue by region
- Profit by country (sorted)
- Orders with profit > 5000
- Loss-making orders (Unit Cost > Unit Price)

**Date-Based Queries**
- Orders between specific dates
- Latest 5 orders
- Monthly cost and profit

**Categorization & Ranking**
- Profit-level segmentation (High, Medium, Low)
- Top 5 countries by profit
- Top 10 orders by revenue
## Dashboard
**Slicers:**
- Region
- Country
- Item Type
- Sales Channel

**KPI Cards:**
- Total Revenue
- Total Profit
- Profit Margin (%)
- Total Orders
- Profit Contribution (%)
## DAX
**Measures**
Online Sales Profit,
Offline Sales Profit,
Revenue for High / Medium Priority Orders,
Profit Contribution % by Region,
Total Profit by Item Type,
Top 5 Countries by Profit,
Top 3 Item Types by Revenue

**Calculated Columns**
Profit per Unit,
Profit Category (High / Medium / Low),
Profit Margin (%),
Shipping Duration (days),
Year extracted from Order Date
## Visualizations
- Total Profit by Country (Top 5 highlighted)
- Profit Contribution (%) by Region
- Online vs Offline Profit Comparison
- Revenue by Order Priority
- Item Type vs Profit vs Margin
- Yearly Revenue Trend
- Average Shipping Duration
- Profit Category Distribution
- Region–Country profit matrix
- Combined bar-line charts
- Heat Map & Tree Map
- Revenue trend by Sales Channel
## Summary
This project demonstrates an end-to-end analytics workflow:
SQL for detailed data exploration
Power BI for interactive reporting
DAX for advanced calculations
Data storytelling through visual analysis
