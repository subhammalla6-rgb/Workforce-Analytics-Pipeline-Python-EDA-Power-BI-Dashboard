#  Employee Data: Cleaning & Exploratory Analysis

## Project Objective
This project focuses on transforming a "messy" administrative dataset into a clean, actionable format for analysis. The goal was to identify key workforce trends while navigating common real-world data issues like missing values and extreme outliers.

## 🛠️ Data Cleaning Process
Before analysis, I performed several critical cleaning steps to ensure the accuracy of the insights:
- **Outlier Removal:** Identified that the 'Salary' column contained phone numbers (values over $10 Billion). I filtered the dataset to include only realistic salaries ($10k - $300k).
- **Handling Missing Data:** Filled missing 'Age' entries using the median value to maintain dataset size without biasing the mean.
- **Feature Engineering:** Split the combined `Department_Region` column into two separate attributes for better granularity.
- **Standardization:** Unfied the casing for categorical columns (Status, Performance) and standardized date formats.

## Key Insights
1. **Salary Distribution:** Most employees earn between $50,000 and $80,000, which was only visible after removing the multi-billion dollar outliers.
2. **Age vs. Salary Correlation:** My analysis (using jittered scatter plots) shows a **flat trend line**, indicating that age is not a primary driver of salary in this specific organization.
3. **Departmental Spending:** Identified which departments carry the highest average payroll through sorted bar visualizations.

## Repository Contents
- `project_EDA_emp_dataset.ipynb`: The full Python code and visualizations.
- `Messy_Employee_dataset.csv`: The original raw data.
- `Cleaned_Employee_Data.csv`: The final processed dataset ready for reporting.
