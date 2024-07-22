# Customer Churn Prediction for TELCO Company

This project aims to predict customer churn for a TELCO company using machine learning techniques. Given the customer data with several features, the goal is to create a model that can predict whether a customer will churn (leave the company) or not. This is part of the company's customer retention program.

## Project Overview

- **Objective**: Predict customer churn to help retain customers.
- **Dataset**: The dataset consists of 7043 records with 21 features, including customer ID and churn status.
- **Techniques Used**: Data preprocessing, feature selection, machine learning model development.

## Data Preprocessing

1. **Loading Data**: The dataset is loaded using pandas.
2. **Data Cleaning**: Handling missing values and converting data types.
   - `TotalCharges` converted to numeric.
   - `SeniorCitizen` converted to boolean.
3. **Encoding Categorical Features**: Label encoding for categorical features.
4. **Feature Scaling**: MinMaxScaler is used for scaling features.

## Model Development

1. **Feature Selection**: SelectKBest with chi-square is used for feature selection.
2. **Model Training**: Logistic Regression is used for model training.
3. **Evaluation**: The model is evaluated using accuracy score and classification report.

## Dependencies

- pandas
- numpy
- matplotlib
- scikit-learn

## How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook to see the step-by-step implementation and results.

