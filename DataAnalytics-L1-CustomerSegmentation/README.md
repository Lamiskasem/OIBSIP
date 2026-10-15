# Customer Segmentation Analysis

## Oasis Infobyte Data Analytics Internship — Level 1 Task 2

## Project Overview

This project applies customer segmentation to online retail transaction data. Customers are grouped based on purchasing behaviour using RFM (Recency, Frequency, Monetary) features and the K-Means clustering algorithm.

## Objectives

- Load and inspect the retail dataset.
- Clean transaction records.
- Calculate customer-level RFM features.
- Explore descriptive statistics.
- Standardize clustering features.
- Use the Elbow Method to select the number of clusters.
- Apply K-Means clustering.
- Visualize customer segments.
- Profile each cluster.
- Develop targeted marketing recommendations.

## Dataset

The project uses the Online Retail dataset from the UCI Machine Learning Repository.

Dataset page:
https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains transaction information such as invoice number, product, quantity, invoice date, unit price, customer ID, and country.

## RFM Features

- Recency: days since the customer's latest purchase.
- Frequency: number of distinct invoices.
- Monetary: total recorded customer spending.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
DataAnalytics-L1-CustomerSegmentation/
├── data/
│   └── Online Retail.xlsx
├── images/
│   ├── rfm_distributions.png
│   ├── elbow_method.png
│   ├── recency_vs_monetary.png
│   ├── frequency_vs_monetary.png
│   └── customers_per_cluster.png
├── notebooks/
│   └── customer_segmentation.ipynb
├── README.md
└── requirements.txt