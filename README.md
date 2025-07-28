# Tokyo-Olympics-Data-Engineering-Project
This project demonstrates a complete data engineering pipeline built on Microsoft Azure, using data from the Tokyo 2020 Olympic Games. It showcases how large-scale datasets can be ingested, transformed, analysed, and stored using modern cloud-based technologies.


Tools Used 

Azure Data Factory: Orchestrated data ingestion and movement from raw CSV files to the data lake.

Azure Blob Storage: Served as the data lake, securely storing raw and curated data.

Azure Databricks: Performed data cleaning, transformation, and analysis using PySpark notebooks.

Azure Synapse Analytics: Enabled structured querying and reporting on processed datasets.

GitHub Actions: Automated deployment and data uploads to Azure Blob Storage.



Pipeline Flow

Raw Data Ingestion:
Tokyo Olympics datasets were uploaded to Azure Blob Storage.

Data Orchestration:
Azure Data Factory pipelines automated the movement of raw data into staging and curated layers.

Data Transformation:
Azure Databricks notebooks cleaned and transformed the data—handling missing values, standardising formats, and preparing it for analytics.

Data Analysis & Warehousing:
Transformed data was loaded into Azure Synapse Analytics for SQL-based querying and visualisation.

Automation:
GitHub Actions ensured automated uploads of datasets to Azure Blob Storage on every code push.
