# 🏅 Azure Olympic Data Pipeline Project

This project demonstrates an end-to-end **data engineering pipeline on Microsoft Azure**, built to process, transform, and visualize Tokyo Olympic 2020 Games data using various Azure services and Tableau.

---

## 📌 Project Overview

### Goal:
To build a scalable data pipeline that ingests raw Olympic data, transforms it for analysis, and produces interactive dashboards for key stakeholders.

### Dataset:
The raw dataset includes:
- `Athletes.csv` — Athlete demographics
- `Coaches.csv` — Coaching staff
- `Medals.csv` — Medal count by country
- `Teams.csv` — Team participation info
- `EntriesGender.csv` — Gender-based entries by discipline

---

## 🧱 Architecture

[Data Source (.csv)]
->
[Azure Data Factory] → [Raw Data Zone in Data Lake Gen2]
->
[Azure Databricks] (PySpark transformation)
->
[Transformed Data in Data Lake Gen2]
->
[Azure Synapse Analytics]
->
[Tableau Dashboard]


---

## ⚙️ Tools & Technologies

| Layer | Tools |
|-------|-------|
| Ingestion | Azure Data Factory |
| Storage | Azure Data Lake Gen2 |
| Processing | Azure Databricks (PySpark) |
| Analytics | Azure Synapse Analytics |
| Visualization | Tableau Desktop / Tableau Public |

---

## 🧪 Key Transformation Steps

In **Databricks**, we performed the following:
- Aggregated total medal counts per country
- Identified top 10 medal-winning nations
- Cleaned and joined datasets for dashboard input

