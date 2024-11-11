This Customer Churn Prediction project is a machine learning model to predict customer churn in the IT industry. The goal is to understand key factors influencing customer retention and to accurately predict which customers are likely to churn (leave the service). 

The dataset used in this project is based on IT customer churn data from kaggle, which includes customer demographic and service usage information. Here is a snapshot of the data columns:
gender: Customer's gender (Male/Female)
SeniorCitizen: Whether the customer is a senior citizen (0 = No, 1 = Yes)
Partner: Whether the customer has a partner (Yes/No)
Dependents: Whether the customer has dependents (Yes/No)
tenure: Number of months the customer has been with the company
PhoneService: Whether the customer has phone service (Yes/No)
MultipleLines: Whether the customer has multiple phone lines (Yes/No/No phone service)
InternetService: Type of internet service (DSL/Fiber optic/No)
OnlineSecurity: Whether the customer has online security service (Yes/No)
OnlineBackup: Whether the customer has online backup service (Yes/No)
DeviceProtection: Whether the customer has opted for device protection services (Yes/No).
TechSupport: Whether the customer has subscribed to technical support services (Yes/No).
StreamingTV: Whether the customer has a streaming TV subscription (Yes/No).
StreamingMovies: Whether the customer has a streaming movies subscription (Yes/No).
Contract: Type of contract the customer has chosen (e.g., Month-to-month, One year, Two year).
PaperlessBilling: Whether the customer has opted for paperless billing (Yes/No).
PaymentMethod: Method the customer uses for payment (e.g., Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
MonthlyCharges: Monthly amount charged to the customer.
TotalCharges: Total amount charged to the customer over the entire period of service.
Churn: Target variable indicating whether the customer has churned (Yes/No).

This repository contains data preprocessing, exploratory data analysis, model building, and evaluation steps for customer churn prediction.

Data Preprocessing: Cleaning the dataset by handling missing values, encoding categorical variables, and scaling features.
Exploratory Data Analysis (EDA): Analyzing data to identify patterns and correlations. This includes visualizations of customer tenure, service usage, and correlations with churn.
Feature Engineering: Creating new features and preparing data for modeling.
Model Building: Using classification algorithms such as Logistic Regression, Random Forest, and Gradient Boosting to predict churn.
Model Evaluation: Evaluating model performance using metrics like accuracy, precision, recall, and F1-score to choose the best model.
