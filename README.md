# Yandex Projects Repository

This repository contains a collection of data science and machine learning projects completed as part of the Yandex curriculum. Each project is organized in its own folder and includes a description, datasets, and analysis notebooks.

## Repository Structure


Yandex/
├── Employee Turnover/
│   ├── Employee Turnover.ipynb
│   ├── train.csv
│   ├── test.csv
│   ├── requirements.txt
│   └── README.md
│
├── Farm Milk Yield/
│   ├── Farm Milk Yield.ipynb
│   ├── ferma_main.csv
│   ├── ferma_dad.csv
│   ├── cow_buy.csv
│   ├── requirements.txt
│   └── README.md
│
├── Game Sales/
│   ├── Game Sales.ipynb
│   ├── games.csv
│   ├── requirements.txt
│   └── README.md
│
├── Industrial Arc Furnace Final/
│   ├── Industrial Arc Furnace Final.ipynb
│   ├── electrodes.csv
│   ├── bulk.csv
│   ├── gas.csv
│   ├── temperature.csv
│   ├── wire.csv
│   ├── timings.csv
│   ├── requirements.txt
│   └── README.md
│
├── Oil well location/
│   ├── Oil well location.ipynb
│   ├── geo_data_0.csv
│   ├── geo_data_1.csv
│   ├── geo_data_2.csv
│   ├── requirements.txt
│   └── README.md
│
├── Online Store Personalization/
│   ├── Online Store Personalization.ipynb
│   ├── market_file.csv
│   ├── market_money.csv
│   ├── market_time.csv
│   ├── money.csv
│   ├── requirements.txt
│   └── README.md
│
├── Sentiment Analysis/
│   ├── Sentiment Analysis.ipynb
│   ├── toxic_comments.csv
│   ├── requirements.txt
│   └── README.md
│
├── Statistical Analysis/
│   ├── Statistical Analysis.ipynb
│   ├── users_go.csv
│   ├── rides_go.csv
│   ├── subscriptions_go.csv
│   ├── requirements.txt
│   └── README.md
│
├── Taxi Price Forecasting/
│   ├── Taxi Price Forecasting.ipynb
│   ├── taxi_train.csv
│   ├── taxi_test.csv
│   ├── requirements.txt
│   └── README.md
│
├── Car Price Evaluation/
│   ├── Car Price Evaluation.ipynb
│   ├── car_train.csv
│   ├── car_test.csv
│   ├── requirements.txt
│   └── README.md
│
├── Exploratory Data Analysis/
│   ├── Exploratory Data Analysis.ipynb
│   ├── data.csv
│   ├── requirements.txt
│   └── README.md
│

## Projects Overview

### Employee Turnover

- **Description:**  
    Machine learning analysis of employee satisfaction and turnover for the company "Careful Work". The project includes regression (predicting satisfaction level) and classification (predicting employee quit) tasks, model interpretation, and business recommendations.
- **Datasets:**  
    Employee features , with separate training and test sets for both tasks.
- **Main Steps:**  
    Data preprocessing, EDA, feature engineering, model selection (RandomizedSearchCV), evaluation (SMAPE, ROC-AUC), SHAP interpretation, recommendations.
- **Libraries:**  
    pandas, numpy, seaborn, matplotlib, scikit-learn, phik, shap

---

### Farm Milk Yield

- **Description:**  
    Analysis and selection of dairy cows for a farm using linear machine learning models. The goal is to help a farmer choose cows for purchase based on milk yield and taste.
- **Datasets:**  
    - ferma_main.csv: Current herd data (yield, feed, breed, pasture, milk composition, taste, age)
    - ferma_dad.csv: Father's name for each cow
    - cow_buy.csv: Data on cows considered for purchase
- **Main Steps:**  
    Data cleaning, EDA, correlation analysis, feature engineering, linear regression for yield, logistic regression for taste, model comparison, recommendations.
- **Libraries:**  
    pandas, numpy, seaborn, matplotlib, scikit-learn, phik, scipy

---

### Game Sales

- **Description:**  
    Analysis of video game sales from an online store to identify patterns for game success, based on sales, ratings, platform, genre, and region.
- **Dataset:**  
    Game title, platform, release year, genre, regional sales, critic/user scores, ESRB rating.
- **Main Steps:**  
    Data preprocessing, EDA, sales trend analysis, hypothesis testing, conclusions.
- **Libraries:**  
    pandas, numpy, matplotlib, seaborn, missingno, scipy

---

### Industrial Arc Furnace Final

- **Description:**  
    Predicting final alloy temperature in an industrial arc furnace using production data from seven datasets (electrodes, bulk, gas, temperature, wire, and timings).
- **Datasets:**  
    Multiple CSVs with process parameters; all files use `key` as batch identifier.
- **Main Steps:**  
    Data cleaning, EDA, feature engineering, merging, anomaly removal, model selection (GradientBoosting, DecisionTree, ElasticNet, XGBoost), SHAP analysis, recommendations.
- **Libraries:**  
    pandas, numpy, scikit-learn, xgboost, pyod, seaborn, matplotlib, missingno, shap

---

### Oil well location

- **Description:**  
    Selection of the most profitable oil well region using machine learning and statistical analysis. The project uses data from three regions (oil quality and reserves).
- **Datasets:**  
    geo_data_0.csv, geo_data_1.csv, geo_data_2.csv (features and target for each region)
- **Main Steps:**  
    Data loading, EDA, correlation analysis, linear regression, profit calculation with bootstrap, risk assessment.
- **Libraries:**  
    pandas, numpy, seaborn, matplotlib, scikit-learn, phik, scipy

---

### Online Store Personalization

- **Description:**  
    Predicting decrease in customer activity and personalizing offers for an online store using machine learning.
- **Datasets:**  
    - market_file.csv: Customer behavior and preferences
    - market_money.csv: Customer spending
    - market_time.csv: Time spent on site
    - money.csv: Store profit per customer
- **Main Steps:**  
    Data cleaning, merging, EDA, feature engineering, model selection (Logistic Regression, SVC, KNN, Decision Tree), ROC-AUC evaluation, SHAP analysis, segmentation, recommendations.
- **Libraries:**  
    pandas, numpy, seaborn, matplotlib, scikit-learn, phik, shap

---

### Sentiment Analysis

- **Description:**  
    Sentiment analysis for the Wikishop online store using BERT to detect toxic comments. The goal is to flag toxic comments for moderation.
- **Dataset:**  
    toxic_comments.csv (text, toxic label)
- **Main Steps:**  
    Data preprocessing, EDA (word frequency, word clouds), tokenization, BERT model training (transformers), evaluation (F1, accuracy).
- **Libraries:**  
    pandas, numpy, seaborn, matplotlib, nltk, wordcloud, scikit-learn, torch, transformers, datasets

---

### Statistical Analysis

- **Description:**  
    Statistical analysis of GoFast scooter rental data for marketing optimization.
- **Datasets:**  
    - users_go.csv: User info
    - rides_go.csv: Ride data
    - subscriptions_go.csv: Subscription details
- **Main Steps:**  
    Data cleaning, EDA, merging, revenue calculation, hypothesis testing, probability modeling for marketing.
- **Libraries:**  
    pandas, numpy, matplotlib, scipy

---

### Taxi Price Forecasting

- **Description:**  
    Predicting taxi ride prices using regression models based on trip features. The project aims to improve price accuracy for a taxi service.
- **Datasets:**  
    taxi_train.csv, taxi_test.csv (trip features and prices)
- **Main Steps:**  
    Data preprocessing, EDA, feature engineering, model selection (Linear Regression, Random Forest, Gradient Boosting), evaluation (RMSE), recommendations.
- **Libraries:**  
    pandas, numpy, scikit-learn, seaborn, matplotlib

---

### Car Price Evaluation

- **Description:**  
    Predicting used car prices using machine learning models. The project involves analyzing car features and market data to estimate prices.
- **Datasets:**  
    car_train.csv, car_test.csv (car features and prices)
- **Main Steps:**  
    Data cleaning, EDA, feature engineering, model selection (Linear Regression, Random Forest, Gradient Boosting), evaluation (RMSE), recommendations.
- **Libraries:**  
    pandas, numpy, scikit-learn, seaborn, matplotlib

---

### Exploratory Data Analysis

- **Description:**  
    Exploratory data analysis (EDA) on a provided dataset to uncover patterns, trends, and insights.
- **Dataset:**  
    data.csv (various features)
- **Main Steps:**  
    Data loading, cleaning, visualization, summary statistics, correlation analysis, reporting findings.
- **Libraries:**  
    pandas, numpy, matplotlib, seaborn


Each project folder contains its own README.md file with detailed instructions, dataset descriptions, and analysis workflow.
