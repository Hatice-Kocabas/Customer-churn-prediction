# Bank Customer Churn Prediction

## Overview  
This project aims to analyze and predict customer churn for a bank using a dataset from Kaggle. The dataset contains various customer attributes, such as credit score, geography, age, balance, and more. The goal is to build a model that can classify whether a customer will churn or not.

## Dataset  
**Source:** [Kaggle - Predicting Churn for Bank Customers](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers?select=Churn_Modelling.csv)  

**Columns:**
- `CreditScore`: Customer's credit score  
- `Geography`: Customer's country (France, Spain, Germany)  
- `Gender`: Customer's gender  
- `Age`: Customer's age  
- `Tenure`: Number of years the customer has been with the bank  
- `Balance`: Account balance  
- `NumOfProducts`: Number of products held by the customer  
- `HasCrCard`: Whether the customer has a credit card (0 or 1)  
- `IsActiveMember`: Whether the customer is an active member (0 or 1)  
- `EstimatedSalary`: Customer's estimated salary  
- `Exited`: Whether the customer has churned (0 = No, 1 = Yes)  

## Data Preprocessing  
- Removed unnecessary columns (`RowNumber`, `CustomerId`, `Surname`)  
- Checked for missing values (None found)  
- Encoded categorical variables (`Geography` and `Gender`) using one-hot encoding  

## Exploratory Data Analysis (EDA)  
- Displayed dataset statistics and distribution  
- Used `seaborn` countplot to visualize the distribution of churned and non-churned customers  

## Libraries Used  
- `numpy`  
- `pandas`  
- `matplotlib`  
- `seaborn`  

## How to Run  
1. Download the dataset from Kaggle and place it in your working directory  
2. Run the preprocessing script to clean and prepare the data  
3. Perform exploratory data analysis using the provided visualizations  

## Future Work  
- Feature engineering to improve model performance  
- Implement machine learning models for churn prediction  
- Hyperparameter tuning for better accuracy  

## Acknowledgments  
- Kaggle for providing the dataset  
- Open-source Python libraries used for data analysis  

---
