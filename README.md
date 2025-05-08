# 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive end-to-end data warehousing and analytics solution. It follows modern architecture and best practices, ideal for showcasing your skills in data engineering and analytics.

---

## 🏗️ Data Architecture

This project uses **Medallion Architecture** with **Bronze, Silver, and Gold layers**:
![data_architecture](https://github.com/user-attachments/assets/1bd951f3-29d7-44dc-a6cc-cfa07cab5e95)

- **Bronze Layer**  
  Stores raw data ingested from CRM and ERP systems (CSV files). Data is loaded into SQL Server with no transformation.

- **Silver Layer**  
  Performs data cleansing, standardization, normalization, and enrichment to prepare clean data.

- **Gold Layer**  
  Contains business-ready data structured in star schema, used for reporting, analysis, and machine learning.

---

## 📖 Project Overview

This project involves:

- **Data Architecture**  
  Design and implementation of a modern warehouse using Medallion Architecture.

- **ETL Pipelines**  
  Extract, Transform, and Load processes built using SQL Server stored procedures.

- **Data Modeling**  
  Star schema with fact and dimension tables optimized for analytical queries.

- **Analytics & Reporting**  
  SQL-based reports and dashboards for insight generation.

---

## 🎯 Skills Demonstrated

This project is ideal for professionals and students looking to build a strong data portfolio in:

- SQL Development  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  
- Data Architecture

---

## 🛠️ Tools & Resources

Everything used in this project is **free** and beginner-friendly:

- **Datasets** – Raw ERP and CRM CSV files
- **SQL Server Express** – Lightweight RDBMS
- **SQL Server Management Studio (SSMS)** – SQL GUI
- **Git & GitHub** – Version control and collaboration
- **Draw.io** – Data architecture and flow diagrams
- **Notion** – Project management and documentation

---

## 🚀 Project Requirements

### 1. Data Engineering (Building the Data Warehouse)

**Objective**:  
Develop a data warehouse in SQL Server to consolidate ERP and CRM data.

**Specifications**:
- Source: CSV files (ERP & CRM)
- Cleansing: Handle missing, inconsistent, or duplicate data
- Integration: Unified data model
- Scope: Latest data only (no historical storage)
- Documentation: Clear metadata and data model

---

### 2. Data Analysis (BI & Reporting)

**Objective**:  
Develop SQL queries and reports to uncover:

- Customer behavior
- Product performance
- Sales trends

📄 For more details, refer to [`docs/requirements.md`](docs/requirements.md)

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/ # Raw datasets used for the project (ERP and CRM data)
│
├── docs/ # Project documentation and architecture details
│ ├── etl.drawio # Diagram showing ETL techniques and methods
│ ├── data_architecture.drawio # Diagram showing the project's architecture
│ ├── data_catalog.md # Dataset catalog with field descriptions and metadata
│ ├── data_flow.drawio # Diagram for the data flow
│ ├── data_models.drawio # Diagram for data models (e.g., star schema)
│ ├── naming-conventions.md # Guidelines for naming tables, columns, and files
│
├── scripts/ # SQL scripts for ETL and transformations
│ ├── bronze/ # Scripts for extracting and loading raw data
│ ├── silver/ # Scripts for cleaning and transforming data
│ ├── gold/ # Scripts for creating analytical models
│
├── tests/ # Data quality checks and test scripts
│
├── README.md # Project overview and instructions
├── LICENSE # License information for the repository
├── .gitignore # Git ignore rules
└── requirements.txt # Project dependencies
```
## ☕ Stay Connected

> Want to connect, collaborate, or follow my work?

- **LinkedIn**: [www.linkedin.com/in/pushkarganta]
---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and share it with attribution.

---
## 🌟 About Me

**Hi, I'm Pushkar! I'm an IT professional passionate about sharing knowledge and making data work simple, fun, and meaningful.**
-----
