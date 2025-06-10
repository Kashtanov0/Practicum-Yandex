# Sentiment Analysis with BERT for Wikishop

## Project Description

This project focuses on building a sentiment analysis model for the "Wikishop" online store, where users can edit and comment on product descriptions. The main goal is to automatically detect toxic comments and flag them for moderation.

**Dataset:**  
The dataset (`toxic_comments.csv`) contains user comments with two columns:
- `text`: the comment text
- `toxic`: the target label (1 for toxic, 0 for non-toxic)

**Main Steps and Goals:**
- Data loading and preprocessing, including handling class imbalance and text cleaning
- Exploratory data analysis with word frequency and word cloud visualizations
- Tokenization and preparation of data for model training
- Model training using BERT (transformers.BertForSequenceClassification) with PyTorch
- Evaluation of model performance using F1-score and accuracy metrics

**Libraries Used:**
- pandas, numpy, seaborn, matplotlib
- nltk, wordcloud
- scikit-learn
- torch, transformers, datasets

## Conclusions

- The BERT-based model achieved an F1-score of approximately 0.78-0.81 on the test set, surpassing the project goal of 0.75.
- Exploratory analysis revealed a significant class imbalance and common vocabulary related to the store's theme.
- The model successfully distinguishes between toxic and non-toxic comments and can be used to assist moderation in community-driven platforms.
