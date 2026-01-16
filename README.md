📊 Fashion Retail Analytics: Consumer Behavior & Strategy
📌 Project Overview
This project performs an end-to-end analysis of 3,900 customer transactions for a fashion and accessories retail store. By integrating Python for ETL, MySQL for business logic, and Power BI for executive reporting, I uncovered key drivers behind customer spending, subscription rates, and brand loyalty.





🛠️ Data Pipeline & Transformation
1. Data Cleaning (Python)

Missing Value Imputation: Handled 37 missing values in the Review Rating column by applying the median rating of each product category.



Feature Engineering: Created an age_group column to segment customers and a purchase_frequency_days column to track engagement.


Standardization: Converted all column headers to snake_case for database compatibility.

2. Business Analysis (MySQL)
I executed structured queries to answer 10 critical business questions, focusing on revenue and segmentation.


Revenue by Gender: Identified that Male customers contribute $157,890 in revenue compared to $75,191 from Female customers.



Customer Segmentation: Classified the database into three tiers: Loyal (3,116), Returning (701), and New (83).



Shipping Correlation: Confirmed that Express Shipping users have a higher average spend ($60.48) than Standard Shipping users ($58.46).


3. Interactive Visualization (Power BI)
I built a high-fidelity dashboard to track KPIs at a glance:


Core KPIs: Total Customers (3.9K), Avg. Purchase Amount ($59.76), and Avg. Review Rating (3.75).




Category Insights: Visualized that Clothing and Accessories are the primary revenue drivers.



Subscription Breakdown: Visualized that 27% of the customer base is subscribed, while 73% are not.


📈 Key Business Insights

Top Performance: The Young Adult age group is the highest revenue contributor ($62,143), followed closely by Middle-aged shoppers ($59,197).


Product Popularity: Jewelry and Blouses are the top-selling items within the Accessories and Clothing categories, respectively.


Discount Impact: Products like Hats and Sneakers have the highest discount dependency, with nearly 50% of their sales involving a promo code.

💡 Strategic Recommendations

Segment Transition: Develop a targeted campaign to move the 701 "Returning" customers into the "Loyal" tier through personalized rewards.



Subscription Upsell: Since non-subscribers have a slightly higher average spend ($59.87) than subscribers ($59.49), there is a significant opportunity to convert high-value shoppers into the subscription model for long-term retention.



Logistics Marketing: Promote Express Shipping options more aggressively, as these users correlate with higher overall order values.


📂 Project Structure
scripts/data_cleaning.py: Python ETL script for cleaning and normalization.

sql/analysis_queries.sql: 10 business queries for revenue, ranking, and segmentation.

visuals/dashboard.pbix: The interactive Power BI report file.

docs/report.pdf: Detailed project summary and recommendations.
