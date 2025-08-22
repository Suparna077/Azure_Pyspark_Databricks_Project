# Azure PySpark Databricks Project 🚀

This repository showcases a series of hands-on notebooks demonstrating real-world data engineering workflows using **Apache Spark**, **Azure Databricks**, and **Azure SQL/Cosmos DB**. 
The project is designed to highlight scalable ETL patterns, upsert strategies, and JSON handling in distributed environments.

## 🔧 Tech Stack

- **Azure Databricks** (Spark 3.x, Delta Lake)
- **PySpark** (DataFrame API, SQL functions)
- **Azure SQL Database**
- **Azure Cosmos DB**
- **Jupyter Notebooks**

## 📁 Notebooks Overview

| Notebook | Description |
|---------|-------------|
| `MultipleFileRead_With_Spark.ipynb` | Reads multiple files using Spark and demonstrates schema inference and union operations. |
| `Pyspark_With_JSON.ipynb` & `Pyspark_With_Json_2.ipynb` | Parses nested JSON structures and flattens them using PySpark. |
| `Pyspark_With_AzureSQLDB.ipynb` | Connects to Azure SQL DB using JDBC and performs read/write operations. |
| `AzureSQLDB_Upsert.ipynb` | Implements upsert logic using merge statements with Azure SQL. |
| `Upsert_With_DatabricksDeltaTable.ipynb` | Demonstrates Delta Lake upsert using `MERGE INTO` for slowly changing dimensions. |
| `Databricks_To_CosmosDB_DataLoad.ipynb` | Loads transformed data into Azure Cosmos DB using Spark connector. |
| `Pyspark_Scenariobased_Coding_1.ipynb` | Contains scenario-based PySpark coding challenges for interview prep. |

## 🧠 Key Concepts Demonstrated

- Efficient file ingestion and schema evolution
- JSON normalization and nested structure handling
- JDBC connectivity and secure credential management
- Delta Lake upserts and data deduplication
- Cosmos DB integration for NoSQL workloads
- Scenario-based PySpark problem solving
