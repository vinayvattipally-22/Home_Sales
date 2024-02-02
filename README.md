# Home Sales Analysis - README
## Introduction:

This document provides a comprehensive overview of the Home Sales Analysis assignment performed using Google Colab, PySpark, and SQL. The analysis involves reading and processing a dataset containing information about home sales. Below is a step-by-step guide, including both input code cells and output results.

## Prerequisites:

Ensure you have the necessary libraries and dependencies installed before running the program:

 * PySpark
 * pandas
 * findspark

You can install these libraries using the following command:
bash'''
pip install pyspark pandas findspark
'''
## Usage:

 * Import the required libraries and dependencies.
 * Read the home sales data from an AWS S3 bucket into a PySpark DataFrame.
 * Create a temporary view of the DataFrame to facilitate SQL queries.
 * Explore and analyze the data using various SQL queries, such as finding average prices for different bedroom configurations, view ratings, and more.
 * Utilize caching to optimize query performance.
 * Partition the data by the "date_built" field and write it in parquet format.
 * Read the parquet-formatted data and create a temporary table for further analysis.
 * Run additional queries on the parquet data, including filtering based on view ratings and average prices.

## Results and Analysis:

 1. Analysis of Average Prices for Different Bedroom Configurations Over the Years.
 2. Average Prices of Homes Built Each Year with 3 Bedrooms and 3 Bathrooms.
 3. Average Prices of Homes with Specific Features (3 bedrooms, 3 bathrooms, 2 floors, and at least 2000 sqft).
 4. View Ratings for Homes with Prices Greater Than or Equal to $350,000.
 5. Comparison of Query Runtimes with and without Caching.
 6. Partitioning Home Sales Data by "date_built" and Running Queries on Parquet Data.

## Conclusion:

The script provides valuable insights into the home sales dataset, demonstrating the power of PySpark and SQL for efficient data analysis. The results showcase trends in average prices, bedroom configurations, and the impact of specific features on home prices. The use of caching and parquet formatting contributes to improved query performance and data storage efficiency. Further exploration and adaptation of queries can enhance the depth of analysis for different datasets.