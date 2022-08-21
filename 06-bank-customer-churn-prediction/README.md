# Forecasting the Bank's customer churn

Area: Machine Learning, Classification Model

Goal of the project: Using the bank's data, identify a customer who can leave the bank.

Project description: Customers started to leave the bank. Every month. A little, but noticeably. Bank marketers thought that it was cheaper to keep the existing customers than to attract new ones.
It is necessary to predict whether the customer will leave the bank in the near future or not. Historical data on customer behavior and termination of contracts with the bank were provided.

Data: Data on the behavior of customers who have already switched to these tariffs.

Data description:

Features:
* *RowNumber* - row index in data
* *CustomerId* - unique customer identifier
* *Surname* - surname
* *CreditScore* - credit rating
* *Geography* - country of residence
* *Gender* - gender
* *Age* - age
* *Tenure* - how many years a person has been a bank client
* *Balance* - account balance
* *NumOfProducts* - the number of bank products used by the client
* *HasCrCard* - the presence of a credit card
* *IsActiveMember* - client activity
* *EstimatedSalary* - estimated salary

Target feature:
* *Exited* - the fact that the client left

Libraries: Python, Pandas, Matplotlib, Scikit-learn

Tags: classification, tuning of hyperparameters, choice of ML model
