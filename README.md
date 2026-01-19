# Databricks_Sales_Project

## 📌 Project Overview
The **Databricks Sales Project** focuses on exploring Databricks concepts and building a scalable **data warehouse** using **PySpark** and the **Medallion Architecture**.  
The project demonstrates how raw sales data can be transformed through structured ETL pipelines into analytics-ready datasets for reporting and business insights.

This project simulates a real-world data engineering workflow commonly used in modern cloud-based analytics platforms.

---

## 🎯 Objective
- To understand and implement **Databricks workflows** for data engineering
- To design a **scalable ETL pipeline** using **Medallion Architecture (Bronze, Silver, Gold)**
- To transform raw sales data into a **clean, analytics-ready data warehouse**
- To leverage **PySpark** for efficient distributed data processing
- To enable reliable downstream reporting and BI use cases

---

## 🏢 Business Overview
The business context revolves around a **sales analytics use case**, where an organization needs to:
- Track sales performance across products, regions, and customers
- Improve data quality and consistency for decision-making
- Reduce manual data processing by automating ETL workflows
- Create trusted datasets for dashboards and executive reporting

Raw transactional data often comes in inconsistent formats and requires structured processing before it can be used for analysis.

---

## 🧱 Architecture Used – Medallion Architecture
This project follows the **Medallion Architecture**, a best-practice data design pattern in Databricks:

### 🥉 Bronze Layer (Raw Data)
- Ingests raw sales data from source files
- Stores data in its original format
- Minimal transformations applied
- Acts as a single source of truth for raw data

### 🥈 Silver Layer (Cleaned & Enriched Data)
- Data cleansing and standardization
- Handling nulls, duplicates, and inconsistent values
- Data type normalization
- Business rule application (e.g., standardizing categorical fields)

### 🥇 Gold Layer (Analytics & Reporting)
- Aggregated and business-ready datasets
- Optimized for reporting and BI tools
- Supports KPIs, trends, and performance metrics
- Designed for consumption by analysts and stakeholders

---

## ⚙️ Actions & Tasks Performed
- Set up Databricks workspace and notebooks
- Designed end-to-end ETL pipeline using **PySpark**
- Implemented **Bronze → Silver → Gold** data flow
- Applied data transformations using Spark DataFrame APIs
- Standardized and validated sales data attributes
- Built analytical tables suitable for reporting
- Ensured scalable and maintainable data warehouse structure

---

## 🛠️ Technologies Used
- **Databricks**
- **Apache Spark (PySpark)**
- **Delta Lake**
- **Medallion Architecture**
- **SQL & DataFrame APIs**
- **Cloud-based Data Warehouse Concepts**

---

## 📊 Outcome & Key Learnings
- Hands-on experience with Databricks ETL workflows
- Practical understanding of Medallion Architecture
- Improved data quality and consistency for analytics
- Built a foundation for scalable, enterprise-grade data pipelines
- Prepared datasets suitable for BI dashboards and advanced analytics

<p align="center">
  <img alt="Screenshot 2026-01-18 at 9 05 41 PM" src="https://github.com/user-attachments/assets/a912acec-4a0d-4dea-89aa-73f0d08fd1bd"  width="400" height="500" />

</p>
<p align="center">
 
  <img alt="Screenshot 2026-01-18 at 9 10 22 PM" src="https://github.com/user-attachments/assets/e0d242bc-8b93-4dc2-b5d8-5dafa2a63166" width="400" height="500" />
</p>

---

## 📌 Future Enhancements
- Integrate real-time or streaming data sources
- Add data quality checks and validation frameworks
- Implement orchestration using Databricks Jobs
- Connect Gold layer to Power BI or Tableau dashboards
- Optimize performance usi

