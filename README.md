# 🏗️ End-to-End FMCG Data Engineering Pipeline

A production-style Data Engineering project that implements a complete **Lakehouse Architecture** using **AWS S3, Databricks, PySpark, SQL, and Delta Lake**. The pipeline ingests raw FMCG sales data, transforms it through the **Bronze → Silver → Gold Medallion Architecture**, and produces analytics-ready datasets for business reporting.

---

## 📌 Project Overview

This project demonstrates how modern data engineering pipelines are built using industry-standard tools and best practices.

The pipeline:

- Ingests raw FMCG datasets from multiple sources
- Stores data in AWS S3
- Processes data using PySpark in Databricks
- Implements Delta Lake for ACID transactions
- Follows the Medallion Architecture (Bronze, Silver, Gold)
- Performs historical and incremental data loading
- Builds dimensional models for business analytics
- Produces clean datasets ready for BI tools such as Power BI and Tableau

---

# 🏛️ Architecture

```
                Raw Data Sources
                       │
                       ▼
                  AWS S3 Landing
                       │
                       ▼
               Bronze Layer (Raw)
                       │
              Data Cleaning & Validation
                       │
                       ▼
              Silver Layer (Processed)
                       │
          Business Transformations
                       │
                       ▼
             Gold Layer (Analytics)
                       │
               Reporting / Dashboard
```

---

# ⚙️ Tech Stack

| Technology | Purpose |
|------------|----------|
| AWS S3 | Data Storage |
| Databricks | Data Processing Platform |
| PySpark | ETL Development |
| SQL | Data Transformation |
| Delta Lake | Lakehouse Storage |
| Git & GitHub | Version Control |

---

# 📂 Project Structure

```
project-de-fmcg-end-to-end
│
├── data/
│   ├── raw/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── notebooks/
│   ├── Bronze_ETL
│   ├── Silver_ETL
│   └── Gold_ETL
│
├── sql/
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

# 🚀 Pipeline Workflow

### Step 1 — Data Ingestion

- Load raw FMCG sales datasets
- Store files in AWS S3
- Validate schema

---

### Step 2 — Bronze Layer

- Store raw data
- Preserve original records
- Add ingestion metadata
- Handle schema evolution

---

### Step 3 — Silver Layer

- Remove duplicates
- Handle missing values
- Standardize formats
- Apply business rules
- Historical & Incremental loading

---

### Step 4 — Gold Layer

- Build Fact tables
- Build Dimension tables
- Create business KPIs
- Aggregate data for reporting

---

# 📊 Features

- End-to-End ETL Pipeline
- Lakehouse Architecture
- Medallion Design Pattern
- Incremental Data Loading
- Historical Data Processing
- Delta Lake Transactions
- Data Quality Validation
- Dimensional Data Modeling
- Analytics-Ready Data
- Production-Oriented Design

---

# 📈 Business Use Cases

The pipeline enables business users to analyze:

- Sales Performance
- Revenue Trends
- Product Performance
- Regional Sales
- Customer Insights
- Inventory Analysis
- Time-based Reporting

---

# 📷 Screenshots

Add screenshots here:

- Architecture Diagram
- Databricks Workspace
- Bronze Layer
- Silver Layer
- Gold Layer
- SQL Queries
- Dashboard
- AWS S3 Bucket

---

# 🎯 Skills Demonstrated

- Data Engineering
- ETL Pipeline Development
- PySpark
- Databricks
- SQL
- Delta Lake
- AWS S3
- Data Modeling
- Medallion Architecture
- Incremental Data Loading
- Git & GitHub

---

# 📚 Learning Outcomes

This project demonstrates practical knowledge of:

- Building scalable ETL pipelines
- Designing Lakehouse architectures
- Implementing Medallion Architecture
- Processing large datasets with PySpark
- Creating analytics-ready datasets
- Managing historical and incremental data

---

# 👨‍💻 Author

**Subhayan Mitra**

- GitHub: https://github.com/OfficialSubhayan
- LinkedIn: https://www.linkedin.com/in/subhayan-mitra/

---

## ⭐ If you found this project useful, consider giving it a star!
