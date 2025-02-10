Paris Olympics 2024 Data Engineering Project

📌 Project Overview

This project involves building an end-to-end ETL pipeline for Paris Olympics 2024 data analytics, leveraging Microsoft Azure services for data processing, transformation, and analysis. The goal is to demonstrate cloud-based data engineering practices and optimize large-scale datasets for insightful analytics.

🚀 Technologies Used

Microsoft Azure (Cloud Platform)

Azure Data Factory (Data Ingestion & Orchestration)

Azure Data Lake Gen2 (Data Storage)

Azure Databricks (Apache Spark, PySpark) (Data Processing & Transformation)

Azure Synapse Analytics (Data Warehousing & SQL Analytics)

🔧 Project Workflow

1️⃣ Data Ingestion:

Extracted raw Olympic datasets from GitHub/Kaggle using Azure Data Factory.

Data pipeline to fetch and load CSV files into Azure Data Lake Gen2 for scalable storage.

2️⃣ Data Transformation:

Mounted Azure Data Lake Gen2 storage on Azure Databricks.

Processed, cleaned, and aggregated the data using Apache Spark.

Applied transformations such as handling missing values, standardizing formats, and performing aggregations.

Stored processed data back into the processed zone of Azure Data Lake Gen2.

3️⃣ Data Storage & Analytics:

Loaded structured data from Azure Data Lake Gen2 into Azure Synapse Analytics.

Created tables and performed SQL-based queries for analysis.

Used Synapse SQL pools to enable fast querying and optimized reporting.

📊 Key Features

✔ End-to-End ETL Pipeline on Microsoft Azure
✔ Automated Data Ingestion using Azure Data Factory
✔ Cloud-Based Big Data Processing with Databricks (Apache Spark)
✔ Optimized Data Storage with Azure Data Lake Gen2
✔ Scalable Analytics & SQL Querying using Azure Synapse Analytics
✔ Performance Insights & Trend Analysis using structured querying

📷 Project Architecture & Visuals

![image](https://github.com/user-attachments/assets/43ddbddb-972d-4332-9b56-82c03ac2876a)
![image](https://github.com/user-attachments/assets/24f08a55-2998-4633-ae96-6345a6efaed5)



📁 Dataset Information

The dataset contains historical Olympic data, including athlete performance, event details, and medal counts.

Data is sourced from Kaggle and GitHub.


📌 How to Use This Project

Clone this repository.

Set up Azure Data Factory, Azure Data Lake Gen2, Databricks, and Synapse Analytics.

Configure the ETL pipeline following the workflow mentioned above.

Run SQL queries in Azure Synapse Analytics to generate insights.

🏆 Future Enhancements

Integrate real-time streaming data from Olympic events.

Implement machine learning models for predictive analytics.

Develop a dashboard using Power BI to visualize insights.

📜 License

This project is open-source and available for learning purposes.
