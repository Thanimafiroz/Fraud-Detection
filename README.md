# Fraud-Detection

## Background information on the dataset and its relevance

Credit card fraud is a wide-ranging term for theft and fraud committed using or involving a payment card, such as a credit card or debitcard, as a fraudulent source of funds in a transaction. The purpose may be to obtain goods without paying or to obtain unauthorized funds from an account. Credit card fraud is also an adjunct to identity theft. Although incidences of credit card fraud are limited to about 0.1% of all card transactions, they have resulted in huge financial losses as the fraudulent transactions have been large value transactions. It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Over view of dataset

The dataset contains transactions made by credit cards in September 2013 by European cardholders, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, in which the proportion of the fraud transactions is only 0.172%. It contains 30 independent variables including 2 numerical features, ‘Time’ and ‘Amount’, and 28 principal components obtained with PCA. Feature 'Time' is a timestamp, which means the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, and this feature can be used for example-dependent cost-sensitive learning. Feature class is the response variable and it takes value 1 for fraud transactions and 0 for normal ones. Finally, 29 independent variables and one dependent variable are included in our research.

Data: https://www.kaggle.com/datasets/mlgulb/creditcardfrau
