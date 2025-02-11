# Employee Churn Prediction

## Overview  
Recently, my friend, a Data Analyst at a tech company with six years of experience, quit her job. I was intrigued by the reason behind her decision. Hence, the goal of this project was to analyze a dataset to identify patterns in employee churn, with the aim of predicting employee resignations.  

## Project Content  
- **Data Processing**  
- **Exploratory Data Analysis** of employee demographics, performance, and job satisfaction  
- **Development of Machine Learning Models** to predict employee churn  

## Data Processing  
- **Data Collection:** The dataset was sourced from Kaggle, stored in SQL Workbench. 
 
  ![alt text](<Screenshot 2025-02-11 at 13.18.56.png>)

 The dataset was processed using Python libraries such as Pandas and NumPy.

- **Data Cleaning:** Minimal cleaning was required due to the synthetic nature of the data.  

## Exploratory Data Analysis  
- Insights and visualizations were created using Tableau.  
The interactive dashboard consists of visualizations of employee demografics such as gender, age, education and overall performance and job satisfaction scores.

![alt text](<Screenshot 2025-02-11 at 13.06.38.png>)

## Machine Learning Models to Predict Employee Churn  
- Various models were tested, including **Logistic Regression, Random Forest, Decision Tree,** and **XGBoost**.  
- **Extreme Gradient Boosting (XGBoost)** was selected as the final model.  
- **Handling Class Imbalance:** Techniques like **SMOTE resampling** and **hyperparameter tuning** were applied.  
- **Model Performance:** Due to limited correlations in the data, the best **ROC-AUC score** achieved was **0.522**, indicating the need for more relevant features.  

## Conclusion  
This project highlights that synthetic datasets may lack the depth of real-world patterns. Incorporating additional features, such as workload indicators or external data on market trends, could improve predictive performance.  

---

📌 **Technologies Used:**  
- Python (Pandas, NumPy, Scikit-Learn)  
- SQL Workbench  
- Tableau  
- Machine Learning (Logistic Regression, Decision Tree, Random Forest, XGBoost)  

📌 **Dataset:** [Kaggle (Synthetic Data)](https://www.kaggle.com/datasets/mexwell/employee-performance-and-productivity-data)  

🚀 **Future Improvements:**  
- Collect real-world data for better model performance  
- Include additional features such as workload indicators, salary trends, or market conditions  
- Experiment with deep learning models for enhanced accuracy  

