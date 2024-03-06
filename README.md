## READ ME
This repository contains code written in Python using Apache Spark for analyzing home sales data. The code performs various Spark SQL queries on a dataset of home sales records to extract insights such as average prices, partitioning data, and caching tables for optimization.

# Requirements
Python 3.x
Apache Spark
PySpark
This repository contains Python code leveraging Apache Spark for analyzing home sales data. Utilizing PySpark, the code executes various Spark SQL queries on a dataset of home sales records to extract valuable insights. The process begins with initializing Spark and loading the data from an AWS S3 bucket into a DataFrame. Subsequently, the code performs data analysis tasks such as calculating average prices, grouping data by specific criteria, and ordering results. Additionally, it partitions the data by the "date_built" field and writes it to a parquet file for optimized storage and querying. To enhance performance, the code caches the temporary table containing home sales data and releases cached resources after analysis. This project provides a robust framework for analyzing large-scale home sales datasets efficiently and offers flexibility for customizing analyses based on specific requirements.
