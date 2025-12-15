# Pizza-Sales-Analysis-Project-Power-BI-SQL-PostgreSQL-

📌 Project Overview

This project is a Pizza Sales Analysis Report developed using SQL (PostgreSQL) and Microsoft Power BI.
It is a replication study inspired by a publicly available YouTube tutorial, created to strengthen skills in data analysis, KPI computation, and business intelligence visualization.

The analysis converts raw transactional data into actionable insights on sales performance, customer behavior, and product trends.

🛠️ Tools & Technologies

Database: PostgreSQL

Query Language: SQL

Visualization Tool: Microsoft Power BI

📂 Dataset Overview

The dataset is stored in PostgreSQL and contains transactional pizza sales records with the following attributes:

Core Fields

Identifiers: pizza_id, order_id

Product Information: pizza_name, pizza_category, pizza_size, pizza_ingredients

Transaction Details: quantity, unit_price, total_price

Time Dimensions: order_date, order_time

This structure supports detailed analysis of sales trends, product mix, and customer demand.

📊 Key Business Metrics (KPIs)
Metric	Value
Total Revenue	817,860.05
Average Order Value (AOV)	38.31
Total Pizzas Sold	49,574
Total Orders	21,350
Average Pizzas per Order	2.32
📈 Sales Trends
Daily Trends

Peak Days:

Friday – 3,538 orders

Thursday – 3,239 orders

Lowest Demand:

Sunday – 2,624 orders

Monthly Trends

Seasonal fluctuations were identified using SQL time-based aggregations and visualized in Power BI to highlight periods of high and low demand.

💰 Revenue Analysis
Revenue by Category

Classic: 26.91%

Supreme: 25.46%

Chicken: 23.96%

Veggie: 23.68%

Revenue by Size

Large: 45.89%

Medium: 30.49%

Large-sized pizzas account for nearly half of total revenue.

📦 Category Performance (February Example)
Category	Quantity Sold
Classic	1,178
Supreme	964
Veggie	944
Chicken	875
🥇 Product-Level Insights
Top Performing Pizzas

By Revenue

Thai Chicken

Barbecue Chicken

California Chicken

Classic Deluxe

Spicy Italian

By Quantity Sold

Classic Deluxe

Barbecue Chicken

Hawaiian

Pepperoni

Thai Chicken

By Number of Orders

Classic Deluxe

Hawaiian

Pepperoni

Barbecue Chicken

Thai Chicken

Underperforming Pizzas

Low Revenue

Brie Carre

Green Garden

Spinach Supreme

Mediterranean

Spinach Pesto

Low Demand

Brie Carre (less than 500 units and orders)

Mediterranean and spinach-based pizzas (less than 1,000 units/orders)

📌 Strategic Insights & Recommendations

Customer Behavior:
Preference for large pizzas suggests group or family-based purchases.

Sales Timing:
Higher demand on Thursdays and Fridays supports targeted promotions on these days.

Menu Optimization:
Core products perform consistently well, while niche products underperform.

Recommended Actions

Promote combo deals focused on large pizzas

Improve or phase out weak-performing menu items

Increase midweek sales using targeted discounts

📊 Power BI Dashboard Features

The Power BI dashboard includes:

KPI Cards (Revenue, Orders, AOV, Total Pizzas Sold)

Daily, weekly, and monthly trend charts

Category and size contribution pie charts

Top and bottom product bar charts

🎯 Project Outcome

This project demonstrates how PostgreSQL and Power BI can be combined to transform transactional data into meaningful business intelligence.
The insights support data-driven decisions in pricing, promotions, and menu optimization.

📚 Reference

YouTube – Pizza Sales Analysis Project
https://www.youtube.com/watch?v=Vs8c6jMRN0&list=PPSV&t=8998s
