# 📊 Telecom Customer Churn Analysis (EDA)

## Objective

In this project, I performed an Exploratory Data Analysis (EDA) on the Telecom Customer Churn dataset to identify the key factors influencing customer churn.

The project focuses on understanding customer demographics, service subscriptions, contract types, payment methods, and tenure to uncover business insights that can help improve customer retention.

The sections below explain the dataset, technologies used, data preparation process, exploratory analysis, and key findings.

## Table of Contents

- [Dataset Used](#dataset-used)
- [Technologies](#technologies)
- [Data Inspection](#data-inspection)
- [Data Cleaning & Transformation](#data-cleaning--transformation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Insights](#key-insights)

## Dataset Used

The dataset contains customer demographics, account information, subscribed services, billing details, and customer churn status.

The objective is to analyze customer behavior and identify factors contributing to churn.

Dataset Source:
- IBM Telecom Customer Churn Dataset (Kaggle)

## Technologies

The following technologies were used in this project:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Inspection

The initial inspection included:

- Understanding dataset structure using `info()`
- Checking data types
- Identifying missing values
- Generating descriptive statistics
- Detecting duplicate customer IDs

## Data Cleaning & Transformation

The following preprocessing steps were performed before analysis:

- Converted `TotalCharges` from object to float
- Replaced blank values in `TotalCharges`
- Checked missing values
- Removed duplicate customer IDs
- Converted `SeniorCitizen` values from **0/1** into **Yes/No** for better visualization

## Exploratory Data Analysis

Several visualizations were created to understand customer churn.

The analysis includes:

- Customer Churn Distribution
- Gender vs Churn
- Senior Citizen Analysis
- Tenure Distribution
- Contract Type Analysis
- Internet Service Analysis
- Additional Services Analysis
- Payment Method Analysis

## Key Insights

The analysis revealed several important business insights:

- Around **26.5%** of customers have churned.
- Customers with **Month-to-Month contracts** show the highest churn rate.
- Customers with **Fiber Optic Internet** are more likely to churn.
- Customers without **Online Security**, **Online Backup**, **Device Protection**, and **Tech Support** have significantly higher churn.
- Customers using **Electronic Check** as the payment method have the highest churn.
- Customers with longer tenure are much less likely to churn.

---
