# E-Commerce Sales Analysis: Exploratory Data Analysis & Business Insights

## Project Overview

This project explores an e-commerce transaction dataset using Python to understand product revenue, country-level sales performance, customer contribution, and monthly revenue trends.

The notebook combines exploratory data analysis, feature engineering, data visualization, and business question analysis to demonstrate practical data analytics skills.

## Objectives

- Understand dataset structure, data types, and descriptive statistics.
- Check missing values and duplicate records.
- Explore numerical distributions and correlations.
- Create datetime features and calculate transaction revenue.
- Identify top-performing products and countries by revenue.
- Examine monthly revenue trends.
- Identify customers with the highest total revenue.
- Compare revenue across countries and months.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Dataset

The notebook loads a local CSV file named `ecommerce.csv`.

The displayed dataset contains 4,870 rows and 8 original columns:

- `InvoiceNo`
- `StockCode`
- `Description`
- `Quantity`
- `InvoiceDate`
- `UnitPrice`
- `CustomerID`
- `Country`

The notebook creates additional features, including year, month, month number, day name, quarter, and revenue.

## Business Questions

1. Which products generate the highest total revenue?
2. Which countries contribute the most revenue?
3. How does revenue change over time?
4. Which customers contribute the highest total revenue?
5. How does revenue vary by country and month?

## Analytical Workflow

1. Data loading and preview.
2. Dataset structure and quality checks.
3. Descriptive statistics and numerical visualization.
4. Datetime feature engineering.
5. Revenue calculation using quantity and unit price.
6. Product, country, and customer revenue analysis.
7. Monthly trend analysis and country-month comparison.
8. Business interpretation and recommendations.

## Key Considerations

- Monthly trends should use chronological ordering.
- Transaction counts should be distinguished from row counts.
- Negative quantities and prices should be investigated before being removed.
- Revenue calculations should account for the business meaning of returns and cancellations.
- Business recommendations should be supported by calculated results.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload or place `ecommerce.csv` in the expected working directory.
3. Run the notebook cells in order.

## Learning Outcomes

This project demonstrates practical skills in exploratory data analysis, feature engineering, data visualization, aggregation, and translating transaction data into business insights.
