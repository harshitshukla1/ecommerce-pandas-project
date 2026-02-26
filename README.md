📊 E-Commerce Data Analysis using Pandas
Overview

This project focuses on analyzing e-commerce data using Python and Pandas. It follows a typical data analysis workflow—starting from raw data cleaning to generating business insights.

The goal is to work with multiple datasets, prepare them for analysis, and extract meaningful information that can support decision-making.

Dataset

The analysis is based on four datasets:

Orders – order-level details

Customers – customer information

Products – product catalog

Payments – transaction records

Data Preparation

Before analysis, the datasets were cleaned and standardized:

Missing values were handled appropriately

Date formats were unified

Duplicate records were removed

Inconsistent entries were corrected

Relationships between datasets were validated

Data Processing

All datasets were merged into a single working dataset

A new column was created:
revenue = quantity × price

Analysis
Business Metrics

Total revenue

Total number of orders

Total number of customers

Product Insights

Best-selling products

Highest revenue-generating products

Performance by category

Customer Insights

Top customers by revenue

Purchasing patterns

Payment Analysis

Distribution of completed, failed, and pending payments

Estimated revenue loss from failed transactions

Time-based Trends

Revenue trends over time

Key Findings

Certain products and categories consistently drive higher revenue

A small segment of customers contributes significantly to total sales

Failed payments represent a measurable revenue loss


Tech Stack

Python

Pandas


Project Structure
data/        # raw datasets
notebooks/   # analysis notebooks
output/      # generated results
README.md
Conclusion

This project demonstrates a complete data analysis pipeline, from preprocessing to insight generation, using real-world structured data.

Author

Harshit Shukla
