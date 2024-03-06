# Credit-Card-Fraud-Detection

## Overview
This project aims to detect fraudulent transactions in credit card data using machine learning techniques. The dataset used in this project is sourced from Kaggle and includes a collection of anonymized credit card transactions labeled as fraudulent or legitimate.

## Motivation
Credit card fraud is a prevalent issue that can lead to significant financial losses for both individuals and financial institutions. By developing effective fraud detection models, we can mitigate the impact of fraudulent activities and enhance security measures in the financial sector.

## Dataset
The dataset was obtained from a Kaggle share, where it was found in the Kaggle repository. It contains transactions made by European cardholders with credit cards in September 2013. This set reveals transactions over two days, with a total of 284,807 transactions, among which 492 frauds were identified. The proportion of frauds with respect to total transactions is minimal, representing only 0.172%. For confidentiality reasons, the data have been subjected to a PCA transformation. The variables V1 to V28 represent the principal components obtained through PCA, with 'Time' and 'Amount' being the only characteristics that have not been altered. For more details, the repository can be consulted at the following link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Link to dataset: [Kaggle Credit Card Fraud Detection Dataset](https://github.com/JessicaChepe/DL-Deteccion-Credict-Card-Fraud-Autoencoder)

## Approach
In this notebook, we will use the creditcard.csv file, which records past credit card transactions. We will make some EDA and use Isolation Forest and Logistic Regression to distinguish between fraudulent (1) and legitimate/non-fraudulent (0) credit card transactions.

## Conclusion
By using logistic regression, we were able to increase the precision of our fraud transactions.
However, due to the imbalance of information in the dataset regarding what constitutes a signal of a fraudulent transaction, the search for patterns indicating a possible fraudulent transaction is not accurate enough.
Even though the overall accuracy is nearly 100%, the precision of identifying fraud was only 59%. This means that out of all the fraudulent transactions we detected, 59% were false positives. Additionally, our recall index indicates that 56% of the false negatives were actually fraudulent transactions.
This project marks one of my first endeavors in financial data science, and I still have much to learn. Nonetheless, I am satisfied with the results thus far.
My next step is to explore alternative approaches to this problem in order to improve our accuracy.

