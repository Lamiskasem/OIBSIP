# EDA on Retail Sales Data

## Oasis Infobyte Data Analytics Internship — Level 1 Task 1

This project was completed as part of the Oasis Infobyte Data Analytics Internship (OIBSIP).

The objective of this task is to perform Exploratory Data Analysis (EDA) on a retail sales dataset to identify sales trends, customer behaviour patterns, product-category performance, and actionable business insights.

---

## Project Overview

Retail businesses generate large amounts of sales data that can be used to understand customer behaviour and improve business decisions.

In this project, the retail sales dataset was analyzed using Python and several data analysis and visualization libraries.

The analysis focuses on:

- Sales trends over time
- Customer demographics
- Gender distribution
- Product-category sales volume
- Revenue by product category
- Relationships between numerical variables
- Customer spending behaviour
- Business insights and recommendations

---

## Objectives

The main objectives of this project are to:

- Inspect and understand the retail sales dataset.
- Examine the structure, data types, and missing values.
- Calculate descriptive statistics.
- Analyze monthly sales trends.
- Analyze quarterly sales trends.
- Analyze customer age groups.
- Analyze gender distribution.
- Analyze sales volume by product category.
- Analyze revenue by product category.
- Explore correlations between numerical variables.
- Identify additional customer spending insights.
- Develop actionable business recommendations based on the analysis.

---

## Dataset

The dataset used in this project is a retail sales dataset containing 1,000 transactions.

### Dataset Columns

| Column | Description |
|---|---|
| Transaction ID | Unique identifier for each transaction |
| Date | Date of the transaction |
| Customer ID | Unique identifier for each customer |
| Gender | Customer gender |
| Age | Customer age |
| Product Category | Category of the purchased product |
| Quantity | Number of units purchased |
| Price per Unit | Price of one unit |
| Total Amount | Total transaction amount |

The available product categories are:

- Beauty
- Clothing
- Electronics

### Important Dataset Limitation

The dataset contains product categories but does not contain individual product names.

Therefore, product performance in this analysis is evaluated at the **product-category level** using quantity sold and total revenue rather than individual products.

---

## Technologies and Libraries

The project was developed using:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Structure

```text
DataAnalytics-L1-EDARetailSales
│
├── data
│   └── retail_sales_dataset.csv
│
├── images
│   ├── monthly_sales_trend.png
│   ├── quarterly_sales_trend.png
│   ├── customer_age_groups.png
│   ├── gender_distribution.png
│   ├── quantity_by_product_category.png
│   ├── revenue_by_category.png
│   ├── correlation_heatmap.png
│   ├── average_transaction_by_age.png
│   └── revenue_by_gender.png
│
├── notebooks
│   └── retail_sales_eda.ipynb
│
├── README.md
│
└── requirements.txt