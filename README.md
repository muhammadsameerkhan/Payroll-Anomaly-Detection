# Payroll-Anomaly-Detection
Isolation Forest Model to detect outliers from the Payroll HR data

# Dataset used
Employees' Payroll in Los Angeles (Public Data: https://www.kaggle.com/datasets/dsfelix/employees-payroll-in-los-angeles/versions/3)

# Key Findings
1. Individual KPIs have their own outliers which represents the skewness of the variables.
2. Trained Isolation Forest Model with contamination (0.1) shows same trend of variables correlation in outliers dataset as it was in raw dataset.
3. The contamination (0.5) shows some strong correlations in different variables but with similar trend.
4. This unchanged correlation represents the outliers in the datasets are not the random errors instead they are meaningful data points.
5. These outliers are might based on some job titles which require more analysis.

# Highly Correlated KPIs
1. Regular Pay vs City Retirement Contribution
2. Regular Pay vs Benefit Pay
