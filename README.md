# Credit_Card_Fraud_Detection


## Dataset Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

## Problem Statement:

To identify whether a new credit card transaction is fraudulent or not based on a model trained by past data.


## Attribute Information:

Time: Contains the seconds elapsed between each transaction and the first transaction in the dataset.

V1-V28: Principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.

Amount: Transaction Amount, this feature can be used for example-dependant cost-sensitive learning.

Class: Response variable and it takes value- 1 in case of FRAUD and 0 otherwise.

# Workflow:
#### 1) Data Collection
#### 2) Data Visualization (EDA)
#### 3) Data Preprocessing
  **Data Cleaning:** Handle missing values, Remove duplicates.

  **Handling Outliers:** Identify and handle outliers in the data.

  **Correlation Analysis:** Check for correlations between features.
#### 4) Splitting the data into dependent and independent variables
#### 5) Train_Test_split
#### 6) Model Training
-- Logistic Regression
-- Random Forest
-- KNN Classifier
#### 8) Building predictive model / Model Testing
