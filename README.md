# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a complete, end-to-end data warehousing and analytics solution — from raw data ingestion to generating actionable business insights. Designed as a professional portfolio project, it highlights industry best practices in **data engineering, analytics, and architecture**.

---

## 🏗️ Data Architecture

The data architecture for this project follows the **Medallion Architecture** framework with **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer** – Stores raw data as received from source systems. Data is ingested from CSV files into a SQL Server database.  
2. **Silver Layer** – Performs data cleansing, standardization, and transformation to prepare the data for analytical modeling.  
3. **Gold Layer** – Contains business-ready, curated datasets modeled into a **star schema** for efficient reporting and analytics.  

---

## 📖 Project Overview

This project showcases the full lifecycle of building a modern data warehouse:

1. **Data Architecture** – Designing a scalable warehouse using Medallion principles.  
2. **ETL Pipelines** – Building SQL-based extract, transform, and load (ETL) workflows to move data through the Bronze, Silver, and Gold layers.  
3. **Data Modeling** – Structuring fact and dimension tables optimized for analytics.  
4. **Analytics & Reporting** – Producing insights with SQL queries and dashboards focused on business value.

🎯 This repository is an excellent reference for professionals or students aiming to demonstrate expertise in:
- SQL Development  
- Data Engineering  
- ETL Pipeline Design  
- Data Modeling  
- Business Intelligence & Analytics  

---

## 🛠️ Tools & Technologies

This project leverages a modern stack of freely available tools:

- **SQL Server Express** – Lightweight database for hosting the data warehouse.  
- **SQL Server Management Studio (SSMS)** – GUI for database management and query development.  
- **Draw.io** – Used for designing data flow, architecture, and schema diagrams.  
- **Notion / Markdown Docs** – Documentation for requirements, process steps, and architecture details.  
- **Git & GitHub** – Version control and project management.  

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a SQL Server–based data warehouse that consolidates ERP and CRM data into a unified model for analytics and reporting.

#### Specifications
- **Data Sources**: Two CSV files representing ERP and CRM systems.  
- **Data Quality**: Clean and transform data to resolve duplicates and inconsistencies.  
- **Integration**: Merge both sources into a single, query-ready schema.  
- **Scope**: Focus on current dataset; historization is out of scope.  
- **Documentation**: Provide data dictionary, schema diagrams, and process documentation.  

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Deliver actionable business insights through SQL-based analytics, focusing on:

- **Customer Behavior Patterns**  
- **Product Performance**  
- **Sales Trends & KPIs**  

These reports enable data-driven decision-making by highlighting performance metrics and identifying growth opportunities.  
Additional documentation can be found in [docs/requirements.md](docs/requirements.md).

---

## 📂 Repository Structure

data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
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
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).  
You’re free to use, modify, and share this project with proper attribution.

---

## 🌟 About the Author

Hi there! I’m **Desarael Black**, a **Technical Architect and Data Analytics professional** passionate about bridging the gap between data engineering and business strategy.  

This project reflects my approach to designing scalable, insight-driven data systems — combining architectural rigor with analytics that deliver measurable impact.

If you’re interested in discussing data architecture, analytics, or AI-driven insights, feel free to connect or collaborate on future projects!
