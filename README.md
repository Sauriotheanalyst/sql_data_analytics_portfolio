# 📈 US Retail Sales Data Analysis (1992–2020)

![SQL](https://img.shields.io/badge/Language-SQL-blue) 
![Database Compatibility](https://img.shields.io/badge/Database-Cross--Platform_SQL-orange) 
![Focus](https://img.shields.io/badge/Focus-Data_Analysis_%26_Market_Insights-green)

---

## Summary

This project presents an end-to-end SQL analysis of the official **US Retail Sales dataset**, from **1992 to 2020**. 

**Objective:** Measure **category-specific growth**, and analyze **environmental impacts on consumer behavior** through economic shifts and market volatility up to the **2020 COVID-19 pandemic**.

* **Dataset Scope:** **28 years** of monthly US retail sales data across all trade categories, including **missing data flags** for statistical analysis.

* **Technical Focus:** **Data cleaning**, **YoY growth calculation**, **historical trend analysis**, **market share evolution**, and **behavioral anomaly assessment**.
---

## 🛠️ Data Architecture & Compatibility

### 🌐 Cross-Platform SQL Compatibility
All queries in this repository adhere to **ANSI SQL syntax** standard to ensure full compatibility across major relational database engines, including:
* **PostgreSQL**
* **Microsoft SQL Server (T-SQL)**
* **MySQL**

### Setup & Replication
To import the database and run the queries locally:

1. Clone this repository.
2. Execute the dataset script located in `/data/schema_and_data.sql` inside your preferred SQL engine.

```sql
-- Structure overview for the primary dataset
DESCRIBE retail_sales;
