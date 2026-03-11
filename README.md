# customer_behaviour_analysis
Data analytics project for customer behavior using Python,SQL and PowerBI
Customer Behavior Data Analytics Project
Overview

This project analyzes customer purchasing behavior to identify patterns in sales, revenue, and customer demographics. The analysis was performed using Python, SQL, and Power BI, and the insights are presented through an interactive Customer Behavior Dashboard.

The goal of the project is to transform raw customer data into meaningful insights that help businesses understand:

Customer purchasing trends

Revenue contribution by product category

Sales distribution across different age groups

Customer subscription behavior

Overall customer satisfaction through review ratings

The final output includes data cleaning, SQL analysis, an interactive Power BI dashboard, and a presentation summarizing the results.

Dataset

The dataset contains customer transaction and demographic information used to analyze shopping behavior.

Main attributes in the dataset include:

Customer ID

Age

Gender

Item Purchased

Category

Purchase Amount (USD)

Location

Shipping Type

Season

Review Rating

Subscription Status

Previous Purchases

Payment Method

The dataset was loaded and prepared in Python before being analyzed using SQL and visualized in Power BI.

Tools & Technologies

The project uses the following tools:

Python (Pandas) – Data loading and cleaning

SQL (PostgreSQL / MySQL / SQL Server) – Data querying and analysis

Power BI – Interactive dashboard creation

Jupyter Notebook – Data analysis environment

Gamma – Presentation creation

Power BI Dashboard

The Customer Behavior Dashboard summarizes key business metrics and insights from the dataset.

Key Performance Indicators (KPIs)

The dashboard highlights three main KPIs:

3.9K Total Customers

$59.76 Average Purchase Amount

3.75 Average Review Rating

These metrics provide a quick overview of customer activity and purchasing behavior.

Dashboard Insights
1. Customer Subscription Status

The dashboard shows the percentage of customers who are subscribed versus non-subscribed.

73% Non-Subscribed Customers

27% Subscribed Customers

This indicates a potential opportunity to increase subscription adoption.

2. Revenue by Product Category

Revenue analysis across product categories shows:

Clothing generates the highest revenue

Followed by Accessories, Footwear, and Outerwear

This helps identify the most profitable product segments.

3. Sales by Category

The number of transactions by category indicates purchasing frequency.

Clothing has the highest number of sales

Accessories follows next

Footwear and Outerwear have lower sales volumes

4. Revenue by Age Group

Revenue contribution by age group shows that:

Young Adults generate the highest revenue

Middle-aged customers contribute the second highest

Adults and Seniors contribute slightly less

This insight helps businesses target their most valuable customer segments.

5. Sales by Age Group

The sales distribution by age group highlights which customers make the most purchases.

Young Adults and Middle-Aged customers represent the largest share of transactions.

Dashboard Filters

The dashboard allows users to interactively explore the data using filters such as:

Subscription Status

Gender

Category

Shipping Type

Shipping type options include:

2-Day Shipping

Express

Free Shipping

Next Day Air

Standard

Store Pickup

These filters help users analyze customer behavior under different conditions.

Project Workflow
1. Data Loading

The dataset was imported into Python using Pandas and inspected to understand its structure.

2. Data Cleaning

Data preprocessing included:

Handling missing values

Removing duplicate records

Correcting data types

Standardizing column names

3. SQL Analysis

The cleaned dataset was analyzed using SQL to extract insights such as:

Top selling categories

Customer purchase trends

Revenue by category

Sales distribution across demographics

4. Dashboard Development

The dataset was imported into Power BI where visualizations were created to build the final interactive dashboard.

Key Insights

Important findings from the analysis include:

Clothing is the top-performing category in both revenue and sales.

Young adults are the most active customers.

A large portion of customers are not subscribed, indicating potential growth for subscription programs.

The average purchase amount is approximately $59.76 per transaction.

Customer review ratings average 3.75, suggesting moderate satisfaction.

Project Structure
customer-behavior-analysis
│
├── data
│   └── shopping_dataset.csv
│
├── notebooks
│   └── data_analysis.ipynb
│
├── sql
│   └── analysis_queries.sql
│
├── dashboard
│   └── customer_behavior_dashboard.pbix
│
├── presentation
│   └── project_presentation.ppt
│
└── README.md
Conclusion

This project demonstrates how Python, SQL, and Power BI can be used to analyze customer data and transform it into actionable insights. The interactive dashboard helps businesses better understand purchasing patterns and supports data-driven decision making.
