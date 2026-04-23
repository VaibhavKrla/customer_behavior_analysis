# Customer Shopping Behavior Analysis 🛍️

## Overview
This project provides a comprehensive analysis of consumer shopping behavior for a leading retail company. The primary objective is to uncover actionable insights into customer demographics, purchasing patterns, and the effectiveness of marketing strategies (like discounts and subscriptions) to optimize product offerings and enhance customer engagement.

## Dataset
The analysis is based on the **Customer Shopping Behavior Dataset**, which includes transaction-level data such as:
- **Demographics:** Age, Gender, Location.
- **Transaction Details:** Item Purchased, Category, Purchase Amount (USD), Payment Method.
- **Behavioral Metrics:** Review Rating, Subscription Status, Frequency of Purchases, Previous Purchases.
- **Marketing Impact:** Shipping Type, Discount Applied, Promo Code Used.

## Tools & Technologies
- **Python:** Data cleaning, preprocessing, and exploratory data analysis (EDA) using `pandas`.
- **SQL (PostgreSQL / MySQL / SQL Server):** Advanced data querying and customer segmentation using `SQLAlchemy`.
- **Power BI:** Interactive dashboard for visual storytelling and trend analysis.
- **Gamma / PowerPoint:** Professional presentation of findings and strategic recommendations.
- **PDF:** Structured business problem documentation and final analysis report.

## Project Steps
1.  **Data Preparation (Python):** Cleaned and transformed the raw CSV data, handling missing values and ensuring data type consistency for analysis.
2.  **Database Integration:** Migrated the cleaned data from Python into SQL environments (PostgreSQL, MySQL, and SQL Server) to simulate real-world business data workflows.
3.  **Data Analysis (SQL):** Performed complex aggregations and window functions to answer critical business questions, such as revenue distribution by gender and the impact of discounts on high-value purchases.
4.  **Data Visualization (Power BI):** Developed a multi-page interactive dashboard focusing on sales performance, customer demographics, and product trends.
5.  **Reporting & Presentation:** Compiled insights into a stakeholder-ready PowerPoint presentation (via Gamma) and a detailed PDF report.

## Dashboard Highlights
The **Power BI Dashboard** includes:
- **Sales Performance:** Total revenue and average purchase amounts across different categories.
- **Customer Segmentation:** Analysis of loyal vs. new customers and their spending habits.
- **Geographic Insights:** Heatmaps showing top-performing locations.
- **Marketing Effectiveness:** Comparison of purchase rates with and without discount applications.

## Key Results & Insights
- **Revenue Drivers:** Identified specific product categories (e.g., Clothing and Footwear) that contribute most to the total revenue.
- **Discount Impact:** Analyzed how discount applications correlate with higher-than-average purchase amounts, suggesting effective promotional strategies.
- **Customer Loyalty:** Segmented customers based on purchase frequency, highlighting the high value of "Loyal" subscribers who spend more on average.
- **Shipping Preferences:** Observed a significant preference for standard shipping, providing an opportunity for optimized delivery messaging.

## How to Run
1.  **Python Environment:** Install dependencies using `pip install pandas sqlalchemy psycopg2-binary pymysql pyodbc`.
2.  **SQL Setup:** Use the provided `customer_behavior_sql_queries.sql` to run analysis on your preferred SQL database.
3.  **Power BI:** Open `customer_behavior_dashboard.pbix` in Power BI Desktop to view and interact with the visualizations.
4.  **Reports:** Review `Business Problem Document.pdf` and `Customer Shopping Behavior Analysis.pdf` for the full project context and findings.
