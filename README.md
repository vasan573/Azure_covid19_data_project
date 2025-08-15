# COVID-19 Data Pipeline – Azure Data Engineering Project

## 📌 Overview
This project demonstrates an **end-to-end Azure Data Engineering workflow** to ingest, transform, store, and visualize COVID-19 and population data from the European Centre for Disease Prevention and Control (ECDC).  
The solution is designed to replicate real-world enterprise data pipelines using multiple Azure services.

---

## 🛠 Tech Stack
- **Azure Data Factory** – Orchestrating ingestion pipelines
- **Azure Data Lake Storage Gen2** – Raw & processed data storage
- **Azure Data flow & databricks** – Data transformation and cleaning
- **Azure SQL Database** – Processed data storage
- **Power BI** – Data visualization & reporting
- **Azure Monitor** – Pipeline monitoring & alerts

---

---

## 🚀 Pipeline Workflow
1. **Data Ingestion**
   - COVID-19 daily data from ECDC (HTTP Connector in ADF)
   - Population dataset from Azure Blob Storage
2. **Data Transformation**
   - Cleaning & joining datasets in Azure Databricks and ADF Mapping Data Flows
3. **Storage**
   - Raw data → Azure Data Lake Gen2  
   - Processed data → Azure SQL Database & ADLS Gen2
4. **Visualization**
   - Power BI dashboard with KPIs (total cases, deaths, testing, hospitalizations)
5. **Monitoring**
   - Email alert for failed triggers in ADF
   - Cost tracking in Azure Cost Management

---
---

## 📈 Key Learnings
- Building and orchestrating ETL pipelines in Azure
- Transforming large datasets efficiently in Databricks
- Managing storage layers (raw, processed, curated)
- Connecting Azure SQL Database with Power BI
- Implementing alerts and cost optimization

---

## 📚 References
- [Microsoft Azure Documentation](https://learn.microsoft.com/azure)
- [Azure Data Factory Documentation](https://learn.microsoft.com/azure/data-factory)
- [Azure Databricks Documentation](https://learn.microsoft.com/azure/databricks)
- [Power BI Documentation](https://learn.microsoft.com/power-bi/)

---

---

## 🏷 Tags
`Azure Data Engineering` `Azure Data Factory` `Azure SQL` `Azure Data Lake` `Databricks` `Power BI` `ETL Pipeline` `Data Analytics`


