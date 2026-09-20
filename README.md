# E-commerce Customer Analysis

## Project Overview

This project explores customer data to understand customer demographics,
geographic distribution, customer segments, and customer acquisition costs.

The project uses exploratory data analysis (EDA) and data visualization
to identify patterns within the customer dataset.

## Objectives

- Understand the structure and quality of the customer dataset
- Analyze customer distribution across countries and regions
- Examine customer segments
- Analyze customer age distribution
- Explore customer acquisition costs
- Identify the states with the highest customer counts
- Visualize important patterns in the dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

- Dataset dimensions and data quality checks
- Missing-value and duplicate checks
- Descriptive statistics
- Customer distribution by country
- Average acquisition cost by country
- Average customer age by country
- Customer age distribution
- Age vs. acquisition cost analysis
- Regional customer distribution
- Customer segment analysis
- Top 10 states by customer count

## Key Findings

- USA contributes highest number of cusotomers about 59.70% of total customers.
- Average acquisition cost is relatively similar accross countries (~ 41-42)
- Southern region constributes highest number of customer (~ 32.0%).
- Consumer segment has highest number of customers which is 13638 while business segment has the lowest which       is 2519.
- Pennsylvania has the highest customer concentration among individual states in the dataset, with approximately 1632 customers

## Project Structure

```text
ecommerce-customer-analysis/
│
├── data/
│   └── customer_master.csv
│
├── notebooks/
│   └── ecommerce_analysis.ipynb
│
├── .gitignore
├── requirements.txt
└── README.md
```