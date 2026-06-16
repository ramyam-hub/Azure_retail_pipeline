# Azure Retail Sales Data Pipeline

## Project Overview
End-to-end retail sales data pipeline built on Microsoft Azure.

## Architecture
Raw Data → Azure Data Lake (Bronze) → 
Python Cleaning (Silver) → 
Analytics Tables (Gold) → 
Power BI Dashboard

## Tools Used
- Azure Data Lake Gen2
- Databricks (Python & PySpark)
- Power BI
- GitHub

## Project Structure
- Silver_layer.ipynb → Data cleaning and transformation
- Gold_layer.ipynb → Final analytics tables
- gold_*.csv → Gold layer summary tables
- sales_dashboard_powerbi.pbix → Power BI dashboard

## Key Insights
- Total Revenue: $3,865.73
- Top Category: Electronics
- Top City: Atlanta
- Total Orders: 10
