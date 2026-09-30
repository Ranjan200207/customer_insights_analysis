🛍️ Customer Insights Dashboard

An end-to-end Customer Shopping Behavior Analysis project that combines Python, PostgreSQL, SQL, and a business dashboard to transform raw customer transaction data into actionable insights.
The project covers data cleaning and preparation in Python, database creation and loading in PostgreSQL, business-question analysis using SQL, and interactive visualization through a customer insights dashboard. 

🎯 Project Objective
The main objective of this project is to analyze customer shopping behavior and understand patterns related to:
1. Customer demographics
2. Purchase amounts and revenue
3. Product categories
4. Customer subscriptions
5. Discounts and promotional activity
6. Shipping methods
7. Customer review ratings
8. Previous purchases and customer segments
9. Purchase frequency
10. Age-group purchasing behavior
The analysis is designed to turn raw customer-level data into useful business insights that can support customer understanding and sales analysis.

🧹 Data Cleaning & Preparation
The dataset contains 3,900 customer records with 18 original columns.
Python was used for initial data exploration and preparation.

Steps performed -:
1. Loaded the CSV dataset using Pandas.
2. Inspected the dataset using:head() info() describe()
3. missing-value checks - Found 37 missing values in Review Rating
4. Filled missing review ratings using the median review rating within each product category.


🐍 Python
The Python notebook performs the data preparation workflow.
Main libraries-
1. Pandas
2. SQLAlchemy
3. psycopg2-binary

🗄️ PostgreSQL Database
The cleaned data was loaded into a PostgreSQL database.
The notebook uses SQLAlchemy to connect Python with PostgreSQL and loads the DataFrame using python

    
Database workflow
   text
CSV Dataset
     ↓
Python / Pandas
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
PostgreSQL
     ↓
SQL Analysis
     ↓
Customer Insights Dashboard

💡 Key Project Highlights
1. Analyzed 3,900 customer records, Worked with 18 original data attributes, Handled missing review-rating values, Performed feature engineering for age groups and purchase frequency, Loaded cleaned data into PostgreSQL.
2. Created SQL queries for 10 business questions
3. Used SQL aggregation, subqueries, CTEs, CASE, and window functions
4. Built an interactive customer insights dashboard
5. Added filters for customer and transaction dimensions

📌 Skills Demonstrated
This project demonstrates practical skills in:
Data Analytics
Data cleaning
Exploratory data analysis
Feature engineering
Business-question analysis

👨‍💻 Author
D. Ranjan
🐙 GitHub: Ranjan200207

⭐ If you find this project useful
Feel free to explore the SQL queries, notebook, and dashboard, and use the project as a reference for customer behavior and retail analytics.
