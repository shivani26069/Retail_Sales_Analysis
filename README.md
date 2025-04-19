
🛒 Retail Sales Analysis with Python
This project performs a comprehensive data analysis on an E-Commerce retail dataset using Python. The goal is to extract actionable insights related to customer behavior, product performance, geographical sales trends, and overall business health.

🎯 Purpose: This project was done solely to learn Data Analysis with Python and practice using its core libraries such as Pandas, Matplotlib, and Seaborn in a real-world business dataset.

📁 Dataset Overview
The dataset contains over 500,000 transactions between 2009–2011 for a UK-based online retailer. It includes:

InvoiceNo: Unique identifier for each transaction

StockCode: Unique product ID

Description: Product description

Quantity: Number of units sold

InvoiceDate: Date and time of transaction

UnitPrice: Product price per unit

CustomerID: Unique identifier for each customer

Country: Customer's country

📌 Objectives & Insights
✅ Data Cleaning
Removed cancelled orders (negative quantity with zero price)

Filtered out transactions with missing customer or product data

Dropped irrelevant codes (e.g., adjustments, samples, test entries)

Converted data types and created TotalPrice = Quantity * Price

📦 Product & Inventory Insights
Identified top-performing products by sales volume and revenue

Highlighted underperforming and returned products

Found which products are bought frequently by the same customers

Set the foundation for bundle analysis

🤝 Customer Behavior
🧮 RFM (Recency, Frequency, Monetary) Analysis
Calculated RFM scores to understand customer loyalty

Created segments such as:

Champions

Loyal Customers

At Risk

Potential Loyalists

🏆 Highest Value Customer
Identified customer(s) with the highest total spending

🌍 Geographical Sales Distribution
Visualized total revenue and quantity sold per country

Found top markets like the United Kingdom, Netherlands, Germany, etc.

📊 Visualizations
Used Matplotlib and Seaborn to create:

Bar plots of top-selling countries by revenue

Product sales distribution

RFM segment count chart

🔍 Summary of Key Insights
By conducting this end-to-end analysis, we discovered that:

Most revenue is generated from the United Kingdom, followed by a few key European countries.

A handful of products contribute disproportionately to the total sales.

Certain customers consistently generate high revenue and can be categorized as Champions or Loyal.

Returned and faulty items were identified, which can help improve operations and customer satisfaction.

The RFM segmentation provides a powerful way to personalize marketing based on customer value and activity.

This project not only provided these insights but also served as a learning experience in using Python for data analysis, combining multiple libraries and techniques used by professional data analysts.

🧰 Tech Stack
Python

Pandas – Data cleaning & manipulation

Matplotlib – Data visualization

Seaborn – Advanced charts & plots

Jupyter Notebook – Interactive coding environment
