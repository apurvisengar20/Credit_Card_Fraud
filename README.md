Credit Card Fraud Detection

This project analyzes credit card transactions to detect patterns, summarize spending behavior, and provide insights for financial decision-making. 

-> Steps

Data Cleaning 
Exploratory Data Analysis 
Model Building (Logistic Regression, Random Forest)
Model Evaluation (Accuracy, Confusion Matrix, Classification Report)

->  Features

- Data visualization of transaction amounts.
- Distribution analysis of transaction frequency.
- Basic statistics and insights from credit card transactions.
- Easy-to-understand Python implementation.

-> Results

Logistic Regression Accuracy: 1%
Random Forest Accuracy: 1%

-> How to Run

Clone the repository
Open the Jupyter notebook
Run all cells

-> About the DataSet

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
