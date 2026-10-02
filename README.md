# customer_shop_analysis
Analysis the customer analysis using postgreSQL, SQL Query and Power Bi.

Customer Shopping Behavior Analysis 🛍️
Overview
This project delivers an end-to-end data analytics solution examining customer purchasing habits, demographics, and product performance. By combining Python for data wrangling, PostgreSQL for advanced querying, Power BI for interactive visualization, and Gamma for presentation, this project uncovers actionable business insights to drive targeted marketing and revenue growth.
Dataset
Source: Customer Shopping Behavior Dataset
Key Attributes: Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount (USD), Review Rating, Subscription Status, Shipping Type, Discount Applied, Previous Purchases, and Payment Method.
Tools & Technologies
Python (Jupyter Notebook): Data loading, Exploratory Data Analysis (EDA), and data cleaning.
PostgreSQL & pgAdmin 4: Database creation, data migration via SQLAlchemy, and exploratory SQL analysis.
Power BI: Interactive dashboarding and KPI visualization.
Gamma: Professional presentation deck creation.
MS Word/Docs: Analytical reporting.
Project Workflow & Steps
Data Loading & Preprocessing (Python):
Loaded the raw CSV dataset into a Pandas DataFrame.
Inspected data types, summary statistics, and identified missing values.
Handled missing values (e.g., imputing missing review ratings with category-specific medians).
Standardized text columns and mapped categorical variables into numeric equivalents where necessary.
Database Integration (SQL):
Configured a local PostgreSQL database (customer_behavior).
Exported the cleaned Pandas DataFrame directly into PostgreSQL using SQLAlchemy and psycopg2.
SQL Business Analysis:
Wrote and executed targeted SQL queries to answer critical business questions (e.g., comparing revenue by gender, identifying top-performing products, analyzing subscription impact on spend, and segmenting customer loyalty).
Visualization & Reporting:
Connected Power BI to the PostgreSQL database to design an interactive dashboard tracking total revenue, average spend, and product category trends.
Compiled comprehensive findings into an analytical report and designed a sleek summary presentation using Gamma.
Power BI Dashboard
Key Metrics Tracked: Total Revenue, Average Order Value, Total Customers, and Category-wise Breakdown.
Interactive Filters: Filter by Subscription Status, Age Group, and Gender to drill down into specific customer segments.
Key Results & Insights
Subscription Impact: Subscribed customers demonstrate a higher average spend compared to non-subscribers, indicating that loyalty programs effectively increase customer lifetime value.
Top Categories: Electronics and Clothing generate the highest overall revenue contribution.
Discount Sensitivity: A significant percentage of repeat buyers utilize discounts, highlighting opportunities to optimize promotional strategies.
How to Run This Project
Clone the repository:
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git


Run the Jupyter Notebook:
Open Jupyter Notebook or Jupyter Lab.
Run Customer_shopping_behavior_Analysis.ipynb to execute data cleaning and export data to PostgreSQL.
Execute SQL Queries:
Open pgAdmin 4, connect to your local PostgreSQL server, and run the queries provided in the SQL script file to view analytical insights.
View the Power BI Dashboard:
Open the .pbix file included in the repository and refresh the data source connection pointing to your local PostgreSQL database.
