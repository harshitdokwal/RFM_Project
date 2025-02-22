# E-Commerce Customer Segmentation Using RFM Clustering
![RFM](clustering_image.png)
## Overview
This project demonstrates how to analyze and segment customers using the Recency, Frequency, and Monetary (RFM) model, followed by clustering using K-Means. It enables businesses to identify different customer segments and develop targeted strategies for each group.

## Dataset Description
The dataset includes transactional data with the following key columns:

1. CustomerID: Unique identifier for each customer.
2. Date of Purchase: Date of the transaction.
3. Price: Total value of the transaction.
4. InvoiceNo: Unique identifier for each transaction.
5. Quantity: Number of items purchased.

## Preprocessing Steps
1. Handle missing values and duplicates.
2. Format date columns appropriately.
3. Aggregate data to calculate RFM metrics.

## Methodology
1. Data Preprocessing:
Cleaned and transformed the dataset to ensure consistency and accuracy.
2. RFM Calculation:
Calculated Recency, Frequency, and Monetary values for each customer.
3. Clustering:
Standardized the RFM metrics and applied K-Means clustering to segment customers.

## Insights and Visualization:
Visualized the clusters to interpret customer behavior and identify actionable insights.

## Key Insights
1. Loyal Customers: Customers with frequent purchases and high monetary value.
2. At-Risk Customers: Customers who haven't made purchases recently.
3. Big Spenders: Customers with high monetary value irrespective of frequency.

## Requirements
Python 
Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn

# Conclusion
This project provides a framework for customer segmentation using RFM analysis and clustering. Businesses can utilize the insights to improve customer retention, target high-value customers, and re-engage inactive ones.
