# 📈 Retail Sales Time Series Analysis

![SQL](https://img.shields.io/badge/Language-SQL-blue) 
![Database](https://img.shields.io/badge/Database-MySQL-orange) 
![Focus](https://img.shields.io/badge/Focus-Data_Analysis)

---

## 📌 Executive Summary

This project analyzes a historical **Retail Sales dataset** to track sector performance, identify seasonal trends, and handle missing data/anomalies in time-series records. The primary goal is to derive actionable business insights using SQL techniques (Window Functions, CTEs, Aggregations, and Conditional Logic).

* **Key Dataset Characteristics:** Historical monthly sales records across retail categories, featuring missing data flags (`reason_for_null`).
* **Technical Focus:** Data cleaning, trend identification, Year-over-Year (YoY) growth calculation, and windowing metrics.

---

## 🛠️ Data Architecture & Setup

To replicate this database and execute the queries in your local environment (e.g., MySQL Workbench or CLI):

1. Clone this repository.
2. Download and execute the full dataset script located in `/data/schema_and_data.sql`.

```sql
-- Quick preview of the core table structure
DESCRIBE series_de_tiempo.retail_sales;
