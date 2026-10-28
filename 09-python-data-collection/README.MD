# Data Collection with Python: Excel, Google Sheets & APIs

## Overview
This notebook explores different techniques for collecting and importing data into Python from various sources. It demonstrates how to work with Excel files, Google Sheets, REST APIs, and synthetic datasets.

## Learning Objectives
- Import data from Excel files using pandas.
- Read specific worksheets and multiple worksheets.
- Load data from Google Sheets in CSV format.
- Retrieve JSON data from REST APIs using Python requests.
- Generate synthetic datasets using Faker and NumPy.
- Define dataset purposes, columns, and data types.

## Topics Covered

### 1. Excel Data Import
- Reading Excel files with `pandas.read_excel()`.
- Accessing a specific worksheet using `sheet_name`.
- Importing all worksheets into a dictionary of DataFrames.

### 2. Google Sheets Integration
- Exporting Google Sheets data as CSV.
- Reading spreadsheet data using `pandas.read_csv()`.

### 3. REST API Data Collection
- Sending HTTP GET requests using `requests`.
- Checking HTTP response status codes.
- Extracting fields from JSON responses.

### 4. Synthetic Dataset Generation
- Generating sample names with Faker.
- Creating random student IDs and scores with NumPy.
- Selecting values from predefined subject categories.
- Structuring records as dictionaries and storing them in a list.

### 5. Dataset Design
- Defining the purpose of a dataset.
- Identifying columns and data types.
- Preparing a student score dataset for further analysis.

## Tools and Technologies
- Python
- pandas
- NumPy
- Faker
- requests
- Google Colab

## Key Skills
- Data collection and ingestion
- Excel and spreadsheet integration
- REST API fundamentals
- JSON data extraction
- Synthetic data generation
- Dataset structuring

## Notes
This notebook contains practical examples for learning data collection techniques. File paths and spreadsheet permissions may need to be adjusted before running the notebook in another environment. API availability and external data access may also vary.
