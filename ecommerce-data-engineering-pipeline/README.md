# E-Commerce Data Engineering Pipeline

## Project Overview
An end-to-end E-Commerce Data Engineering project built using
Python, PySpark, SQL, and Databricks.

The project processes customer, product, and order data through
Bronze, Silver, and Gold layers.

## Technologies Used
- Python
- PySpark
- SQL
- Databricks
- Delta Lake

## Architecture

Source Data
    |
    v
Bronze Layer - Raw Data
    |
    v
Silver Layer - Data Cleaning and Deduplication
    |
    v
Gold Layer - Business Analytics

## Project Workflow
1. Created customer, product, and order datasets.
2. Stored raw datasets in Bronze tables.
3. Removed duplicate records in the Silver layer.
4. Handled missing customer names.
5. Joined customer, product, and order datasets.
6. Calculated product-wise revenue.
7. Created customer spending and order status reports.
8. Validated the final tables.

## Final Validation

| Table | Records |
|---|---:|
| Bronze Customers | 7 |
| Bronze Products | 6 |
| Bronze Orders | 10 |
| Silver Customers | 5 |
| Silver Products | 5 |
| Silver Orders | 9 |
| Gold Product Sales | 4 |
| Gold Customer Spending | 5 |
| Gold Order Summary | 3 |

## Key Learnings
- PySpark DataFrame transformations
- Data cleaning and deduplication
- Inner Join and Left Join
- Aggregations and revenue calculations
- Bronze, Silver, and Gold architecture
- Delta table creation and validation
