# pyspark-olympic-data-etl


# 🏅 Tokyo Olympics 2021 - Azure Synapse Analytics Project

## 📚 Project Overview
This project demonstrates how to build an end-to-end data pipeline for the Tokyo Olympics 2021 dataset using:
- **Azure Synapse Analytics**
- **Azure Data Lake Storage Gen2**
- **SQL Serverless Pools**
- **(Optional) Azure Databricks for transformation**

It covers medal analysis, gender participation statistics, athlete data modeling, and country-wise sports performance through Azure services.

---
## 🏗️ Architecture

- **Azure Data Lake Gen2** → Store raw and curated datasets.
- **Azure Synapse Analytics** → Create external and managed tables, run analytical queries.
- **(Optional)** **Azure Databricks** → Preprocessing and transformation.
- **Power BI / Other Reporting Tools** → Connect for querying (no visualization in this project).

---
## 🛠️ Technologies Used
| Tool                   | Purpose                        |
| ---------------------- | ------------------------------ |
| Azure Synapse           | SQL Data Analytics             |
| Azure Data Lake Gen2    | Scalable Storage Layer         |
| Azure Databricks (Optional) | Data Engineering if required |
| SQL Serverless Pools    | Querying External Tables       |

---
## 🚀 Steps to Reproduce

1. **Upload Dataset**  
   Upload CSV data files into an Azure Data Lake Storage Gen2 container.

2. **Create External Tables in Synapse**  
   Connect Synapse Serverless SQL pool to Data Lake and define external tables.

3. **Run Analytical SQL Queries**  
   Execute pre-written queries for medal analysis, gender participation, and country-level statistics.

4. **Connect to Reporting Tools (Optional)**  
   Connect Power BI or Tableau to Synapse for data querying and reporting *(no dashboards built here)*.

---
## 📊 Key Data Insights Explored
- Medal tally by country and discipline.
- Gender distribution across different sports.
- Medal efficiency: number of medals per athlete.
- Country-wise coach-to-athlete ratios.

---
## 📍 About the Author
> Project by **[Shalin Vachheta](https://github.com/ShalinVachheta017)**  
> Focused on AI, Data Engineering, Cloud Analytics, and Big Data solutions.  
> Passionate about real-world data-driven applications.


