# Retail Orders ETL & Sales Analysis

## 📊 Project Overview
End-to-end data pipeline for retail order analytics using Python for ETL and Microsoft SQL Server for database and queries. The project automates data extraction, transformation, loading, and delivers actionable sales and profit insights.

## 🛠 Tools & Technologies Used
- Python (Pandas, SQLAlchemy, zipfile)
- Microsoft SQL Server
- SQL (analysis, aggregation, window functions)

## ⚙️ Main Steps
- Downloaded and unzipped orders dataset in Python
- Cleaned data: handled nulls, renamed columns, derived new KPIs (profit, sale price)
- Converted date columns and dropped unnecessary features
- Loaded processed DataFrame into SQL Server table (`df_orders`)
- Wrote advanced SQL queries:
  - Top 10 revenue products
  - Top 5 selling products by region
  - Month-over-month sales growth for 2022/2023
  - Monthly sales highs by product category
  - Subcategory with highest year-on-year profit growth

## 🚀 Key Insights
- Automated pipeline enables quick refresh and analysis
- SQL analytics surface high revenue drivers and reveal monthly/category trends

## 🔗 How to Run
1. Ensure Python 3.x, `pandas`, `sqlalchemy`, `kaggle`, and access to SQL Server.
2. Edit credentials in the .py script as needed for your local SQL Server.
3. Run `orders-data-analysis.py` to process, clean, and load data.
4. Run `sql_code.sql` in SQL Server Management Studio for analysis.

## 📄 Files
- `orders-data-analysis.py` — ETL & data prep script
- `sql_code.sql` — Analysis queries
- `.gitignore` — Ignore .pyc, .DS_Store, csv, etc.

## 📫 Contact
[Your LinkedIn] | [Your Email]

---

> **Recruiters:**  
See the full ETL script and query file for practical, production-friendly data analysis skills—ready to deliver insights from real business data!
