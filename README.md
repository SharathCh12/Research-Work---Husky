Research 16754889
# Research Data Pipeline for GPT Hallucination Reduction

## Overview  
This project was developed as part of my role as a **Research Data Analyst** at Northeastern University, contributing to a research team focused on **reducing hallucinations in GPT models**. The implementation follows the **Medallion Architecture (Bronze → Silver → Gold)** using **Azure Data Factory (ADF), Databricks, and Snowflake**.

## Data Flow Architecture  

1. **Data Sources**  
   - 📂 **CSV Files** (Raw Data)  
   - ❄️ **Snowflake** (Date Data)  
   - 🔥 **Databricks** (Predicted Data)  

2. **ETL & Transformation (Azure Data Factory)**  
   - Ingests data from all sources  
   - Cleans and applies naming conventions (Bronze Layer)  
   - Joins and standardizes data (Silver Layer)  
   - Loads into **Fact & Dimension Tables** (Gold Layer)  

3. **Storage & Reporting**  
   - Processed data stored in **Snowflake**  
   - Ready for analysis and visualization  

## Technologies Used  
- **Azure Data Factory (ADF)** – Data Ingestion & Orchestration  
- **Databricks** – Predictive Data Processing  
- **Snowflake** – Data Warehousing  
- **Python & SQL** – Data Cleaning & Processing  

## Project Structure  
📂 research-data-pipeline
│── 📁 data_sources/ # Raw CSV files
│── 📁 scripts/ # Python/SQL scripts
│── 📁 dataflows/ # ADF Pipelines & Dataflows
│── 📁 models/ # ML Predictions from Databricks
│── 📁 reports/ # Final reports & dashboards
│── README.md


