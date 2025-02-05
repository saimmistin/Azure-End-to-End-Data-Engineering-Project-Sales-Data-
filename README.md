# Azure-End-to-End-Data-Engineering-Project-Sales-Data-Pipeline
<img width="1389" alt="Screenshot 2025-02-04 at 4 28 36 PM" src="https://github.com/user-attachments/assets/985ecc3f-4121-41e4-994d-7330c0a61a01" />

This project addresses a  business need by building an end-to-end data pipeline on Azure. The goal is to extract customer and sales data from an on-premises SQL database, transform it in the cloud, run it once daily, and connect it to Tableau to make actionable insights through a Tableau dashboard.

## Tech Stack
	•	Data Sources: Azure MS SQL Database
	•	Cloud Services: Azure Data Factory, Azure Data Lake Gen2, Azure Synapse Analytics
	•	Processing & Transformation: Databricks
	•	Visualization: Tableau
<img width="1539" alt="Screenshot 2025-02-03 at 11 19 41 PM" src="https://github.com/user-attachments/assets/f6a67511-ab20-46e7-abb0-1829cd316ab9" />

## Data Pipeline Workflow
#### Configuration
	•	Connect on-premises SQL database to Azure Data Factory
	•	Copy data from SQL to Azure Data Lake
 
#### Data Ingestion
 	.       Use ForEach Activity in Azure Data Factory
	•	Test and debug the SQL-to-Bronze pipeline
	•	Monitor pipeline runs
  	. 	Run the pipeline once a day
 
#### Data Transformation in Dtabricks using Pyspark
	•	Create and configure a Databricks cluster
	•	Mount Data Lake Storage in Databricks
	•	Perform data transformations
	•	Automate ETL processes

#### Loading Data into Synapse Analytics
	•	Load transformed data into Azure Synapse
	•	Create optimized views for efficient querying
	•	Integrate Synapse views into Data Factory Pipelines
 
#### Data Connection to Tableau
	•	Connect to Synapse Analytics in Tableau


 
 
