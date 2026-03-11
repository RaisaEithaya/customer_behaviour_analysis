# customer_behaviour_analysis
Data analytics project for customer behavior using Python,SQL and PowerBI
Customer Behavior Data Analytics Project

**Overview**

This project analyzes customer purchasing behavior to identify patterns in sales, revenue, and customer demographics. The analysis was performed using Python, SQL, and Power BI, and the insights are presented through an interactive Customer Behavior Dashboard.

The goal of the project is to transform raw customer data into meaningful business insights that help organizations understand:

Customer purchasing trends

Revenue contribution by product category

Sales distribution across different age groups

Customer subscription behavior

Customer satisfaction through review ratings

The final output includes data cleaning, SQL analysis, an interactive Power BI dashboard, and a presentation summarizing the results.

**Dataset**

The dataset contains customer transaction and demographic data used to analyze shopping behavior.

**Key attributes include:**

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

The dataset was loaded and cleaned in Python, then analyzed using SQL and visualized in Power BI.

**Tools & Technologies**

The project uses the following technologies:

Python (Pandas) – Data loading and cleaning

SQL (PostgreSQL / MySQL / SQL Server) – Data querying and analysis

Power BI – Interactive dashboard creation

Jupyter Notebook – Data analysis environment

Gamma – Presentation creation

Power BI Dashboard

The Customer Behavior Dashboard provides a visual summary of key business metrics and insights.

**Key Performance Indicators (KPIs)**

The dashboard highlights three major KPIs:

3.9K Total Customers

$59.76 Average Purchase Amount

3.75 Average Review Rating

These metrics provide a quick overview of customer engagement and purchasing behavior.

**Dashboard Insights**
1. Customer Subscription Status

A donut chart shows the percentage of customers by subscription status:

73% Non-Subscribed Customers

27% Subscribed Customers

This indicates a significant opportunity to grow subscription-based customers.

2. Revenue by Product Category

Revenue distribution across categories shows:

Clothing generates the highest revenue

Followed by Accessories

Footwear

Outerwear

This insight helps businesses identify their most profitable product categories.

3. Sales by Category

The number of transactions by category highlights customer purchasing frequency.

Clothing has the highest sales volume

Accessories is the second most purchased category

Footwear and Outerwear have comparatively lower sales

4. Revenue by Age Group

Revenue contribution across customer age groups shows:

Young Adults generate the highest revenue

Middle-aged customers contribute the second highest

Adults and Seniors contribute slightly less

This helps identify high-value customer segments.

5. Sales by Age Group

Sales distribution shows that:

Young Adults and Middle-Aged customers make the most purchases

Seniors and Adults have lower purchase frequency

This information can guide marketing and targeting strategies.

**Dashboard Filters**

The dashboard includes interactive filters that allow users to explore the data by:

Subscription Status

Gender

Product Category

Shipping Type

Shipping options available:

2-Day Shipping

Express

Free Shipping

Next Day Air

Standard

Store Pickup

These filters enable dynamic exploration of customer behavior.

**Project Workflow**
1. Data Loading

The dataset was imported into Python using Pandas to inspect the structure, columns, and data types.

2. Data Cleaning

Data preprocessing included:

Handling missing values

Removing duplicate records

Correcting data types

Standardizing column names

3. SQL Analysis

The cleaned dataset was analyzed using SQL queries to extract insights such as:

Top selling categories

Customer purchase trends

Revenue by category

Sales distribution across demographics

4. Dashboard Development

The dataset was imported into Power BI where visualizations were created to build the interactive dashboard.

**Key Insights**

Important findings from the analysis include:

Clothing is the top-performing category in both revenue and sales.

Young Adults are the most active buyers.

73% of customers are not subscribed, indicating an opportunity for subscription growth strategies.

The average purchase amount is $59.76 per transaction.

The average review rating is 3.75, indicating moderate customer satisfaction.

**Project Structure**
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
**Conclusion**

This project demonstrates how Python, SQL, and Power BI can be used to transform raw customer data into actionable insights. The interactive dashboard helps businesses understand customer behavior, sales patterns, and revenue drivers, enabling data-driven decision making.
