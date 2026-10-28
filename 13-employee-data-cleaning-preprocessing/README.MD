# Employee Data Cleaning & Preprocessing with Python

## Project Overview

This notebook demonstrates a data cleaning and preprocessing workflow for an employee performance dataset using Python. The project covers exploratory data analysis, duplicate detection, outlier handling, missing value imputation, and categorical encoding.

## Objectives

- Understand dataset structure and data types.
- Explore descriptive statistics and variable distributions.
- Detect and handle duplicate records.
- Identify numerical outliers using the Interquartile Range (IQR) method.
- Apply Winsorization to selected numerical variables.
- Handle missing numerical and categorical values.
- Encode categorical variables for further analysis.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Dataset Overview

The dataset contains 1,248 rows and 14 columns before cleaning. It includes employee-related attributes such as salary, training hours, satisfaction score, department, work mode, education level, and performance category.

The original dataset is loaded from `employee_performance_assignment_dirty.csv`.

## Workflow

1. **Exploratory Data Analysis:** Inspect dataset shape, data types, descriptive statistics, missing values, and numerical distributions.
2. **Duplicate Handling:** Identify and remove duplicate rows.
3. **Outlier Analysis:** Calculate Q1, Q3, IQR, and outlier boundaries for numerical columns.
4. **Outlier Handling:** Apply Winsorization to appropriate numerical variables.
5. **Missing Value Imputation:** Use median imputation for selected numerical variables and mode imputation for categorical variables.
6. **Categorical Encoding:** Apply label encoding and one-hot encoding to selected categorical columns.
7. **Validation:** Check data quality after preprocessing and compare the dataset before and after transformations.

## Key Considerations

- Outlier treatment should be applied only to appropriate numerical variables.
- Missing value strategies should reflect the variable type and business context.
- Encoded category values should not automatically be interpreted as numerical rankings.
- Analytical insights should be supported by actual notebook outputs.

## Learning Outcomes

This project demonstrates practical data preparation techniques for analytics workflows, including data quality assessment, missing value handling, outlier treatment, and categorical encoding.
