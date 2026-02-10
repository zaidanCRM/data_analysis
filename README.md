# data_analysis

SQL Sales & Customer Intelligence Analytics
📌 Project Overview
This project focuses on transforming raw transactional and customer data into actionable business intelligence. 
Using Advanced SQL techniques, I developed a series of queries to analyze sales trends, product performance, and customer behavior. 
The goal is to provide a 360-degree view of the business to support data-driven decision-making.

🛠️ Tech StackDatabase: 

SQL Server (T-SQL)Concepts: Window Functions, Common Table Expressions (CTEs), Data Segmentation, Time-Series Analysis, Data Aggregation.

🚀 Key Analyses & Business Insights1. 

Sales Trend AnalysisDeveloped time-series queries to track monthly revenue growth and cumulative sales.
Impact: Allows stakeholders to identify seasonality and monitor progress toward annual targets using Moving Averages and Running Totals.

2. Product Performance & BenchmarkingCreated a product intelligence module that compares yearly sales against a product's historical average.
Technique: Utilized LAG() functions for Year-over-Year (YoY) growth analysis and window functions for performance benchmarking.
Impact: Identifies "Rising Stars" (increasing sales) and "Underperformers" (below-average sales).

3. Customer Segmentation (VIP vs. Regular)Built a customer clustering model to segment the database based on Lifespan and Monetary Value.
4. Segments: * VIP: Long-term customers ($\ge 12$ months) with high spend ($> €5,000$).
5. Regular: Established customers with steady spending.New: Recent acquisitions (lifespan $< 12$ months).
6. Impact: Enables targeted marketing campaigns and improves Customer Relationship Management (CRM) strategies.
7. Comprehensive Customer ReportThe final output consolidates multiple KPIs into a single unified view, including:Recency: Months since the last purchase.
8. AOV: Average Order Value per customer.Engagement: Unique products purchased and monthly spending averages.
9. 📂 Repository Structuresales_customer_analysis.sql: Contains the full SQL script with documented logic.README.md: Project documentation and business context.
10. How to UseEnsure you have the gold schema (dim_customers, dim_products, fact_sales) populated.Run the scripts in a SQL environment (SQL Server Management Studio or Azure Data Studio).The queries are modularized; you can run specific sections depending on the required insight.
