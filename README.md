# E-Commerce Customer Yearly Amount Prediction (Linear Regression Supervised Learning)

## Project Overview
This repository contains a machine learning project focused on predicting the **Yearly Amount Spent** by e-commerce customers. It uses a **Linear Regression** model (Supervised Learning) to analyze customer engagement metrics and determine their impact on total spending.

## Dataset
The dataset `EcommerceCustomers.csv` contains details about customers and their activity.
Key columns include:
- `Email`
- `Address`
- `Avatar`
- `AvgSessionLength`: Average duration of an in-store session.
- `TimeonApp`: Time spent on the mobile app (in minutes).
- `TimeonWebsite`: Time spent on the website (in minutes).
- `LengthofMembership`: How many years the customer has been a member.
- `YearlyAmountSpent`: The target variable, representing the total amount spent by the customer in a year.

## Model Features and Target Variable
- **Features (Independent Variables)**: The model uses `AvgSessionLength`, `TimeonApp`, and `LengthofMembership` to make predictions.
- **Target (Dependent Variable)**: `YearlyAmountSpent`.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas (Data manipulation and analysis)
- Scikit-learn (Machine learning model and data splitting)
- Matplotlib (Data visualization)

## Repository Structure
- `EcommerceCustomers.csv`: The dataset used to train and test the model.
- `Ecommerce_customers_Yearly_ammount_prediction_with_linear_regression_model.ipynb`: A Jupyter Notebook containing the code for exploratory data analysis (EDA), data preparation, model training using Scikit-Learn's `LinearRegression`, and result visualization.
- `README.md`: Project description.
