# anushkaadubey_2511015_part1_datacleaning
BITSOM CAPSTONE  
Project Overview

This project focuses on data cleaning, validation, transformation, and exploratory analysis of a retail sales dataset. The objective was to improve data quality, prepare the dataset for analysis, and generate meaningful business insights using Microsoft Excel.

The project involved identifying data quality issues, handling missing values, removing duplicates, standardizing formats, creating derived metrics, and summarizing results through pivot tables and visualizations.

Dataset Information

Dataset Name: Raw Orders Dataset

Source: Assignment-provided retail sales data

The dataset contains information related to:

Orders
Customers
Products
Sales
Shipping
Regions
Order Status
Tasks Performed
Task 1: Data Cleaning

The following cleaning activities were performed:

Identified and handled missing values
Detected and removed duplicate records
Standardized text fields and categorical values
Cleaned and validated date columns
Verified data types
Removed formatting inconsistencies
Validated order and shipping dates
Additional Feature Engineering

A new column named shipping_delay_days was created using:

shipping_delay_days = ship_date - order_date

This metric was used to analyze delivery performance.

Task 2: Data Analysis Using Pivot Tables

Pivot tables were created to summarize and analyze:

Sales by Region
Sales by Category
Sales by Customer Segment
Order Status Distribution
Average Shipping Delay by Shipping Mode
Task 3: Dashboard and Visualization

Charts and summaries were created to provide a visual representation of business performance and operational trends.

Key metrics analyzed include:

Total Sales
Regional Performance
Product Category Performance
Customer Segment Contribution
Shipping Performance
Tools Used
Microsoft Excel
Pivot Tables
Conditional Formatting
Data Validation
Formulas and Functions
Charts and Visualizations
Key Insights
Data quality issues such as duplicates and inconsistent formatting were successfully resolved.
Sales performance varied significantly across regions and product categories.
Customer segments contributed differently to overall revenue.
Shipping delays were measured using a derived metric for operational analysis.
Clean and standardized data improved the reliability of analytical results.
Repository Structure
├── raw_orders.xlsx
├── cleaned_dataset.xlsx
├── mapping_sheet.xlsx
├── pivot_tables.xlsx
├── dashboard_screenshots/
├── task_report.docx
└── README.md
Conclusion

This project demonstrates the complete workflow of preparing raw business data for analysis. Through data cleaning, validation, feature engineering, and reporting, the dataset was transformed into a reliable source for business decision-making and performance evaluation.
