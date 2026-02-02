# Customer-Shopping-Behavior-Analysis
🛒 Customer Shopping Behavior Analysis

Python • PostgreSQL • Power BI

📌 Project Description

This project analyzes customer shopping behavior using retail transaction data to uncover patterns in spending, subscriptions, discounts, and customer segments.
The objective is to transform raw customer data into actionable business insights using an end-to-end analytics workflow involving Python, SQL, and Power BI.

Rather than focusing only on visuals, this project emphasizes data preparation, feature engineering, business-driven analysis, and insight generation.

🎯 Project Objectives

Clean and prepare raw customer data for analysis using Python 🧹

Engineer meaningful features to improve segmentation and analysis 🧠

Perform business analysis using SQL queries in PostgreSQL 🗄️

Build an interactive Power BI dashboard for insight communication 📊

Provide actionable business recommendations based on data insights 💡

🗂️ Dataset Overview

Rows: 3,900

Columns: 18

Key Data Areas

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Season, Size, Color, Purchase Amount

Behavioral Data: Discount Applied, Purchase Frequency, Review Rating, Shipping Type

⚠️ Missing values were present in the Review Rating column and handled during preprocessing.

🧭 Project Workflow
1️⃣ Data Preparation & Feature Engineering (Python)

Loaded and explored data using pandas

Handled missing review ratings using median imputation

Standardized column names for consistency

Created new features:

Age Groups for customer segmentation

Customer Purchase Segments (New, Returning, Loyal)

Prepared the dataset for SQL-based analysis

2️⃣ Business Analysis (PostgreSQL)

Loaded cleaned data into PostgreSQL

Wrote SQL queries to answer key business questions, including:

Revenue contribution by gender and age group

Subscriber vs non-subscriber spending behavior

Impact of discounts on purchase amounts

Identification of high-value and repeat customers

Top-performing products and categories

3️⃣ Data Visualization (Power BI)

Connected PostgreSQL database to Power BI

Designed an interactive dashboard highlighting:

Revenue and customer KPIs

Subscription trends

Category and demographic analysis

Created calculated measures (DAX) for advanced insights such as:

Revenue per customer

Subscriber revenue contribution

Discount effectiveness

📊 Key Insights

Subscribers spend more on average than non-subscribers

Young adults contribute the highest share of revenue

Certain categories rely heavily on discounts for sales volume

Express shipping is associated with higher purchase values

Loyal customers generate significantly higher lifetime value

💡 Business Recommendations

Strengthen subscription programs to improve customer retention

Introduce loyalty incentives for repeat customers

Optimize discount strategies to balance revenue and margins

Focus marketing efforts on high-value age groups and categories

🧰 Tools & Technologies

Python (pandas, numpy) – Data cleaning & feature engineering

PostgreSQL – SQL-based business analysis

Power BI – Dashboarding & visualization

Jupyter Notebook – Analysis & documentation

🏁 Conclusion

This project demonstrates an end-to-end data analytics workflow that mirrors real-world business analysis.
It highlights practical skills in data cleaning, SQL querying, feature engineering, and dashboard storytelling, making it suitable for data analyst portfolio and interview discussions.
