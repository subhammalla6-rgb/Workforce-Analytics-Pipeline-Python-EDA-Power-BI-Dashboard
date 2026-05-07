# Workforce Analytics Pipeline: Python EDA & Power BI Dashboard

Project Objective
This project demonstrates an end-to-end data workflow—from cleaning a highly "messy" administrative dataset using Python to creating a professional executive dashboard in Power BI.

##  Phase 1: Data Cleaning (Python)
Using a Google Colab environment, I performed critical cleaning steps on 1,000+ employee records:
- [cite_start]**Outlier Removal:** Identified and filtered "salary" entries that were actually phone numbers (values > $10B)[cite: 52].
- **Missing Data:** Handled 20% missing 'Age' data using median imputation.
- **Feature Engineering:** Decoupled `Department_Region` into separate columns for granular analysis.

##  Phase 2: Interactive Dashboard (Power BI)
I built a high-level summary dashboard for HR managers, focusing on:
- **Headcount Trends:** Visualizing the 2023 hiring surge.
- **Regional Distribution:** A treemap of the workforce across key states.
- **Payroll Insights:** Average salary breakdown by department, filtered to exclude outliers ($10k - $300k).

## 📂 Repository Contents
- `project_EDA_emp_dataset.ipynb`: Python cleaning logic and deep-dive jitter plots.
- `emp_insight_dashboard.pbix`: The interactive Power BI file.
- `Cleaned_Employee_Data.csv`: The final dataset used for the dashboard.
