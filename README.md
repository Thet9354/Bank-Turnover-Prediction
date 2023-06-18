# Bank Turnover Prediction

This project aims to predict customer turnover (churn) in a bank using machine learning techniques. The dataset used for training and evaluation contains various customer attributes and their corresponding turnover status.


## Project Overview

In this project, we leverage machine learning algorithms to predict whether a customer will churn or not. The main steps involved in the project are as follows:

1. Data preprocessing and exploration: This step involves loading and analyzing the dataset, handling missing values, performing feature engineering, and gaining insights into the data.

2. Model training and evaluation: Various machine learning models are trained using the preprocessed data. The models are evaluated using appropriate performance metrics, such as accuracy, precision, recall, and F1-score.

3. Model selection and optimization: The best-performing model is selected based on the evaluation results. Hyperparameter tuning and other optimization techniques may be applied to improve model performance further.

4. Deployment and usage: The selected model is deployed for real-world predictions. A simple user interface or API can be created to make predictions on new data.

## Dataset

The dataset used for this project contains information about bank customers, including demographic attributes, transaction history, and turnover status. It is located in the `data` directory and provided in CSV format. The columns in the dataset include:

- `CustomerId`: Unique identifier for each customer
- `Surname`: Surname of the customer
- `CreditScore`: Credit score of the customer
- `Geography`: Customer's country of residence
- `Gender`: Gender of the customer (Male or Female)
- `Age`: Age of the customer
- `Tenure`: Number of years the customer has been with the bank
- `Balance`: Bank account balance of the customer
- `NumOfProducts`: Number of bank products the customer has
- `HasExited`: Customer turnover status (0 - not churned, 1 - churned)


