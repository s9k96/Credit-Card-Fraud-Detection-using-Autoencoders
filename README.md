# Credit-Card-Fraud-Detection-using-Autoencoders
Given features of credit card transactions, formulating an anomaly detection problem to classify transactions as fraudulent  or not. 

## Dataset: 
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Features given:
- Time: Number of seconds elapsed between this transaction and the first transaction in the dataset
- V1-V28: Result of a PCA Dimensionality reduction to protect user identities and sensitive features(v1-v28)
- Amount: Transaction amount
- Class: 1 for fraudulent transactions, 0 otherwise
