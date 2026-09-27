# Employee Salary & Performance Analysis

End-to-end Exploratory Data Analysis (EDA) project on a synthetic employee dataset.

## Dataset
- 1,005 rows, 11 columns
- Synthetic data created for demonstrating EDA workflow
- Includes intentional data quality issues (duplicates, missing values, outliers)

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

## Analysis Covered
- Data inspection & quality checks
- Univariate analysis (Salary, Performance)
- Outlier detection (IQR method)
- Department-wise analysis
- Bivariate analysis (Salary vs Performance)
- Correlation matrix

## Key Findings
- Salary is right-skewed (8 outliers)
- HR highest paid, Operations lowest
- Salary ↔ Performance correlation = 0.20 (weak)
- Data leakage: Experience ↔ Joining_Year = -0.98

## Recommendations
- Use median for salary reporting
- Investigate Finance dept pay inequality
- Review data quality before production

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/employee_salary_performance_analysis.ipynb
