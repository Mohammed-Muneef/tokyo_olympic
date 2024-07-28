# Tokyo Olympic Data Analytics | End-to-End Azure Data Engineering Project

## Overview

This project demonstrates an end-to-end data engineering pipeline designed to analyze data from the Tokyo Olympics. Leveraging a suite of Azure tools, this solution showcases how to efficiently ingest, store, transform, and analyze large datasets, ultimately providing insightful visualizations and analytics.

## Architecture

The architecture consists of the following components:

1. **Data Source**: Various data sources providing raw data related to the Tokyo Olympics.
2. **Data Ingestion**: Azure Data Factory is used to ingest data from multiple sources into the data lake.
3. **Raw Data Store**: Azure Data Lake Storage Gen2 serves as the scalable and secure storage for raw data.
4. **Transformation**: Azure Databricks is employed for data processing and transformation, enabling complex computations and data preparation.
5. **Transformed Data Store**: The transformed data is stored back in Azure Data Lake Storage Gen2.
6. **Analytics**: Azure Synapse Analytics is utilized for advanced analytics and querying of the transformed data.
7. **Dashboard**: Visualizations and insights are created using Power BI, Looker Studio, and Tableau, providing interactive and informative dashboards.

## Components

### 1. Data Ingestion
- **Azure Data Factory**: Orchestrates the ETL process, connecting to various data sources and ingesting data into the data lake.

### 2. Raw Data Storage
- **Azure Data Lake Storage Gen2**: Offers high throughput and secure storage for large datasets, ensuring data is readily available for processing.

### 3. Data Transformation
- **Azure Databricks**: A powerful analytics platform that facilitates data engineering and machine learning tasks. It transforms raw data into a structured format for analysis.

### 4. Analytics
- **Azure Synapse Analytics**: Provides a unified experience for big data and data warehousing, enabling seamless querying and analysis of the transformed data.

### 5. Dashboard
- **Power BI, Looker Studio, Tableau**: These visualization tools are used to create interactive dashboards, presenting the analytics in a comprehensible and visually appealing manner.

## Workflow

1. **Ingest Data**: Data from multiple sources is ingested using Azure Data Factory.
2. **Store Raw Data**: Ingested data is stored in Azure Data Lake Storage Gen2.
3. **Transform Data**: Azure Databricks processes and transforms the raw data.
4. **Store Transformed Data**: Transformed data is stored back in Azure Data Lake Storage Gen2.
5. **Analyze Data**: Azure Synapse Analytics performs advanced analytics on the transformed data.
6. **Visualize Data**: Insights and visualizations are created using Power BI.


