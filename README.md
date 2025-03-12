## Overview

Welcome to the Intermate Shop analytics engineering case study! 
This exercise is designed to evaluate your ability to work with dbt (Data Build Tool) and transform raw data into meaningful analytics tables.

Your task is to create a dbt project that processes and models data from two sources:
- Shopify Orders Data (intermate_shop_orders.csv)
- Facebook Ads Insights Data (facebook_ads_insights.csv)

Using dbt, you should create cleaned, transformed, and analytics-ready tables that follow best practices in data modeling.

## Tasks
1. Use a database of your choice (Bigquery free trial (credit card required), Postgres or duckdb).
2. Setup a dbt project.
3. Stage and clean the data.
4. Transform the data into tables for analytical use.
5. The following information is needed by your stakeholders in the finished tables:
    - number of new customer orders per day
    - a table for the performance of various discount codes
    - a table that combines both data sources and can be used by performance marketers for a overview over daily performence.
    - a customer dimension table
    - bonus: we need all values in euro
6. Push your code to a repo that we can access for review.


## Evaluation Criteria
- Code structure: Follows dbt best practices.
- Data quality: Properly handled NULL values, data types, and integrity.
- Reusability: Modular and well-structured SQL models.
- Documentation: Clear and informative schema.yml.