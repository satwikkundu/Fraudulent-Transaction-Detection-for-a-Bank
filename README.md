FraudGuard_ML_Sentinel

Overview
This project develops a machine learning model to detect fraudulent bank transactions using a logistic regression pipeline. It processes a dataset of 1M+ records, addressing class imbalance (0.11% fraud) with scaling, encoding, and class weighting. Achieves 93.48% accuracy and 0.97 recall for fraud detection.
Features

Data Preprocessing: Standardizes numerical features and encodes transaction types.
Model: Logistic regression with balanced class weights.
Evaluation: Includes accuracy, precision, recall, F1-score, and confusion matrix.

Dataset:

Columns: step, type, amount, oldbalanceOrg, newbalanceOrig, nameDest, oldbalanceDest, newbalanceDest, isFraud.

Requirements

Python 3.x
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Results

Accuracy: 93.48%
Fraud Recall: 0.97

