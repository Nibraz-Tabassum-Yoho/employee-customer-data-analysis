Orders Data Analysis
Project Overview

This project analyzes customer orders to understand revenue, customer purchasing behavior, and order patterns.

Dataset

The project uses an orders CSV dataset containing:

order_id
customer_id
amount
Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Git and GitHub
Initial Data Analysis

The following checks were performed:

Dataset shape
Dataset information using info()
Statistical summary using describe()
Missing values using isna().sum()
Duplicate records using duplicated().sum()

Business Questions:
1.What is the total revenue generated from all orders?
2.Which customer has placed the highest number of orders?
3.Which customer has generated the highest revenue?
4.What is the average order amount?
5.How many duplicate orders and missing order amounts exist?

Project Structure:
text
employee-customer-data-analysis/
├── data/
│   └── data.csv
├── notebooks/
│   └── orders_data_analysis.ipynb
├── README.md
└── requirements.txt

Project Progress:
Repository setup
Feature branch creation
Dataset loaded
Initial data inspection
Business questions defined
Data cleaning
Exploratory data analysis
Business insights