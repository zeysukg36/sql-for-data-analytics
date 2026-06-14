# 📊 Production-Ready Data Analytics & Engineering Pipelines

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-8A2BE2?style=for-the-badge&logo=fastapi&logoColor=white)

An end-to-end data analytics portfolio demonstrating modern data engineering workflows: migrating relational database architectures (SQL) and live semi-structured web endpoints (REST APIs) into optimized analytical pipelines using Python and Pandas.

---

## 🎯 Repository Architecture & Core Modules

The repository is structured into isolated production modules, each targeting a critical phase of the modern business intelligence workflow:

### 📦 01. SQLite Sales Analysis & Business Intelligence
* **Core Stack:** SQLite, Python `sqlite3`, Pandas, Seaborn, Matplotlib.
* **Pipeline:** Relational Database (SQL) ➡️ Pandas DataFrame ➡️ Automated Visual Reports.
* **Analytical Scope:** Employs relational operators (`SELECT`, `WHERE`, `JOIN`, `GROUP BY`, `ORDER BY`) to process raw database transactional files (`ybs_shop.sqlite`) and extract executive business performance metrics, regional revenue distributions, and market penetration insights.

### 🌐 02. Remote Data Extraction & API JSON Normalization
* **Core Stack:** Python `requests`, Pandas, JSON Parsing Utilities.
* **Pipeline:** Live Web REST API Endpoint ➡️ Semi-Structured JSON ➡️ Flat Tabular DataFrames.
* **Engineering Scope:** Automates data ingestion by handling network requests to remote web endpoints, decoding complex nested JSON payloads, and applying flattening techniques (`pd.json_normalize`) to transform unstructured server responses into clean, analytics-ready tabular formats.

---

## 🛠️ Technical Capabilities Demonstrated

* **Data Engineering & Ingestion:** Automating REST API calls, decoding network responses, error-handling with `try/except RequestException`, and managing resource connections.
* **Database Query Optimization:** Structuring complex multi-table joins, implementing granular aggregations, and filtering transactional data directly at the database layer.
* **Data Rectangularization:** Parsing multi-layered nested JSON structures into relational tables.
* **Executive Visualization:** Translating operational datasets into clean, executive-level data charts (Bar plots, distribution trends) using Seaborn and Matplotlib styles.

---

## 🚀 Getting Started & Local Replication

### 1. Clone the Repository
```bash
git clone [https://github.com/zeysukg36/sql-for-data-analytics.git](https://github.com/zeysukg36/sql-for-data-analytics.git)
cd sql-for-data-analytics