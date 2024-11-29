## CLTV-prediction-using-Regression-models
This repository demonstrates how to predict Customer Lifetime Value (CLTV) for retail customers using two machine learning models: Linear Regression and Gradient Boosting. The goal is to predict the future value that customers will bring to a business based on their historical transaction data.

# Key Features:
Dataset: The dataset includes transaction details from a retail company and includes columns such as InvoiceNo, StockCode, Description, Quantity, UnitPrice, CustomerID, and Country.
Data Preprocessing: The data was cleaned by handling missing values, duplicates, and outliers. Feature engineering was performed to calculate useful features like total purchase value, frequency of purchases, and recency.

# Modeling:
Linear Regression: Used as a baseline model to predict CLTV based on the derived features.
Gradient Boosting: Applied with hyperparameter tuning to optimize the model for better prediction accuracy.

# Performance Metrics:
R-Squared (Test Data): 0.94 for both Linear Regression and Gradient Boosting.
Mean Squared Error: Evaluated for model performance on test data.

# Visualization: Actual vs predicted CLTV values are visualized for both models to assess model accuracy.
# Results:
Best Parameters for Gradient Boosting:
learning_rate: 0.1
max_depth: 7
n_estimators: 200
subsample: 0.9


The Gradient Boosting model achieved an R-Squared value of 0.94 on the test dataset, demonstrating a high level of prediction accuracy.

# Libraries Used:
sklearn for machine learning algorithms.
pandas for data manipulation.
matplotlib and seaborn for visualizations.
numpy for numerical operations.

# Future Improvements:
Incorporating additional machine learning models like XGBoost and Random Forest for comparison.
Exploring more sophisticated feature engineering techniques for improved model performance.
