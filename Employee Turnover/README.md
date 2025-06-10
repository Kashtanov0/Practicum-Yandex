# Employee Turnover and Satisfaction Analysis

This project analyzes employee turnover and satisfaction for the company "Careful Work" using machine learning algorithms.

## Dataset

The dataset includes:
- Employee features: department, job level, workload, years at company, promotion history, labor contract violations, supervisor evaluation, salary.
- Target variables: 
  - `job_satisfaction_rate` (continuous, regression task)
  - `quit` (binary, classification task)

There are separate training and test sets for both tasks.

## Project Goals

- Predict employee satisfaction level based on available features.
- Predict whether an employee will leave the company.
- Interpret model results and provide actionable business recommendations.

## Main Steps

1. Data loading and preprocessing (handling missing values, duplicates)
2. Exploratory data analysis (EDA)
3. Feature engineering and encoding
4. Model selection and hyperparameter tuning (RandomizedSearchCV)
5. Model evaluation (SMAPE for regression, ROC-AUC for classification)
6. Model interpretation (feature importances, SHAP values)
7. Business recommendations

## Libraries Used

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- phik
- shap

---
