# saas-churn-sql-analysis

SQL portfolio project analyzing SaaS subscription, churn, and feature adoption.

## SaaS Churn & Engagement Analysis

This project analyzes a SaaS subscription dataset to understand **customer behavior, churn, and feature engagement**. The goal is to demonstrate applied **SQL and data analysis skills** relevant to business decision-making.

The analysis was conducted using **DuckDB SQL** inside a Kaggle notebook.

## Dataset

The dataset is publicly available on Kaggle: [SaaS Subscription & Churn Analytics Dataset](https://www.kaggle.com/datasets).  

It includes 5 tables:

- `accounts` – customer metadata  
- `subscriptions` – subscription lifecycles, plan tiers, revenue  
- `feature_usage` – daily product usage logs  
- `support_tickets` – support interactions  
- `churn_events` – churn dates and reasons  

## Key Questions & Metrics

1. **Active Subscribers per Month**  
   - Counts total active customers each month  
   - Insight: Tracks overall growth and retention trends  

2. **Monthly Churn Rate**  
   - Percentage of active users that churned per month  
   - Insight: Shows periods of high churn and opportunities for retention  

3. **Plan-Level Churn Rate**  
   - Churn rate per plan tier (e.g., Pro, Enterprise)  
   - Insight: Identifies which subscription tiers are at risk  

4. **Feature Adoption**  
   - Number of unique users interacting with each product feature per month  
   - Insight: Highlights popular features and engagement trends  

5. **Support Tickets vs Churn**  
   - Analyzes correlation between support ticket count and churn  
   - Insight: Helps understand if users needing more support are more likely to churn  

## Tools & Skills

- **SQL** (DuckDB) for querying and aggregating data  
- **Data cleaning & transformation** (joins, date truncation, aggregations)  
- **Portfolio-ready metrics** suitable for SaaS business analytics  

## Insights

- High-tier plans (Enterprise) show slightly higher churn than Pro  
- Features like `Dashboard` and `Reports` have the highest monthly adoption  
- Accounts with more support tickets tend to have higher churn, indicating friction points  
- Active subscribers are growing steadily month over month, but churn spikes in certain months  

## How to Run

1. Open the notebook `saas_churn_analysis.ipynb` in Kaggle  
2. Add the dataset input from Kaggle  
3. Run each cell to reproduce SQL queries and metrics  

---

*This project is part of Fred Olivares' data analytics portfolio.*
