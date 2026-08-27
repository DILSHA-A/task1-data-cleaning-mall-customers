# Task 1: Data Cleaning and Preprocessing
## Objective
Clean and prepare the Mall Customer Segmentation dataset (from Kaggle) by
handling missing values, duplicates, and inconsistent formatting.
## Tools Used
Google Sheets
## Dataset
Mall_Customers.csv — 200 rows, 5 columns (CustomerID, Gender, Age,
Annual Income, Spending Score)
## Steps Performed
1. Checked for missing values using COUNTA across all columns — none found.
2. Checked for duplicate rows using Remove Duplicates — none found,
all 200 rows unique.
3. Renamed column headers to lowercase, no spaces: customerid, gender,
age, annual_income, spending_score.
4. Verified Gender column for consistency (Male/Female only) using
COUNTIF — confirmed 200/200 valid entries, no typos.
5. Confirmed correct data types — age, annual_income, and
spending_score formatted as numbers.
## Result
A fully cleaned dataset with no missing values, no duplicates,
standardized headers, and consistent formatting — ready for analysis.
