# CLTV-prediction-using-Regression-models
Customer Lifetime Value (CLTV) is a critical metric used to assess the total revenue a business can expect from a customer over the entire duration of their relationship. It helps businesses understand how much a customer is worth and enables better decision-making in areas like marketing, customer retention, and sales strategy.
The basic formula for calculating CLTV is:

## CLTV = ( Average Order Value × Purchase Frequency / Churn Rate ) × Profit Margin
  Where:
  •	Average Order Value (AOV): The average amount spent per order by a customer.
  •	Purchase Frequency (F): The average number of times a customer makes a purchase within a given time period.
  •	Churn Rate (C): The rate at which customers stop making purchases, or "churn" out of the customer base.
  •	Profit Margin (P): The profit margin on the total purchases made by the customer.

## Benefits of CLTV:
  •	Optimized Customer Acquisition: By understanding CLTV, businesses can identify which customer segments are the most profitable, allowing for targeted acquisition strategies.
  •	Improved Customer Retention: Helps focus efforts on retaining high-value customers.
  •	Increased Business Value: Knowing how much a customer is worth over time helps businesses make data-driven decisions to enhance profitability.

This repository demonstrates how to predict Customer Lifetime Value (CLTV) for retail customers using two machine learning models: Linear Regression and Gradient Boosting. The goal is to predict the future value that customers will bring to a business based on their historical transaction data.

## Key Features:
  •	Dataset: The dataset includes transaction details from a retail company and includes columns such as InvoiceNo, StockCode, Description, Quantity, UnitPrice, CustomerID, and Country.
  
  •	Data Preprocessing: The data was cleaned by handling missing values, duplicates, and outliers. Feature engineering was performed to calculate useful features like total purchase value, frequency of purchases, and recency.
  
  •	Modeling:
    o	Linear Regression: Used as a baseline model to predict CLTV based on the derived features.
    o	Gradient Boosting: Applied with hyperparameter tuning to optimize the model for better prediction accuracy.
    
  •	Performance Metrics:
    o	R-Squared (Test Data): 0.94 for both Linear Regression and Gradient Boosting.
    o	Mean Squared Error: Evaluated for model performance on test data.
    
  •	Visualization: Actual vs predicted CLTV values are visualized for both models to assess model accuracy.

  
## Results:
  •	Best Parameters for Gradient Boosting:
          o	learning_rate: 0.1
          o	max_depth: 7
          o	n_estimators: 200
          o	subsample: 0.9
  •	The Gradient Boosting model achieved an R-Squared value of 0.94 on the test dataset, demonstrating a high level of prediction accuracy.
  
## Libraries Used:
    •	sklearn for machine learning algorithms.
    •	pandas for data manipulation.
    •	matplotlib and seaborn for visualizations.
    •	numpy for numerical operations.
    
## Future Improvements:
  •	Incorporating additional machine learning models like XGBoost and Random Forest for comparison.
  •	Exploring more sophisticated feature engineering techniques for improved model performance.


