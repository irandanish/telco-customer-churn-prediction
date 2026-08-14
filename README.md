# Telco Customer Churn Prediction

## Project Overview
This project focuses on predicting customer churn using machine learning techniques. The goal is to identify customers who are likely to leave the service so that businesses can take proactive retention actions.

## Dataset
The project uses the Telco Customer Churn dataset containing customer demographics, account information, services used, and churn status.

## Machine Learning Models Used
- Logistic Regression
- XGBoost Classifier

## Model Evaluation
Models were evaluated using:

- ROC-AUC Score
- PR-AUC Score
- Cross-Validation
- Precision, Recall, and F1-score
- Threshold tuning

## Final Model Result

XGBoost was selected as the final model because it achieved better churn detection performance.

Key Results:
- 5-Fold ROC-AUC: 0.8597
- PR-AUC: 0.6601
- Best Threshold: 0.30
- Churn Recall: 75.7%
- Churn F1-score: 0.63

## Project Workflow
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training
5. Model Comparison
6. Threshold Optimization
7. Final Model Selection

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Conclusion
The final XGBoost model provides a strong solution for identifying potential churn customers and can help businesses improve customer retention strategies.
