📊 Customer Shopping Behavior Analysis
🔎 Overview

This project analyzes customer shopping behavior for a retail company to identify trends, improve customer engagement, and optimize marketing and product strategies.

Using Python, PostgreSQL, and Power BI, the project explores transactional data from 3,900 customer purchases to uncover insights into spending patterns, customer segmentation, subscription behavior, and purchase drivers. 


The end goal is to transform raw consumer data into actionable business insights that support data-driven decision-making.

📁 Dataset

Total Records: 3,900 transactions

Total Columns: 18 features 

Key Attributes:

Customer Demographics (Age, Gender, Location, Subscription Status)

Purchase Details (Category, Item Purchased, Purchase Amount, Season)

Behavioral Data (Discount Applied, Review Rating, Shipping Type, Previous Purchases)

Missing Values: 37 missing values in the Review Rating column. 

The dataset enables analysis of revenue trends, customer loyalty, discount effectiveness, and demographic patterns.

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

PostgreSQL

SQL (Business Queries)

Power BI

Jupyter Notebook / Anaconda

Git & GitHub

🔄 Project Steps
1️⃣ Data Preparation & Cleaning (Python)

Loaded dataset using Pandas

Performed structure and summary checks (df.info(), describe())

Handled missing values in Review Rating using category-based median imputation

Standardized column names (snake_case format)

Created new features:

age_group

Customer segments (New, Returning, Loyal)

Removed redundant fields (e.g., promo_code_used) 

Customer Shopping Behavior Anal…

Loaded cleaned data into PostgreSQL

2️⃣ Data Analysis (SQL – PostgreSQL)

Structured SQL queries were written to answer key business questions:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Rating

Shipping Type Comparison

Subscribers vs Non-Subscribers

Discount-Dependent Products

Customer Segmentation

Revenue by Age Group 

Window functions, aggregation, filtering, and segmentation logic were applied to simulate real business analytics scenarios.

📊 Power BI Dashboard

An interactive Power BI dashboard was built to visualize key insights. 

Key Dashboard KPIs:

Total Customers (3.9K)

Average Purchase Amount

Average Review Rating

Revenue by Category

Revenue by Age Group

Subscription Distribution

Sales by Category

The dashboard enables dynamic filtering by:

Subscription Status

Gender

Category

Shipping Type

📈 Key Results & Insights

Certain age groups contributed higher revenue than others.

Subscription customers showed strong revenue contribution.

Discount-heavy products had higher purchase frequency.

Express shipping users had slightly higher average spending.

Loyal customers represented the largest segment. 

Business Recommendations:

Promote subscription benefits

Reward repeat buyers with loyalty programs

Optimize discount strategies

Highlight top-rated products in marketing campaigns 
