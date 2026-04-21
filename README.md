# Data Warehouse and Analytics Project

Welcome to this **Data Warehouse and Analytics Project**.
This project shows how I built a simple data warehouse and used it to generate useful insights from data.

---

## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data exactly as it comes from the source. Data is loaded from CSV files into a SQL Server database.
2. **Silver Layer**: Data is cleaned, standardized, and prepared for analysis.
3. **Gold Layer**: Contains business-ready data structured in a star schema for reporting and analytics.

---

## 📖 Project Overview

This project covers:

* Designing a data warehouse using Bronze, Silver, and Gold layers
* Building ETL pipelines to move and transform data
* Creating fact and dimension tables for analysis
* Writing SQL queries to generate insights and reports

This project is useful for showcasing skills in:

* SQL Development
* Data Engineering
* Data Modeling
* ETL Pipelines
* Data Analysis

---

## 🛠️ Tools Used

* SQL Server Express
* SQL Server Management Studio (SSMS)
* Git and GitHub
* DrawIO
* Notion

---

## 🚀 Project Requirements

### Data Engineering

#### Objective

Build a data warehouse using SQL Server to bring together sales data and make it easy to analyze.

#### What was done

* Loaded data from ERP and CRM systems (CSV files)
* Cleaned and fixed data quality issues
* Combined the data into one simple data model
* Focused only on the latest data
* Documented the data structure clearly

---

### Data Analysis

#### Objective

Use SQL to generate insights on:

* Customer behavior
* Product performance
* Sales trends

These insights help in making better business decisions.

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/
├── docs/
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_model.drawio
│   
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   ├── gold/
│
├── tests/
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt
```

---

## 🛡️ License

This project is licensed under the MIT License.

---

## 🌟 About Me

Hi, I’m **Adeolu Adeyinka**.
I’m a mechanical engineering graduate with a strong interest in data, software, and problem solving. I enjoy building projects like this to improve my skills and gain practical experience.
