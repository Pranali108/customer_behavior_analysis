# customer_behavior_analysis
An end-to-end data analytics project that analyzes retail customer behavior and converts raw transactional data into actionable business insights using Python, SQL, and Power BI.  This project demonstrates the complete analytics workflow used by data analysts in real business environments.


📌 Project Overview

This project analyzes customer shopping behavior to identify purchasing patterns, revenue drivers, and customer segments. The analysis combines Python, SQL, and Power BI to transform raw customer data into meaningful business insights.

The project demonstrates a complete data analytics workflow, including:

Data loading and exploration in Python

Data cleaning and preprocessing

SQL-based business analysis

Interactive Power BI dashboard creation

Insight generation and reporting

🎯 Business Problem

Retail businesses need to understand customer purchasing behavior to improve marketing strategies, optimize product offerings, and increase revenue.

This project answers questions such as:

Which product categories generate the highest revenue?

Which age groups contribute the most sales?

Do subscribed customers spend more?

How do discounts affect purchasing behavior?

Which products have the highest customer ratings?

📊 Dashboard Preview
<img src="images/Customer_behavior_Dashboard.png" width="900">
Dashboard Highlights

Total Customers: 3.9K

Average Purchase Amount: $59.76

Average Review Rating: 3.75

Visualizations Included

Customer distribution by subscription status

Revenue by category

Sales by category

Revenue by age group

Sales by age group

Interactive Filters

Gender

Product Category

Subscription Status

Shipping Type

📂 Dataset

The dataset contains customer shopping activity including:

Customer ID

Gender

Age Group

Category

Item Purchased

Purchase Amount

Review Rating

Subscription Status

Shipping Type

Discount Applied

Previous Purchases

This dataset enables analysis of customer demographics, product performance, and revenue trends.

🛠 Tools & Technologies
Tool	Purpose
Python	Data loading and analysis
Pandas	Data manipulation
NumPy	Numerical operations
Matplotlib / Seaborn	Data visualization
SQL	Data querying
MySQL / PostgreSQL / SQL Server	Database analysis
Power BI	Interactive dashboard
Gamma AI	Presentation creation
⚙️ Project Workflow
1️⃣ Data Loading

Loaded dataset using Pandas

Examined dataset structure

Verified column types

2️⃣ Exploratory Data Analysis

Analyzed purchase distributions

Studied customer demographics

Examined category performance

Visualized data trends

3️⃣ Data Cleaning

Removed duplicates

Handled missing values

Standardized column names

Corrected data types

🗄 SQL Analysis

SQL queries were used to extract business insights.

Revenue by Gender
SELECT gender, SUM(purchase_amount) AS revenue
FROM customer
GROUP BY gender;
Top Rated Products
SELECT item_purchased, ROUND(AVG(review_rating),2) AS avg_rating
FROM customer
GROUP BY item_purchased
ORDER BY avg_rating DESC
LIMIT 5;
Customer Segmentation

Customers were categorized as:

New Customers

Returning Customers

Loyal Customers

based on their previous purchase history.

📈 Key Insights

✔ Clothing category generates the highest revenue

✔ Young Adult customers contribute the most purchases

✔ 73% of customers are non-subscribers

✔ Customers using discounts still spend above average

✔ Loyal customers generate repeat purchases

🧠 Skills Demonstrated

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

SQL Query Development

Data Visualization

Power BI Dashboard Development

Business Insight Generation

📁 Project Structure
customer-shopping-behavior-analysis
│
├── dataset
│   └── customer_shopping_behavior.csv
│
├── notebooks
│   └── Customer_Shopping_Behaviour_Analysis.ipynb
│
├── sql
│   └── customer_shopping_behavior_sql_queries.sql
│
├── dashboard
│   └── Customer_Behavior_Dashboard.pbix
│
├── images
│   └── dashboard_preview.png
│
└── README.md
▶️ How to Run the Project
Clone Repository
git clone https://github.com/yourusername/customer-shopping-analysis.git
Install Required Libraries
pip install pandas numpy matplotlib seaborn
Run Python Notebook

Open:

Customer_Shopping_Behaviour_Analysis.ipynb
Execute SQL Queries

Run queries from:

customer_shopping_behavior_sql_queries.sql
Open Power BI Dashboard

Open the .pbix file in Power BI Desktop to explore the dashboard.

🚀 Future Improvements

Customer churn prediction using machine learning

Customer lifetime value analysis

Automated data pipeline using Python

Deployment of dashboard using Power BI Service

📌 Conclusion

This project demonstrates how Python, SQL, and Power BI can be combined to perform end-to-end data analysis and generate actionable insights from customer data to support business decision-making.
