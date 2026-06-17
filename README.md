# E-commerce SQL & Customer Segmentation

## Overview
End-to-end data analytics project analysing 1M+ retail transactions using SQL, Python, and Tableau. Built a customer segmentation model and interactive dashboard to surface revenue patterns and business insights.

## Dashboard
[View Live Tableau Dashboard](https://public.tableau.com/app/profile/parthavi.shah3285/viz/E-commerceRetailAnalyticsDashboard/Dashboard1)

## Dataset
[Online Retail II - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
- 1,067,371 transactions across 37 countries (2009–2011)
- 5,878 unique customers after cleaning

## Tools & Technologies
- **SQL** — SQLite, CTEs, window functions, aggregations
- **Python** — Pandas, scikit-learn, Plotly
- **Tableau Public** — Interactive dashboard

## Key Analysis

### SQL
- Monthly revenue trends using date aggregations
- Top 10 products by revenue
- Customer activity patterns using window functions
- Country-level revenue distribution

### Machine Learning
- RFM feature engineering (Recency, Frequency, Monetary)
- K-Means clustering (k=4) to segment 5,878 customers
- Identified 4 behavioural groups: Lost, Loyal, VIP, Champions
- Champions (0.07% of customers) averaged £437K spend

## Key Findings
- Revenue peaks in November both years — strong seasonality
- UK dominates with ~85% of total revenue
- Top 0.07% of customers (Champions) drive disproportionate revenue
- Regency Cakestand 3 Tier is the top revenue-generating product

## Repository Structure
```
retail-sql-analysis/
├── retail_sql_analysis.ipynb
├── tableau_monthly_revenue.csv
├── tableau_top_products.csv
├── tableau_country_summary.csv
└── README.md
```
