HR Analysis: Prediction of Employee Churn
By Aru Akbayeva

Data Source: https://www.kaggle.com/datasets/mexwell/employee-performance-and-productivity-data

Overview

This project analyzes a synthetic dataset to identify patterns in employee churn, with the aim of predicting employee resignation. It involves data processing, exploratory analysis, and the development of machine learning models. The dataset is sourced from Kaggle and reflects various aspects of employee demographics, performance, and job satisfaction.

Project Goals

Understand the workforce demographics and resignation trends.
Build predictive models to identify employees likely to resign.
Explore potential insights to aid in reducing employee attrition.

Methodology

Data Collection: Data is sourced from Kaggle, stored in SQL Workbench, and processed using Python libraries.
Data Cleaning: Minimal cleaning due to preprocessed data.
Exploratory Data Analysis (EDA): Insights and visualization are done in Tableau.

Model Building:

Various models were tested: Logistic Regression, Random Forest, Decision Tree, and XGBoost.
Extreme Gradient Boosting was selected as the final model.
Handling Class Imbalance: Techniques like SMOTE resampling and hyperparameter tuning were applied.

Dataset Summary

Rows: 100,000
Columns: 19 key features including demographics, job-related factors, and the Resigned label.
Metadata:
Employee_ID: Unique identifier.
Department: Employee’s department.
Gender: Male/Female/Other.
Age: Age range from 22 to 60.
Job_Title: Employee's role.
Years_At_Company: Duration of employment.
Performance_Score: 1-5 performance rating.
Monthly_Salary: Monthly income in USD.
Employee_Satisfaction_Score: 1.0-5.0 satisfaction rating.
Resigned: Target variable, indicating if the employee has resigned.

Model Performance
Due to limited correlations in the data, the best ROC-AUC score achieved was 0.522, suggesting the need for more relevant features.

Conclusion
This project reveals that synthetic datasets may lack the depth of real-world patterns. Adding features like workload indicators or external data on market trends could enhance predictive performance.
