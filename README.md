# Credit-Card-Data-Analysis

## Objective
The objective of this analysis is to evaluate customer spending and repayment behavior using credit card transaction data. The study focuses on identifying key insights related to customer demographics, spending habits, repayment trends, and overall profitability. Additionally, it aims to analyze customer spending patterns to enhance marketing campaigns and develop personalized offers for better engagement.

## Data Overview
The dataset consists of three key tables:
1. **Customer Acquisition** – Contains details about customers, including age, credit limit, and assigned card type.
2. **Spending Data** – Records transaction-level spending details by customers.
3. **Repayment Data** – Captures repayment transactions made by customers.

## Key Analysis & Insights
- **Data Cleaning & Preprocessing**
  - Replaced age values less than 18 with the mean age.
  - Capped spend amounts exceeding limits to 50% of the assigned limit.
  - Adjusted repayment amounts exceeding the limit to the limit value.

- **Exploratory Analysis**
  - Count of distinct customers in the dataset.
  - Monthly spending and repayment trends.
  - Profitability calculation as the difference between repayments and spending.
  - Identification of the top 5 product types.
  - Analysis of cities with maximum spending.
  - Age group contributing the most to spending.
  - Top 10 customers in terms of repayment amounts.
  - City-wise yearly spend analysis on products, supported with graphical representation.

## Technologies Used
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Data Processing:** Cleaning, transformation, and aggregations
- **Visualizations:** Bar charts, line graphs, and other statistical plots

## Conclusion
This analysis provides a comprehensive view of customer spending patterns, repayment behaviors, and key profitability metrics. The insights can help in strategic decision-making for customer engagement, credit policies, and marketing strategies.

## Usage
To run this analysis, execute the Jupyter Notebook file and ensure the required datasets are available in the specified file paths.

---
**Author:** Agasteen
**Date:** March 2025

