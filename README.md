# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:
- SQL Development
- Data Architect
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Tools Used:

- **Datasets:** Access to the project dataset (csv files).
- **SQL Server Express:** Lightweight server for hosting your SQL database.
- **SQL Server Management Studio (SSMS):** GUI for managing and interacting with databases.
- **Git Repository:** Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
- **DrawIO:** Design data architecture, models, flows, and diagrams.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.  

For more details, refer to [docs/requirements.md](docs/requirements.md).

---

## 💡 Challenges I Faced

1. **Data Quality Issues** – The raw CSV files contained inconsistencies such as missing values, duplicates, and mismatched field formats, which required careful cleaning and validation.  
2. **Schema Design Decisions** – Choosing the right star schema design and ensuring normalization/denormalization balance was a learning curve.  
3. **ETL Complexity** – Building modular and reusable ETL scripts across the Bronze, Silver, and Gold layers required iterative debugging.  
4. **SQL Query Optimization** – Writing efficient queries for analytics in the Gold layer was challenging, especially when handling large joins.  
5. **Version Control Discipline** – Managing SQL scripts and DrawIO diagrams in GitHub required careful organization to maintain clarity.  

---

## 📚 What I Learned

- **Practical Understanding of Medallion Architecture** – How data moves and evolves across Bronze, Silver, and Gold layers.  
- **ETL Best Practices** – Building modular, reusable SQL scripts that ensure data consistency and accuracy.  
- **Data Modeling Skills** – Designing and implementing a star schema for business-ready reporting.  
- **SQL Performance Tuning** – Optimizing queries for better execution times in analytical workloads.  
- **Project Organization** – The importance of clear documentation, folder structure, and using tools like Notion and GitHub to keep track of progress.  
- **Real-World Problem Solving** – How to approach data inconsistencies and business requirements logically and iteratively.  

--- 

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── data_architecture.png           # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_layers.pdf                 # Process of creating each layer
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
```

---

## 🙌 Credits

This project was inspired by the tutorial created by [Data with Baraa](https://www.youtube.com/watch?v=SSKVgrwhzus) on YouTube.  
His walkthrough on building a SQL-based Data Warehouse provided valuable guidance for structuring the ETL pipelines, designing the Medallion Architecture layers, and modeling the star schema.  

Special thanks to him for sharing his knowledge and making the concepts easier to understand for learners and professionals alike.  
