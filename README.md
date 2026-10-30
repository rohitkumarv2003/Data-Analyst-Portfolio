# Rohit

**Data Analyst | SQL, Python, Power BI, Excel, Databricks**

I am a data analyst with a BSc (Hons) in Electronics, working mainly in SQL, Python and Power BI. I build projects end to end, from cleaning raw data to modelling, analysis and dashboards, with a focus on business analytics and quantitative finance. Leading college events and sponsorships taught me to communicate findings clearly to non-technical audiences.

[Email](mailto:rohitkumarv2003@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rohit-kumar-4b454223b)

---

## Projects

### SQL and Database Analysis

| Project | Description | Tech |
|---------|-------------|------|
| [Indian Financial Fraud Analysis](https://github.com/rohitkumarv2003/Financial-Fraud-Analysis) | 35 advanced SQL challenges covering fraud pattern detection, cohort analysis, Benford's Law and precision/recall-style queries | PostgreSQL, PowerBI |
| [Overnight vs Intraday Returns, Indian Equities](https://github.com/rohitkumarv2003/Stock-Market-Investment-Analysis---Overnight-vs-Intraday) | Replication of Lou, Polk and Skouras (JFE 2019) on Indian market data | PostgreSQL, recursive CTEs, window functions, `LAG()` |
| [Netflix Dataset SQL Analysis](https://github.com/rohitkumarv2003/Netflix-Insights) | Business-style questions on content, genres, countries and release trends | PostgreSQL |

### BI Dashboards

| Project | Description | Tech |
|---------|-------------|------|
| [E-Com End-to-End](https://github.com/rohitkumarv2003/E-Com-End-to-End-Using-Databricks-Python-PowerBI) | Messy e-commerce data taken through a medallion pipeline into a Power BI dashboard | Databricks, Python, Power BI |
| [Nykaa Marketing Campaign Analysis](https://github.com/rohitkumarv2003/Nykaa-Marketing-Campaign) | Campaign ROI, channel performance, conversions and customer segments | Power BI |
| [Sales and HR Dashboard](https://github.com/rohitkumarv2003/Sales-Analysis-Excel) | Interactive pivot-table dashboard on a Kaggle store dataset | Excel |
| [Live-API based Weather Dashboard](https://github.com/rohitkumarv2003/Weather-Report-Dashboard-PowerBI-) | API-fed live weather dashboard of 6 Indian cities | Rest API, Power BI |

### Python, EDA and Data Engineering

| Project | Description | Tech |
|---------|-------------|------|
| [E-Com ETL and EDA](https://github.com/rohitkumarv2003/E-Com-End-to-End-Using-Databricks-Python-PowerBI) | `EDA.ipynb`, `bronze_to_silver.py` and `silver_to_gold.py` | Python, Databricks |

---

## Dashboard Gallery

### Nykaa Marketing Campaign Analysis (Power BI)

![Nykaa campaign dashboard](screenshots/overview_dashboard.png)

Campaign produced 1.92 times of profit of its ad spends in `college students` category with net revenue of `₹5.8 billion`. 

### Live Weather Dashboard

![Live Weather dashboard](screenshots/weather_report_dashboard.png)

Live API-based Weather dashboard of 6 Indian cities that automatically updates on 5 minutes or after refreshing dashboard.

### Financial Fraud Analysis

![Executive dashboard](screenshots/executive_dashboard.png)

![Merchant dashboard](screenshots/merchant_dashboard.png)

---

## Featured: E-Com End-to-End

**Problem:** a raw e-commerce CSV with quality issues that made it unusable for reporting.

**Approach:**

```
Raw CSV -> Bronze (raw ingest) -> Silver (cleaned) -> Gold (business-ready) -> Power BI
```

- Exploratory analysis in Python to profile nulls, duplicates, outliers and data types
- ETL in `bronze_to_silver.py` (cleaning, typing, deduplication) and `silver_to_gold.py` (aggregations)
- Medallion architecture on Databricks with materialized views
- Power BI dashboard connected to the gold layer

## Featured: Indian Financial Fraud Analysis

- 35 business-framed SQL problems in the style of DataLemur and StrataScratch
- Covers fraud pattern detection, cohort analysis, Benford's Law checks and confusion-matrix-style precision/recall queries
- Hosted on Supabase, with an ERD designed in dbdiagram.io

---
