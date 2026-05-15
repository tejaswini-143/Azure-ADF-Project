# 🚀 End-to-End Azure Data Engineering Pipeline (On-Prem to Cloud)

## 📌 Overview
This project demonstrates an end-to-end data engineering pipeline that migrates data from an on-premises system to the Azure cloud, processes it using modern data engineering tools, and generates business insights through Power BI dashboards.

The pipeline covers the complete data lifecycle including ingestion, transformation, storage, analytics, and visualization.

---

## 🏗️ Architecture
![Architecture Diagram](./architecture.png)

### 🔹 Workflow
1. Data originates from an **on-premises system (local database/files)**
2. Data is ingested into Azure using **Azure Data Factory (ADF)**  
3. **Self-Hosted Integration Runtime (SHIR)** securely connects on-premises to Azure  
4. Raw data is stored in **Azure Data Lake Storage Gen2**  
5. Data is transformed using **Azure Databricks (PySpark)**  
6. Cleaned data is stored back in Data Lake (Transformed Layer)  
7. Data is queried using **Azure Synapse Analytics**  
8. Insights are visualized using **Power BI dashboards**  
9. Monitoring and alerts are handled using **Azure Monitor & Logic Apps**

---

## 🧰 Tech Stack

- Azure Data Factory (ADF)
- Self-Hosted Integration Runtime (SHIR)
- Azure Data Lake Storage Gen2
- Azure Databricks (PySpark)
- Azure Synapse Analytics
- Azure Key Vault
- Power BI
- Azure Monitor
- Logic Apps
- SQL
- Git

---

## 🔄 Data Pipeline Flow

### 🔹 Data Ingestion
- Built ADF pipelines to extract data from on-premises systems  
- Used SHIR for secure data transfer  
- Configured Linked Services and datasets  

### 🔹 Data Storage
- Stored raw data in **Azure Data Lake Gen2 (Raw Layer)**  
- Used hierarchical structure for organized storage  

### 🔹 Data Transformation
- Used **Azure Databricks (PySpark)** for:
  - Data cleaning  
  - Removing duplicates  
  - Formatting and preprocessing  
- Stored processed data in **Transformed Layer**

### 🔹 Data Security
- Used **Azure Key Vault** to securely manage credentials  
- Integrated Key Vault with Databricks using secret scopes  

### 🔹 Data Analytics
- Connected transformed data to **Azure Synapse Analytics**  
- Created SQL views for querying and reporting  

### 🔹 Data Visualization
- Built interactive dashboards using **Power BI**  
- Visualized key insights and trends for business users  

### 🔹 Monitoring & Alerts
- Used **Azure Monitor** for tracking pipeline execution  
- Configured **Logic Apps** to send email alerts on success/failure  

---

## ⚙️ Project Setup Steps

1. Created Resource Group  
2. Set up Azure Data Lake Storage Gen2  
3. Created containers (raw-data, transformed-data)  
4. Created Azure Data Factory  
5. Configured Git integration  
6. Set up Self-Hosted Integration Runtime (SHIR)  
7. Created Linked Services and datasets  
8. Built ADF pipelines (Copy Activity)  
9. Configured triggers (scheduled runs)  
10. Set up Azure Databricks and wrote PySpark scripts  
11. Configured Azure Key Vault  
12. Created Azure Synapse workspace and SQL views  
13. Built Power BI dashboards  
14. Configured monitoring and alerts  

---

## 📊 Power BI Dashboard
- Built interactive dashboards for business insights  
- Included KPIs, trends, and reporting visuals  
- Connected Power BI to Azure Synapse / Data Lake  

*(Add screenshots here if available)*

---

## 📌 Key Features
- End-to-end data pipeline (On-prem → Cloud → Visualization)
- Secure data transfer using SHIR  
- Scalable storage using Azure Data Lake  
- Big data processing using Databricks  
- Cloud-based analytics with Synapse  
- Real-time monitoring and alerting  
- Business reporting using Power BI  

---

## 🎯 Use Cases
- Data migration from legacy systems  
- Building modern data pipelines  
- Data warehousing and analytics  
- Business intelligence and reporting  

---

## 📈 Future Enhancements
- Implement incremental data loading  
- Add data quality checks  
- Optimize pipeline performance  
- Integrate CI/CD for deployment  

---

## 👩‍💻 Author
**Tejaswini N**  
Data Engineer | SQL | ETL | Azure | Python  
