# Customer Churn Prediction

This project involves predicting customer churn for a telecom company using machine learning models. The goal is to identify customers who are likely to leave the service, enabling the company to take proactive measures to retain them.

## Project Overview

This project compares the performance of two machine learning models: Decision Tree and Naive Bayes. We evaluate these models using several metrics, including Accuracy, Precision, Recall, F1-Score, and ROC AUC, to determine which model performs best for predicting customer churn.

## Data

The dataset consists of approximately 5,000 data points related to customer behavior. The features include various customer attributes like `CustomerID`, `Age`, `Gender`, `ContractType`, `MonthlyCharges`, `TotalCharges`, and others. Additionally, derived features like `average_monthly_charges` and `customer_lifetime_value` are created. We also introduce missing values and outliers to simulate real-world scenarios.

## Models Used

### 1. Decision Tree
A Decision Tree is a non-parametric supervised learning method used for classification. It works by splitting the data into subsets based on the most important features.

- **Best Decision Tree Performance:**
  - **Accuracy:** 0.70
  - **Precision:** 0.68
  - **Recall:** 0.72
  - **F1-Score:** 0.70
  - **ROC AUC:** 0.70

### 2. Naive Bayes
Naive Bayes is a probabilistic classifier based on applying Bayes' theorem with strong (naive) independence assumptions between the features.

- **Best Naive Bayes Performance:**
  - **Accuracy:** 0.56
  - **Precision:** 0.56
  - **Recall:** 0.49
  - **F1-Score:** 0.52
  - **ROC AUC:** 0.60

### Model Comparison
Based on the evaluation metrics, the Decision Tree model outperforms the Naive Bayes model in terms of accuracy, precision, recall, F1-score, and ROC AUC.

## Requirements

The project requires the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`

To install the required libraries, run:

```bash
pip install -r requirements.txt

