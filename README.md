# module22challenge
# Overview
In this challenge, you'll leverage SparkSQL to analyze home sales data and perform various operations including creating temporary views, caching data, and partitioning. This project involves working with a Spark DataFrame to answer specific queries about home prices and their attributes.

# Set Up Your Environment

- Import the necessary PySpark SQL functions.
- Load Data

- Read home_sales_revised.csv into a Spark DataFrame.
- Create Temporary Table

- Create a temporary table named home_sales.
- Answer Queries Using SparkSQL

  - Query 1: What is the average price for a four-bedroom house sold each year? Round to two decimal places.
  - Query 2: What is the average price of a home built each year with three bedrooms and three bathrooms? Round to two decimal places.
  - Query 3: What is the average price of a home built each year with three bedrooms, three bathrooms, two floors, and at least 2,000 square feet? Round to two decimal places.
  - Query 4: What is the average price per "view" rating for homes with an average price greater than or equal to $350,000?      - Include query runtime, rounded to two decimal places.
  
  - Cache and Uncache Operations

- Cache the home_sales temporary table.
- Verify the temporary table is cached.
- Run Query 4 using the cached data and compare runtime with uncached data.
- Uncache the home_sales temporary table.
- Verify that the table is uncached.

# Partitioning and Parquet Data

- Partition the dataset by the date_built field and save it as a Parquet file.
- Create a temporary table for the Parquet data.
- Run Query 4 on the Parquet temporary table and compare runtime with previous results.

# Final Steps

Download your Home_Sales.ipynb file.
Upload it to your Home_Sales GitHub repository.
