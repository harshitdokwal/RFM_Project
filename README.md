# E-Commerce Customer Segmentation Using RFM Clustering
## Overview
This project demonstrates how to analyze and segment customers using the Recency, Frequency, and Monetary (RFM) model, followed by clustering using K-Means. It enables businesses to identify different customer segments and develop targeted strategies for each group.

## Dataset Description
The dataset includes transactional data with the following key columns:

CustomerID: Unique identifier for each customer.
Date of Purchase: Date of the transaction.
Price: Total value of the transaction.
InvoiceNo: Unique identifier for each transaction.
Quantity: Number of items purchased.

## Preprocessing Steps
Handle missing values and duplicates.
Format date columns appropriately.
Aggregate data to calculate RFM metrics.

## Methodology
Data Preprocessing:
Cleaned and transformed the dataset to ensure consistency and accuracy.
RFM Calculation:
Calculated Recency, Frequency, and Monetary values for each customer.
Clustering:
Standardized the RFM metrics and applied K-Means clustering to segment customers.

## Insights and Visualization:
Visualized the clusters to interpret customer behavior and identify actionable insights.

## Key Insights
Loyal Customers: Customers with frequent purchases and high monetary value.
At-Risk Customers: Customers who haven't made purchases recently.
Big Spenders: Customers with high monetary value irrespective of frequency.

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
