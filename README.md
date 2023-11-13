# Home-Sales
 
## Project Description

In this challenge, we demonstrate our knowledge of SparkSQL and apply it to Big Data. In particular, we take a home sales data file and process temporary views, partition the data, and cache and uncache a temporary table. 

This challenge is completed in a Python Notebook using Google Colab.

## Questions for Analysis
1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

The 4th question is then demonstrated in two different instances: caching the data and partitioning the data. It is for the purpose of determining which instance accesses the data faster. 

As per the results, we can determine that cached data is accessed faster at a ate of 0.168 seconds vs. partitioned data at 0.244. Both of these codes were ran multiple times to test for accuracy. 

## Files
1. Home_Sales_colab file

# Dependencies
1. Python
2. Pandas
3. Spark
4. pyspark.sql

## Programs/Languages
1. Python
2. Google Colab
