# Vehicle_Price_Forecasting
A Python-based car price prediction model developed as part of our class assignment on vehicle price forecasting. The model is built from scratch using linear regression without relying on the scikit-learn library.

# Project Overview
This project implements a complete pipeline for predicting car prices, including data preprocessing, feature engineering, and a custom linear regression model. During preprocessing, we standardize feature columns to ensure accurate predictions. The pipeline also includes outlier removal, log transformation of the target variable, and polynomial feature creation to enhance model performance.

# Usage
To run the model, execute CarPrice_Prediction.ipynb in Jupyter Notebook. The provided datasets are:
- train.csv: Training dataset
- test.csv or test1.csv: Test datasets for evaluation
Ensure all required libraries (numpy, pandas, matplotlib, seaborn) are installed.

# Model Performance
1. Training Set:
- R² Score: 0.8316
- Mean Squared Error (MSE): 484,148,310,947
- Mean Absolute Error (MAE): 327,265
2. Test Set:
- R² Score: 0.7929
- Mean Squared Error (MSE): 1,212,357,758,687
- Mean Absolute Error (MAE): 400,717

# Analysis
The model achieves a strong R² score of 0.8316 on the training set and 0.7929 on the test set, indicating good predictive performance. The higher MSE and MAE on the test set suggest potential overfitting or differences in data distribution between the training and test sets. Features like car age, mileage, engine size, and categorical variables (e.g., make, fuel type) significantly influence predictions.

# Summary
This project successfully implements a linear regression model for car price prediction, incorporating data preprocessing, feature engineering, and custom gradient descent with L2 regularization. The model demonstrates robust performance but could benefit from further tuning or additional features to improve generalization on unseen data.

# Conclusion
The developed model provides a reliable framework for predicting car prices based on key vehicle attributes. Future improvements could include experimenting with other algorithms, handling large datasets with Git LFS, or incorporating more features to enhance accuracy.
