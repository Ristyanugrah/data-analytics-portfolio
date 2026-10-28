# Exploratory Data Analysis of Superstore Sales

## Overview

This project explores the Sample Superstore dataset using Python. It covers data preparation, data quality checks, descriptive statistics, feature engineering, and exploratory data analysis to investigate sales, profitability, product quantities, customer segments, and shipping performance.

## Objectives

- Inspect dataset structure and data types.
- Convert date columns into appropriate datetime formats.
- Identify and remove duplicate records.
- Summarize numerical and categorical variables.
- Engineer features related to shipping duration and per-unit sales and profit.
- Explore distributions, outliers, and relationships between variables.
- Analyze correlations among numerical features.

## Dataset

The analysis uses the Sample Superstore dataset from Kaggle, downloaded with KaggleHub.

- Dataset source: `vivek468/superstore-dataset-final`
- Initial dataset size: 9,994 rows and 21 columns.
- Main variables include order dates, shipping modes, customer segments, regions, product categories, sales, quantity, discount, and profit.

## Tools and Libraries

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- KaggleHub

## Analysis Workflow

### 1. Data Preparation and Quality Checks
- Load and inspect the dataset.
- Convert order and shipping dates to datetime.
- Remove unnecessary columns.
- Identify and remove duplicate records.
- Check missing values.

### 2. Data Understanding
- Generate descriptive statistics.
- Examine categorical variables.
- Review the distribution of sales and other key metrics.

### 3. Feature Engineering
- Calculate shipping duration in days.
- Encode shipping modes for exploratory comparison.
- Calculate sales and profit per unit.
- Derive an estimated cost per unit from sales and profit.

### 4. Exploratory Data Analysis
- Univariate analysis of distributions and categories.
- Bivariate analysis of shipping duration and shipping mode.
- Product-level profit comparisons.
- Quantity comparisons across product categories.
- Multivariate analysis of discount and profit by segment and category.
- Correlation heatmap of numerical variables.

## Key Skills Demonstrated

- Data cleaning
- Exploratory data analysis (EDA)
- Feature engineering
- Descriptive statistics
- Distribution and outlier analysis
- Data visualization
- Correlation analysis

## Notes

This notebook is intended for learning and portfolio purposes. Correlations and comparisons are exploratory and do not establish causation. Engineered features and categorical encodings should be interpreted according to their definitions and limitations.
