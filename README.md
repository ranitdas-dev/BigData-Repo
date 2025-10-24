# BigData-Repo

# 🌐 Big Data Pipeline Project

## 📘 Overview
This project showcases a cloud-based Big Data pipeline that integrates **data orchestration** and **distributed processing** using modern tools. It demonstrates how to ingest, transform, and manage large-scale datasets efficiently by combining the strengths of **Azure Data Factory** and **Azure Databricks**.

## 🧰 Technologies Used
- **Azure Data Factory (ADF)**: For orchestrating and scheduling data workflows
- **Azure Databricks**: For scalable data transformation using Apache Spark
- **Cloud Storage**: Used for storing raw and processed data (e.g., Azure Blob Storage)
- **Delta Lake**: For reliable, versioned data storage
- **GitHub**: For version control and collaboration

## 🔄 Pipeline Architecture
The pipeline is designed to handle end-to-end data processing:

1. **Ingestion**: ADF pipelines extract data from various sources and load it into cloud storage.
2. **Transformation**: Databricks notebooks process and clean the data using Spark, storing results in Delta Lake format.
3. **Orchestration**: ADF coordinates the entire workflow, triggering Databricks jobs and managing dependencies.
4. **Monitoring**: Built-in logging and alerts ensure visibility into pipeline health and performance.
