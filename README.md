# 📊 Customer Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![SQL](https://img.shields.io/badge/SQL-Database-orange)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-green)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Project-success)

An end-to-end data analytics project that analyzes retail customer behavior and converts raw transactional data into actionable business insights using **Python, SQL, and Power BI**.

This project demonstrates a complete **data analytics workflow**, including data cleaning, exploratory data analysis, SQL-based business queries, and an interactive dashboard for decision-making.

---

## 📌 Project Overview

This project analyzes **customer shopping behavior** to identify purchasing patterns, revenue drivers, and customer segments.

The analysis combines **Python, SQL, and Power BI** to transform raw customer data into meaningful business insights.

The project demonstrates the complete data analytics workflow used by data analysts in real business environments:

- Data loading and exploration using Python  
- Data cleaning and preprocessing  
- SQL-based business analysis  
- Interactive Power BI dashboard creation  
- Insight generation and reporting  

---

## 📌 Quick Summary

• Dataset analyzed: 3,900+ customer records  
• Tools used: Python, SQL, Power BI  
• Dashboard created for sales and customer insights  
• Identified top revenue categories and customer segments

## 🎯 Business Problem

Retail businesses need to understand **customer purchasing behavior** to improve marketing strategies, optimize product offerings, and increase revenue.

This project answers questions such as:

- Which product categories generate the highest revenue?
- Which age group contributes the most sales?
- Do subscribed customers spend more than non-subscribed customers?
- How do discounts affect purchasing behavior?
- Which products have the highest review ratings?

---

## 📊 Dashboard Preview

![Dashboard](Customer_bahevior_Dashboard.png)

## 📂 Dataset

The dataset contains customer shopping activity including:

- Customer ID  
- Gender  
- Age Group  
- Category  
- Item Purchased  
- Purchase Amount  
- Review Rating  
- Subscription Status  
- Shipping Type  
- Discount Applied  
- Previous Purchases  

This dataset enables analysis of **customer demographics, product performance, and revenue trends**.

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|------|--------|
| Python | Data loading and analysis |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Data visualization |
| SQL | Data querying |
| MySQL / PostgreSQL / SQL Server | Database analysis |
| Power BI | Interactive dashboard |
| Gamma AI | Presentation creation |

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading

- Imported dataset using **Pandas**
- Examined dataset structure
- Checked column types and sample records

### 2️⃣ Exploratory Data Analysis (EDA)

Performed analysis to understand the dataset:

- Purchase amount distribution
- Customer demographic analysis
- Product category performance
- Review rating distribution

Visualizations were created using **Matplotlib and Seaborn**.

### 3️⃣ Data Cleaning

Data preprocessing steps included:

- Handling missing values
- Removing duplicate records
- Standardizing column names
- Correcting data types

This ensured the dataset was **ready for analysis**.

---

## 🗄 SQL Analysis

SQL queries were used to generate business insights.

### Revenue by Gender

SELECT gender, SUM(purchase_amount) AS revenue  
FROM customer  
GROUP BY gender;

### Top Rated Products

SELECT item_purchased, ROUND(AVG(review_rating),2) AS avg_rating  
FROM customer  
GROUP BY item_purchased  
ORDER BY avg_rating DESC  
LIMIT 5;

### Customer Segmentation

Customers were categorized based on previous purchases:

- New Customers  
- Returning Customers  
- Loyal Customers  

---

## 📈 Key Insights

✔ Clothing category generates the **highest revenue**

✔ **Young Adult customers** contribute the most purchases

✔ **73% of customers are non-subscribers**

✔ Customers using **discounts still spend above average**

✔ Loyal customers generate **repeat purchases**

---

## 🧠 Skills Demonstrated

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- SQL Query Development  
- Data Visualization  
- Power BI Dashboard Development  
- Business Insight Generation  

---

## 📁 Project Structure

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
│   └── Customer_Behavior.pbix  
│  
├── images  
│   └── Customer_behavior_Dashboard.png  
│  
└── README.md  

---

## ▶️ How to Run the Project

### Clone the Repository

git clone https://github.com/pranali108/customer_behavior_analysis.git

### Install Required Libraries

pip install pandas numpy matplotlib seaborn

### Run Python Notebook

Open and run:

Customer_Shopping_Behaviour_Analysis.ipynb

### Execute SQL Queries

Run queries from:

customer_shopping_behavior_sql_queries.sql

### Open Power BI Dashboard

Open the **Power BI (.pbix) file** to explore interactive visualizations.

---

## 🚀 Future Improvements

- Customer churn prediction using machine learning  
- Customer lifetime value analysis  
- Deploy dashboard using Power BI Service  
- Automate data pipeline using Python  

---

## 📌 Conclusion

This project demonstrates how **Python, SQL, and Power BI can be combined to perform end-to-end data analysis and generate actionable insights from customer data**.

The analysis helps businesses better understand customer behavior and make **data-driven decisions**.
