## ELECTRONIC DEVICES SALES, ORDER & CUSTOMER ENGAGEMENT ANALYTICS DASHBOARD

![Electronics-Shop](https://github.com/user-attachments/assets/93f26270-f75d-433a-bb97-bf536635937c)

## TASK

Analyze the company's sales performance, order and delivery operations and customer engagement using provided datasets. The goal is to uncover insights that improve sales strategies, customer engagement, and operational efficiency.

## ABOUT THE DATASET 

This project leverages four key datasets:

- Order Data - Captures key transaction details such as order ID, customer ID, product ID, quantity, order date, and delivery status. 
- Product Data - Provides detailed information on each product, including its category, unit price, and unit cost.
- Payment Data - Records payment transactions tied to orders, including payment ID and payment date.
- Customer Data - Contains demographic and contact information such as customer ID, name, gender, location, and date of birth.

## PROBLEM STATEMENT

The business needed a clear and interactive way to:

- Monitor and evaluate electronic device sales performance across different product categories and time periods.
- Track order fulfillment and delivery status to improve logistics and customer satisfaction.
- Understand customer engagement patterns, retention rates, and purchasing behavior through segmentation.

## Power BI Concepts Applied

To bring this project to life, I used a combination of core Power BI tools concepts that made the dashboard not just functional, but insightful:

- Power Query for Data Prep: Cleaned and shaped four different datasets—Orders, Customers, Products, and Payments to ensure consistency and remove clutter that could affect analysis.
- Data Modeling: Set up solid relationships between all tables so that everything connects smoothly.
- DAX (Data Analysis Expressions): Built calculated columns and measures to track key metrics like total sales, total profit, customer types, and average revenue per customer.
- Custom Date Table: Created a date table using DAX for proper time-based analysis (monthly trends, yearly breakdowns, and everything in between).
- Calculation Table: Collected all important KPIs in a single place for better organization and easier maintenance.
- Slicers & Filters: Added interactivity with slicers for product category, delivery status, gender, and country—so users can explore what matters to them.
- Visual Design: Used a mix of charts—line graphs, clustered columns, cards, and pies to tell clear stories without overwhelming the viewer.

## Data Modeling

- The data model was designed using a star schema structure for simplicity and performance. At the center is the Order table, which connects to related tables: Customer, Product, Payment, and a generated Date table.
- Relationships were established using key fields like Customer ID, Order ID, and Product ID to ensure the visuals interact smoothly across the dashboard.

## Dashboards

The dashboard is divided into three key views: [Interact with the dashboard here](https://app.powerbi.com/view?r=eyJrIjoiZjM5MjM2YzItMjM1Yy00MDYyLWIzOTktMDg2ODBjMDBmNTI2IiwidCI6Ijc3ZGJjZTk5LTYwNTQtNGFiYS04MjUwLTE5YzBlZmI0MzE4ZCJ9)

1. Sales Overview Dashboard
   
- Objective:  Visualize the overall performance of the business in terms of total sales, profit, order volume, and quantity over time.
- KPIs: Total Sales (₦1.23bn), Total Profit (₦174M), Total Quantity (1702 units), Total Orders (850 orders)
- Trends: Sales Month-on-Month Change
- key Insights: Sales by Product Category (Laptop, 56%), Top 5 Selling Products (Acer Nitro 5), Top 5 Locations by Sales (Sapele), Impact of Unit Price on Total Sales

2. Order and Delivery Tracking Dashboard

- Objective: Monitor order fulfillment efficiency and delivery patterns.
- KPIs: Total Delivered Orders (296), Shipped Orders (275), Avg. Days to Payment (2 days)
- Trends: Monthly Order Status Trend, Monthly Payment & Delivery Status
- Key Insights: Order Lifecycle Table, Order Status Progress by City

3. Customer Insights & Engagement Dashboard
   
- Objective: Analyze customer behavior, segmentation, and revenue contribution.
- KPIs: Total Customers (200), Active Customers (184), Customer Retention Rate (80%), Average Revenue Per Customer (₦943K)
- Key Insights: Revenue Contribution by Segment, Customer Engagement Overview Table, Monthly Order by Segment

## Performance Review

The dashboards uncover several meaningful business insights across sales, payment behavior, and customer engagement:
- Sales Performance Year-over-Year (YoY): All major KPIs show a decline compared to the previous year. This signals a potential drop in demand that may require strategic intervention.
- Price-Sales Relationship: There's a clear inverse relationship between unit prices and total sales (lower-priced items tend to drive more purchases). 
- Payment Behavior: On average, customers complete their payments two days after placing an order. This short payment cycle indicates operational efficiency and good customer trust in the payment system.
- Customer Retention: The majority of transactions and revenue come from repeat customers, showing that customer retention is strong. 

## Conclusion & Recommendations

This analysis sheds light on areas the business is doing well and where improvements are needed. While customer retention is strong, overall sales and profit have dropped compared to the previous year. 

To move forward:
- The loyal customer base is a valuable asset and should be nurtured further through loyalty programs or personalized offers.
- Dig deeper into the YoY decline to understand what changed whether it is fewer new customers, product issues, or external factors

![2025](https://github.com/user-attachments/assets/d6bb7441-4847-4107-9a3d-811e60ef47f8)





