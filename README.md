# 🛍️ Consumer Shopping Behavior Analysis: End-to-End Retail Strategy
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
![Database](https://img.shields.io/badge/MySQL-Analysis-blue?style=for-the-badge&logo=mysql)
![Python](https://img.shields.io/badge/Python-EDA-green?style=for-the-badge&logo=python)

## 📌 Project Overview
This project addresses a critical business problem: how to leverage consumer shopping data to identify trends, improve engagement, and optimize marketing strategies. I analyzed a dataset of **3,900 purchases** across 18 key features to uncover actionable insights into demographics, subscription behavior, and purchase drivers.

## 🛠️ Data Analytics Workflow

### 1. Data Preparation & Engineering (Python)
Using `pandas` in the `Customer_Shopping_Behavior_Analysis.ipynb` notebook, I performed the following ETL tasks:
* **Missing Value Imputation**: Handled 37 missing values in the `Review Rating` column using the median rating per product category.
* **Feature Engineering**: Created an `age_group` column for demographic segmentation and a `purchase_frequency_days` column.
* **Cleanup**: Renamed columns to `snake_case` and dropped redundant features like `promo_code_used` to ensure data consistency.

### 2. Business Logic & Analysis (SQL)
After loading the cleaned data into **MySQL**, I executed structured queries in `customer_behavior_sql_queries.sql` to answer 10 critical business questions:
* **Revenue Leadership**: Identified that **Male** customers generated **$157,890** in revenue vs. **$75,191** from **Females**.
* **Customer Segmentation**: Classified the database into **Loyal (3,116)**, **Returning (701)**, and **New (83)** segments based on purchase history.
* **Top Performance**: Identified **Young Adults** as the highest revenue group ($62,143) and **Jewelry** as the top-selling accessory.

### 3. Executive Reporting (Power BI)
I built an interactive dashboard in `customer_behavior_dashboard.pbix` to visualize KPIs:
* **Core Metrics**: 3.9K Customers | $59.76 Avg. Purchase | 3.75 Avg. Rating.
* **Insights**: Discovered that while **27%** of customers are subscribers, non-subscribers have a slightly higher average spend ($59.87).

---

## 📂 Repository Structure
* **`customer_shopping_behavior.csv`**: The primary raw dataset containing 3,900 records.
* **`Customer_Shopping_Behavior_Analysis.ipynb`**: Python notebook for data cleaning, EDA, and feature engineering.
* **`customer_behavior_sql_queries.sql`**: MySQL scripts used for business transaction analysis and segmentation.
* **`customer_behavior_dashboard.pbix`**: Interactive Power BI dashboard showing sales and demographic trends.
* **`Customer-Shopping-Behavior-Analysis.pptx`**: Stakeholder presentation with visual findings and strategic advice.
* **`Customer Shopping Behavior Analysis.pdf`**: Detailed project report summarizing insights and methodology.
* **`Business Problem Document.pdf`**: Original project scope and overarching business questions.

---

## 💡 Key Business Recommendations
* **🚀 Loyalty Conversion**: Implement targeted rewards for the **701 "Returning" customers** to transition them into the "Loyal" tier.
* **💳 Subscription Growth**: Market exclusive benefits to the **73% of non-subscribers** who currently demonstrate high purchasing power.
* **📦 Shipping Strategy**: Focus marketing on **Express Shipping** options, as these users correlate with higher overall order values.
* **🧢 Product Positioning**: Highlight top-rated and best-selling products like **Jewelry** and **Blouses** in seasonal campaigns.

---
**Author**: Mopuru Dinesh 
**LinkedIn**: linkedin.com/in/mopuru-dinesh
