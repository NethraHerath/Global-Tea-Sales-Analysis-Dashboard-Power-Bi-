📊 Global Tea Sales Analysis Dashboard (Power BI)

🚀 Overview

This project focuses on analyzing global tea sales data using Power BI to uncover meaningful business insights. The dashboard transforms raw transactional data into an interactive and decision-support tool, helping to understand revenue trends, customer behavior, product performance, and operational efficiency.

🎯 Objectives

Analyze revenue across regions, customer types, and product categories
Track business performance using KPIs and time-based metrics
Identify top-performing customers and products
Evaluate operational efficiency (shipment delays, due days)
Detect customer churn and profitability patterns

🛠️ Tools & Technologies

Power BI Desktop
DAX (Data Analysis Expressions)
Data Modeling (Star Schema)
Excel Dataset

🧩 Data Model

The dataset was structured into a star schema:

Fact Table: Orders (renamed as Fact)
Dimension Tables: Region, Customer, Products, Status
Custom Calendar Table:
Year, Month, Month Number
Fiscal Year (April–March)
Fiscal Quarter

📈 Key Features & Analysis

🔹 Revenue Analysis

Total Revenue and Product Revenue tracking
Year-to-Date (YTD) and Month-to-Date (MTD) calculations
Actual vs Target comparison (Target = Product Revenue × 1.1)
🔹 Customer Insights

Customer Contribution % to total revenue
Ranking of customers using dynamic Top N analysis
Segmentation of Direct vs Indirect customers
🔹 Product Performance

Product ranking based on revenue
Revenue classification (Small / Medium / Large)
Category-level performance analysis
🔹 Operational Metrics

Average Due Days and Total Due Days
On-time shipment %
Order status tracking (Completed vs Overdue)
🔹 Advanced Analysis

Churn Analysis: Identified customers inactive in the current year
Profitability Segmentation:
Scatter plot (Quantity vs Profit Margin %)
High-volume vs high-margin product insights

📊 Dashboard Highlights

Interactive filters (Region, Customer Type, Year)
KPI cards for quick performance tracking
Drill-down capabilities using hierarchical data
Clean and user-friendly report design

🔐 Security

Implemented Row-Level Security (RLS):
Regional Managers → Access to assigned regions
Customer Managers → Access to assigned customer types

💡 Key Insights

A small group of customers contributes a significant portion of total revenue
Some high-volume products generate lower profit margins
Shipment delays directly impact operational performance metrics
Revenue trends vary significantly across regions and customer segments

⭐ Acknowledgment

This project was developed as part of a hands-on data analytics exercise to strengthen practical skills in Power BI and business analysis.
