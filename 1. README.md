# Apache-Spark-Mini-Project
# e-Commerce Sales Data Processing

This mini project demonstrates batch data processing in the e-commerce domain. Here's a brief explanation of the process:

- **Source**:
    Data originates from SQL Servers and SQL Databases (batch data).

- **Ingestion**:
    Data is extracted using JDBC (Java Database Connectivity).
    Key Vaults are used to securely store secrets and credentials.

- **Processing**:
    The data is ingested into the Databricks File System (DBFS) and processed through a medallion architecture: 
    - Bronze layer: Raw data is stored. 
    - Silver layer: Data is cleansed and transformed. 
    - Gold layer: Aggregated or refined data is stored for reporting. 
  

  PySpark and Spark SQL are used for processing and querying data. 

- **Reporting**:
    Processed data in the Gold layer is used to generate operational reports and dashboards in Power BI.

This project provides an end-to-end pipeline for managing, processing, and reporting e-commerce data.
