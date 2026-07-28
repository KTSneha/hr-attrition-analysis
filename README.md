# HR Employee Attrition Analysis

Analyzing employee attrition drivers using Excel and Power BI to uncover which factors most strongly predict turnover.

## Overview

This project analyzes IBM's HR Employee Attrition dataset to identify the key factors driving employee turnover, helping HR teams target retention efforts where they matter most.

## Dataset

- 1,470 employee records with 35 attributes including department, overtime status, age, income, tenure, and attrition status.
- Source: [IBM HR Analytics Employee Attrition Dataset (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Tools Used

Excel (data cleaning, pivot tables) · Power BI (dashboard, DAX measures)

## Process

- Cleaned and validated 1,470 records in Excel — removed constant columns, verified data types, checked for duplicates and blanks
- Created calculated fields: Age Group, Tenure Bucket, Income Band, Attrition Flag
- Built exploratory pivot tables to identify attrition patterns across departments, overtime status, and age groups
- Designed an interactive Power BI dashboard with DAX measures

## Key Insights

- Employees who work overtime attrite at ~3x the rate of those who don't (30.5% vs 10.4%)
- Employees under 30 leave at nearly double the company average (27.9% vs 16.1%)
- Sales has the highest departmental attrition (20.6%), R&D the lowest (13.8%)

## Dashboard Preview

![Dashboard Preview](screenshots/dashboard_preview.png)

## Files

- `data/Hr_cleaned.xlsx` — cleaned dataset with calculated columns
- `dashboard/HR_Attrition_Dashboard.pbix` — Power BI dashboard file

## What I Learned

This project strengthened my data cleaning workflow in Excel (validating data types, handling calculated fields) and gave me hands-on practice writing DAX measures in Power BI to translate raw HR data into clear, actionable business insights.
