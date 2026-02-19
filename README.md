# Customer-behavior-Analysis

This project analyzes customer shopping behavior to identify purchasing patterns, revenue drivers, and actionable business insights.
The goal is simple: turn raw transaction data into decisions using SQL, Python, and Power BI.
This is not a toy dataset walkthrough. It follows a real analytics workflow:
data → queries → analysis → visualization → business recommendations.

Business Problem
Businesses struggle to understand:
Which customers drive the most revenu
What products/categories perform best
How purchasing behavior changes across demographics and time
This project answers those questions using structured analysis instead of guesses.

Dataset
File: customer_shopping_behavior.csv
Contains customer-level shopping data including:
Customer demographic
Product categories
Purchase amounts
Frequency and behavioral attributes
Dataset is cleaned and analyzed using SQL and Python before visualization.

Tools & Technologies
SQL – Data extraction, aggregation, CTEs, business logic
Python (Pandas, NumPy, Matplotlib) – Cleaning, EDA, trend analysis
Power BI – Interactive dashboards and KPIs
Google Colab – Analysis and documentation


Project Structure
customer-trends-data-analysis/
│
├── customer_shopping_behavior.csv      # Raw dataset
├── customer_behavior_sql_queries.sql   # SQL analysis queries
├── Customer_Shopping_Behavior_Analysis.ipynb  # Python analysis
├── customer_behavior_dashboard.pbix    # Power BI dashboard

Analysis Performed
SQL
Revenue by category and customer segment
High-value customer identification
Purchase frequency analysis
Aggregations using CTEs and conditional logic

Python
Data cleaning and validation
Exploratory Data Analysis (EDA)
Distribution and trend analysis
Insight validation against SQL outputs

Power BI
Customer segmentation dashboards
Revenue and category performance KPIs
Interactive filters for demographics and behavior

Key Insights:
A small percentage of customers contribute a disproportionate share of revenue
Certain categories consistently outperform others across demographics
Purchase frequency strongly correlates with average order value
(Details are visualized in the Power BI dashboard.)





