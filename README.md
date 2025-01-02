# Exploratory Data Analysis (EDA) on Bank Transaction Dataset

## Project Overview
This repository contains the exploratory data analysis (EDA) performed on a bank transaction dataset. The analysis aims to understand the dataset's structure and provide insights into the transaction data without delving into modeling or fraud detection efforts.

## Dataset Information
The dataset used for this analysis is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection/data). It includes various features related to bank transactions, such as transaction amounts, timestamps, and customer information.

## Key Features
- **Transaction ID**: Unique identifier for each transaction.
- **Transaction Amount**: The monetary value of the transaction.
- **Transaction Type**: Indicates whether the transaction is a debit or credit.
- **Location**: The geographical location where the transaction took place.
- **Timestamp**: The date and time when the transaction occurred.
- **Customer ID**: Unique identifier for each customer.

## Objectives
The primary objectives of this EDA are:

- To understand the distribution of transaction amounts and types.
- To analyze transaction patterns across different locations.
- To visualize trends and anomalies in the transaction data.

## Methodology
- **Data Loading**: The dataset is loaded into a Pandas DataFrame for analysis.
- **Data Cleaning**: Initial data cleaning steps are performed to handle missing values and data types.
- **Descriptive Statistics**: Summary statistics are generated to understand the basic characteristics of the dataset.
- **Visualizations**: Various plots (histograms, box plots, scatter plots) are created to visualize the data and identify patterns.
- **Correlation Analysis**: Correlation matrices are used to explore relationships between numerical features.

## Results
The EDA results include:

- Insights into transaction patterns and customer behavior.
- Analysis of temporal transaction trends and geographic distribution.
- Visualizations of user activity and transaction characteristics.

## Key Findings

1. **Active Age Group**:
   - Customers aged 18-30 frequently make transactions, with the majority being students.

2. **Transaction Value**:
   - The dataset reveals a high number of low-value transactions, with very few high-value transactions.

3. **Debit vs. Credit Transactions**:
    - The total usage for debit transactions is significantly higher than credit transactions.

4. **Weekend Activity**:
   - There are no transactions recorded on Saturdays and Sundays.
