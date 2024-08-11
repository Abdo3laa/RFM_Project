# RFM Analysis of Online Retail Dataset

## Overview
This project involves conducting an RFM (Recency, Frequency, Monetary) analysis on an online retail dataset to identify and segment customers based on their purchasing behavior.

## Data Collection
- **Dataset Details:** Utilized a dataset with transaction information including InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

## Data Preprocessing
- **Handling Missing Values:** Removed rows with missing CustomerID to ensure data completeness.
- **Data Cleaning:** Eliminated duplicates and inconsistencies to maintain data integrity.
- **TotalPrice Calculation:** Created a `TotalPrice` column to represent the total amount spent in each transaction.

## RFM Calculation
- **Recency:** Measured as the number of days since the customer's last purchase.
- **Frequency:** Counted the number of transactions made by each customer.
- **Monetary:** Calculated the total amount spent by each customer.

## RFM Segmentation
- **Scoring and Ranking:** Customers were ranked and scored based on Recency, Frequency, and Monetary values.
- **Overall RFM Score:** Combined the individual scores to derive an overall RFM score for each customer.
- **Segmentation:** Categorized customers into groups such as Champions, Loyal Customers, Potential Loyalists, Recent Customers, At Risk, and Hibernating.

## Insights and Application
- **Behavioral Insights:** The segmentation provided valuable insights into customer behavior.
- **Targeted Strategies:** Enabled the development of targeted marketing strategies aimed at improving customer retention and maximizing revenue.

This RFM analysis is a vital tool for enhancing customer relationship management and optimizing marketing efforts across different customer segments.
