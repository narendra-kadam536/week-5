# week-5
## Advanced Data Manipulation with Pandas
## Customer Sales Analysis
## Project Overview

The Customer Sales Analysis project focuses on analyzing customer purchasing behavior and sales performance using Python and Pandas. The goal is to identify top customers, understand sales patterns, and create a dashboard-ready analysis with actionable business insights.

This project demonstrates real-world data analyst skills, including data cleaning, aggregation, merging datasets, pivot tables, and professional visualizations.

 ## Objectives
Analyze customer purchasing patterns
Identify top and high-value customers
Perform monthly and category-wise sales analysis
Create summarized views using pivot tables
Build a sales performance dashboard
Provide business insights and recommendations

## Technologies Used
Python
Pandas (data manipulation)
NumPy
Matplotlib
Seaborn
Jupyter Notebook
## Project Structure
Customer-Sales-Analysis/
│
├── customer_analysis.ipynb
├── sales_data.csv
├── customer_data.csv
├── analysis_report.pdf
├── requirements.txt
└── screenshots/
    ├── monthly_sales.png
    ├── top_customers.png
    ├── category_sales.png
    ├── pivot_table.png

## Dataset Description
## sales_data.csv
Column Name	Description
Sale_ID	Unique transaction ID
Customer_ID	Customer identifier
Product	Product name
Category	Product category
Sales_Amount	Transaction amount
Sale_Date	Date of sale

## customer_data.csv
Column Name	Description
Customer_ID	Unique customer ID
Customer_Name	Customer name
City	Customer city
## Setup & Installation
## Clone the Repository
git clone https://github.com/your-username/Customer-Sales-Analysis.git
cd Customer-Sales-Analysis

## Install Dependencies
pip install -r requirements.txt

## Run the Notebook
jupyter notebook customer_analysis.ipynb

## Analysis Workflow
## Day 1: Data Loading & Exploration
Loaded datasets
Inspected structure and data types
Checked for missing values

## Day 2: Data Cleaning & Preparation

Handled missing values
Converted date columns to datetime
Created year and month features
Cleaned text columns using string methods

## Day 3: Customer Analysis

Identified top customers by total spending
Calculated customer lifetime value (CLV)
Analyzed sales distribution by region

## Day 4: Sales Pattern Analysis

Monthly sales trend analysis
Identified best-selling products
Category-wise performance evaluation

## Day 5: Advanced Analysis

Created pivot tables for summarized insights
Calculated customer retention rate
Identified cross-selling opportunities

## Day 6: Dashboard Creation

Built multiple professional visualizations:
Line chart (Monthly sales trend)
Bar chart (Top customers)
Pie chart (Category-wise sales)
Horizontal bar chart (City-wise sales)
Heatmap (Pivot table summary)

## Day 7: Report & Insights

Documented findings
Provided business recommendations
Prepared executive summary

## Technical Requirements Fulfilled
Requirement	                         Implementation
Pandas for data manipulation	      Used throughout
3+ Aggregations	                    Monthly, Category, Customer
Data merging/joining	              Sales + Customer data
Pivot tables	                      City × Category
Professional visualizations         4+ chart types

## Key Insights

Top 20% of customers contribute a major portion of total revenue
Electronics category generates the highest sales
Sales show strong monthly seasonality
Metro cities have higher average order values
