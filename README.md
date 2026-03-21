# Fraud Detection with Machine Learning

This project was developed as part of the Aygaz Machine Learning Bootcamp.

## Problem
Online payment systems are vulnerable to fraudulent transactions, making accurate detection critical for financial security.

## Objective
To compare supervised and unsupervised machine learning approaches for fraud detection and identify the most effective method.

## Dataset
- Online Payments Fraud Detection Dataset (Kaggle)
- Contains transaction data including amount, balances, transaction type, and fraud labels

## Methods

### Supervised Learning
- Logistic Regression
- Used labeled data to classify transactions as fraud or non-fraud

### Unsupervised Learning
- K-Means Clustering
- Identified hidden patterns and anomalies in transaction data

## Results

### Logistic Regression
- Accuracy: 99.9%
- Strong performance in detecting non-fraud cases
- Lower recall for fraud class due to class imbalance

### K-Means Clustering
- Successfully grouped similar transaction patterns
- Less effective for direct fraud classification

## Key Insights
- Supervised models perform better in fraud detection when labeled data is available
- Class imbalance significantly impacts fraud detection performance
- Unsupervised learning is useful for anomaly detection but not sufficient alone

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Outcome
Developed a data-driven approach to fraud detection and evaluated model performance to determine the most suitable algorithm.

## Project Link
🔗 https://www.kaggle.com/code/aygulse/aygaz-makine-renmesi-bootcamp-proje-kamp
