# End-to-End-Data-Engineering-Pipeline-Using-Databricks

# 🏗️ End-to-End Data Engineering Project – Databricks (FMCG Domain)

## 📌 Project Overview

This project demonstrates a complete **end-to-end data engineering pipeline** built using **Databricks** for a real-world **FMCG domain use case**.

The scenario is based on one retail FMCG company acquiring another, where data from both companies is consolidated into a **single Lakehouse** for analytics and reporting.

This project highlights practical **ETL, big data processing, and cloud-based data engineering skills**.

---

## 🎯 Business Problem

* Two FMCG retail companies have separate data systems
* After acquisition, data must be combined into one unified platform
* Data should be clean, structured, and analytics-ready
* Final output should support BI dashboards and reporting

---

## 🛠️ Tools & Technologies Used

* **Python**
* **SQL**
* **Databricks**
* **Apache Spark (PySpark)**
* **Azure / AWS (Cloud Storage)**
* **Medallion Architecture (Bronze, Silver, Gold)**

---

## 🏗️ Architecture Used

### Medallion Architecture

* **Bronze Layer**: Raw data ingestion from source systems
* **Silver Layer**: Cleaned, transformed, and standardized data
* **Gold Layer**: Business-level aggregated tables for analytics and BI

---

## 🔑 Key Work & Implementation

* Ingested raw data from multiple FMCG sources into **cloud storage (Amazon S3 / Azure Data Lake)**
* Loaded raw data into **Databricks Bronze tables**
* Cleaned, validated, and transformed data using **PySpark**
* Merged data from both companies into unified datasets
* Created **Silver tables** with structured and clean data
* Built **Gold tables** for reporting, KPIs, and dashboards
* Developed **reusable ETL notebooks** for scalable processing
* Optimized pipelines for performance and reliability

---

## 📊 Final Output

* Analytics-ready tables
* Unified customer, product, and sales datasets
* Data suitable for **Power BI / Tableau dashboards**
* Scalable Lakehouse architecture

---

## 📁 Project Structure

```
Databricks-FMCG-Data-Engineering/
│── notebooks/
│   ├── bronze_ingestion.ipynb
│   ├── silver_transformation.ipynb
│   └── gold_aggregation.ipynb
│── data/
│── architecture/
│── README.md
```

---

## 🚀 What This Project Demonstrates

* Real-world FMCG data engineering use case
* End-to-end ETL pipeline development
* Hands-on experience with Databricks & Spark
* Cloud-based data processing
* Industry-standard Medallion Architecture

---

## 📈 Future Enhancements

* Add streaming data using Spark Structured Streaming
* Implement data quality checks
* Automate pipelines using Databricks Jobs
* Add monitoring and logging

---

## 👤 Author

**Murli Sharma**
M.Sc. Big Data Analytics | Aspiring Data Engineer / Data Analyst
📍 Ahmedabad, India

---

## ⭐ Support

If you found this project useful, please ⭐ the repository and feel free to fork or contribute.
