# Dairy Cow Selection Project

This project analyzes and selects dairy cows for a farm using linear machine learning models. The main goal is to help a farmer choose cows for purchase based on their milk yield and milk taste, using data-driven approaches.

## Dataset Overview

The project uses three datasets:
- **ferma_main.csv**: Contains current herd data, including yield, feed characteristics, breed, pasture type, milk composition, taste, and age.
- **ferma_dad.csv**: Contains the name of each cow's father.
- **cow_buy.csv**: Contains data on cows the farmer is considering for purchase, with similar features.

## Main Steps and Goals

- Data loading and preprocessing: cleaning, renaming columns, handling missing values and duplicates.
- Exploratory data analysis: distribution analysis, outlier detection, and visualization.
- Correlation analysis: identifying relationships between features and the target.
- Feature engineering: creating new features and transforming existing ones.
- Model training: building and evaluating linear regression models for yield prediction and logistic regression for milk taste classification.
- Model comparison and selection: evaluating model performance using metrics like R2, MAE, RMSE, and precision.
- Recommendations: identifying cows suitable for purchase based on model predictions and confidence intervals.

## Libraries Used

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn (sklearn)
- phik
- scipy

The project demonstrates the process of building and evaluating machine learning models for agricultural decision-making, with a focus on practical recommendations for the farmer.
