# Customer Shopping Behavior Analysis
> End-to-end retail analytics project using Python, SQL, and Power BI

## Business Problem
A retail business wants to understand what drives customer spending,
which segments are most valuable, and whether their subscription
program is delivering ROI.

## Key Findings
- Subscription status had negligible impact on per-transaction spend
  ($59.49 subscribers vs $59.54 non-subscribers) — suggests subscription
  value lies in purchase frequency, not basket size
- Identified 100% column redundancy between discount_applied and
  promo_code_used — flagged as data quality issue
- Young Adults generated the highest total revenue across all age segments
- Repeat buyers (5+ purchases) showed strong subscription uptake

## Tools & Approach
| Step | Tool | Purpose |
|------|------|---------|
| Data Cleaning | Python, Pandas | Null handling, feature engineering |
| Business Analysis | SQL, PostgreSQL | 10 business questions answered |
| Dashboard | Power BI, DAX | Executive KPI reporting |

## Files
- `Customer_Shopping_behaviour_analysis.ipynb` — Python EDA notebook
- `Customer Behaviour Analysis SQL.sql` — 10 SQL business queries
- `Customer Behaviour Analysis Report.pbix` — Power BI dashboard

## Dashboard Preview
<img width="1338" height="727" alt="{D7BD7E4F-3A5F-415C-8451-6310C73D1648}" src="https://github.com/user-attachments/assets/7b43edaf-a6e5-475a-99aa-75d789375c4d" />


## How to Run
1. Load `customer_shopping_behavior.csv` into PostgreSQL
2. Run SQL file for business queries
3. Open .pbix file in Power BI Desktop
