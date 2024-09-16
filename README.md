# Spark-Data Fabric
This repository demonstrates the concept and implementation of Apache Spark &amp; Lakehouse on Data Fabric, specifically designed to support the Medallion Architecture.

The Medallion Architecture (Bronze, Silver, Gold) represents a modern data lake design pattern that enhances data processing and analytics by segmenting the data pipeline into manageable stages.

# Key Features
- **Concept Overview**:  
  Detailed explanation of the Medallion Architecture, including the roles of the Bronze, Silver, and Gold layers.

- **Data Ingestion**:  
  The example demonstrates the process of ingesting data from multiple sources, such as TXT, CSV, and XLSX files, as well as MYSQL and MONGODB databases, into the Bronze layer.

- **Data Transformation**:  
  A comprehensive guide on how to transform and cleanse raw data in the Bronze layer to create a structured Silver layer.

- **Data Aggregation**:  
  Techniques for aggregating and enriching the data in the Silver layer to produce the final Gold layer.

- **Data Quality (DQ) Checks**:  
  To ensure data integrity, data quality checks must be implemented at each stage.

# Implementation Highlights
- **Code**:  
  Code samples using PySpark in Data Fabric notebooks for each layer of the Medallion Architecture.

- **Storage**:  
  Storage using [Lakehouse] Delta Table in Data Fabric

- **Automation and Scheduling**:  
  Automation and Scheduling using Pipeline in Data Fabric
