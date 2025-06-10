# Online Store Personalization

This project aims to select the most accurate machine learning model to predict a decrease in customer activity in an online store. Based on the model and data analysis, customer segments are identified and personalized offers are formulated to improve customer engagement.

## Dataset Overview

The project uses four datasets:
- **market_file.csv**: Customer behavior, communications, and product preferences.
- **market_money.csv**: Customer spending per period.
- **market_time.csv**: Time spent by customers on the site per period.
- **money.csv**: Store profit from each customer.

## Main Steps and Goals

- Data loading and preprocessing (fixing typos, formatting, merging tables)
- Exploratory data analysis (EDA) and visualization
- Feature engineering and encoding
- Model selection using pipelines and hyperparameter tuning (RandomizedSearchCV)
- Evaluation using ROC-AUC metric
- Feature importance analysis (SHAP)
- Customer segmentation and business recommendations

## Used Libraries

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- phik
- shap

The project demonstrates a full machine learning workflow from data preparation to actionable business insights.
