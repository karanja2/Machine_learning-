# machine_learning

### Bank Customer Churn Analysis
## Overview
This repository contains a Jupyter Notebook that performs exploratory data analysis (EDA) and logistic regression on a bank customer churn dataset. The goal of this analysis is to build a model that predicts whether a customer is likely to churn (i.e., leave the bank) based on their demographic and banking information.

## Requirements
In order to run the Jupyter Notebook, you will need to have the following software installed:

- Python 3.x
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sklearn
- Data

The bank customer churn data is provided in a CSV file called "bank_customer_churn.csv". 
The data contains information on customer demographics and banking habits, as well as a binary label indicating whether or not the customer churned. 
The data includes the following columns:

- RowNumber: Unique identifier for each customer
- CustomerId: Customer's unique identification number
- Surname: Customer's surname
- CreditScore: Customer's credit score
- Geography: Customer's country of residence (e.g., France, Germany, Spain)
- Gender: Customer's gender (Male or Female)
- Age: Customer's age (in years)
- Tenure: Number of years the customer has been with the bank
- Balance: Customer's average account balance (in euros)
- NumOfProducts: Number of bank products the customer has
- HasCrCard: Whether the customer has a credit card (yes or no)
- IsActiveMember: Whether the customer is an active member (yes or no)
- EstimatedSalary: Customer's estimated salary (in euros)
- Exited: Binary label indicating whether the customer churned (yes or no)
### Exploratory Data Analysis (EDA)
The Jupyter Notebook starts by performing exploratory data analysis on the bank customer churn data. This includes:

- Importing the data into a Pandas DataFrame
- Cleaning the data and handling missing values
- Generating summary statistics for the data
- Visualizing the distribution of the data using histograms, box plots, and scatter plots
- Examining the relationship between the independent variables and the target variable (i.e., whether or not the customer churned)

### Logistic Regression

After completing the EDA, the Jupyter Notebook trains a logistic regression model on the data. This includes:

- Encoding categorical variables as numerical variables
- Splitting the data into training and testing sets
- Training the logistic regression model on the training data
- Evaluating the model on the test data using accuracy, precision, recall, and F1 score metrics
- Plotting the confusion matrix to visualize the model's performance
- Interpreting the coefficients of the logistic regression model to understand the impact of each independent variable on the likelihood of churn.


