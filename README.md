# Bank_Churn_Prediction_using_ANN
Developed to help banks retain valuable customers, this project implements an Artificial Neural Network (ANN) that predicts bank customer churn with 84% accuracy.
Objective:

To construct a robust neural network-based classifier that accurately predicts bank customer churn (the likelihood of a customer leaving) within the next 6 months. This model will assist bank management in identifying valuable customers at risk of departing and prioritizing efforts to retain them.

# Context:

Customer churn is a pressing challenge for service providers like banks, leading to lost revenue and increased acquisition costs. Identifying key factors influencing churn enables targeted interventions and service improvements that enhance customer satisfaction and loyalty.

# Data Description:

Source: Public Kaggle dataset ("[Bank Customer Churn Modeling](https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling?resource=download)")
Size: 10,000 samples
Features: 14 attributes including CustomerId, CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, and Exited (target variable)

# Feature	Description

CustomerId	Unique identifier
Surname	Customer's surname
Credit Score	Numerical representation of creditworthiness
Geography	Customer's country
Gender	Customer's gender
Age	Customer's age
Tenure	Duration of the customer-bank relationship
Balance	Current account balance
NumOfProducts	Number of bank products the customer holds
HasCrCard	Whether the customer has a bank credit card
IsActiveMember	Subjective measure of customer engagement
EstimatedSalary	Customer's estimated annual income
Exited	Churn label (1 = churned, 0 = retained)

# Model Results:

Training Loss: 0.3197
Training Accuracy: 86.04%
Model Evaluation Loss: 0.3694
Model Evaluation Accuracy: 83.99%

# Key Observations:

The initial neural network model demonstrates promising performance, with high training accuracy (above 86%) and moderate test accuracy (84%).
