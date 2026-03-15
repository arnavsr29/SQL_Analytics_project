# SQL Data Analytics Project (SQL Server)

## Project Overview

This project demonstrates a full SQL analytics lifecycle using SQL Server and SSMS.
It covers everything from data ingestion and validation to exploratory analysis, KPI reporting, trend analysis, and customer/product segmentation.

The project simulates how data analysts answer business questions using SQL Server and structured SQL queries, with a focus on actionable insights rather than just data retrieval.

## Key Analytics Performed

- Exploratory Data Analysis (EDA) — dimensions, measures, and date ranges
- KPI & Metrics Calculation — total sales, revenue, quantity, customer/product counts
- Time-based Analysis — change-over-time, cumulative growth, performance trends
- Segmentation & Part-to-Whole Analysis — top customers/products, revenue contribution, customer/product tiers

## Folder Structure
SQL-Data-Analyst-Portfolio\
├── data/                     # CSV and raw SQL files\
│   ├── gold.dim_customers.csv\
│   ├── gold.dim_products.csv\
│   └── gold.fact_sales.csv\
│\
├── sql/                      # SQL scripts executed in sequence\
│   ├── 01_init_database.sql\
│   ├── 02_database_exploration.sql\
│   ├── 03_dimensions_exploration.sql\
│   ├── 04_date_range_exploration.sql\
│   ├── 05_measures_exploration.sql\
│   ├── 06_magnitude_analysis.sql\
│   ├── 07_ranking_analysis.sql\
│   ├── 08_change_over_time_analysis.sql\
│   ├── 09_cumulative_analysis.sql\
│   ├── 10_performance_analysis.sql\
│   ├── 11_data_segmentation.sql\
│   ├── 12_part_to_whole_analysis.sql\
│   ├── 13_report_customers.sql\
│   └── 14_report_products.sql\
│\
├── results/                  # Example outputs\
│   ├── Top_Customers.png\
│   ├── Top_Products.png\
│   └── Revenue_Contribution.png\
└── README.md

## Tools & Technologies
- SQL Server (Developer / Express Edition)
- SQL Server Management Studio (SSMS)
- T-SQL, Window Functions, CASE Statements
- Aggregations, Ranking, Part-to-Whole Analysis

## Key Analytics Performed
- Exploratory data analysis
- KPI and metric calculations
- Time-based trend analysis
- Cumulative and part-to-whole analysis
- Customer and product segmentation

## How to Run & Verify everything
1. Create database in SQL Server
2. Import datasets
3. Schema Validation as it correct data types and date columns etc.
4. Execute SQL scripts in SSMS
5. Review results in the results folder

## Business Value
- Identifies top-performing products and customers.
- Highlights key revenue contributors for strategic focus.
- Supports data-driven decisions using KPIs and segmentation.
- Provides a reproducible SQL workflow for business analytics.

## Biggest Insight
A small percentage of customers/products contributed to a large portion of revenue, highlighting optimization opportunities.
