# Home Sales Analysis with PySpark  
Module 22 Challenge 

This project analyzes home sales data using **PySpark**. The dataset is sourced from an AWS S3 bucket and processed for insights.  

## Features  
- **Load Data**: Reads `home_sales_revised.csv` from S3 into a PySpark DataFrame.  
- **SQL Queries**: Performs analytical queries on home sales data.  
- **Caching**: Implements caching for improved performance.  
- **Partitioning**: Saves data in Parquet format, partitioned by `date_built`.  
- **Performance Comparison**: Measures query runtimes for cached vs. Parquet data.  
