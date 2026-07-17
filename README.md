# Sales Forecasting using Machine Learning

## Overview
This project predicts future sales using machine learning techniques on the Store Sales Time Series Forecasting dataset.

## Dataset
- Source: Kaggle
- Rows: ~479,000
- Features:
  - date
  - store_nbr
  - family
  - sales (Target)
  - onpromotion

## Project Workflow
1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. One-Hot Encoding
6. Model Training
   - Random Forest
   - XGBoost
7. Model Evaluation
8. Prediction
9. Model Saving

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- XGBoost
- Joblib

## Evaluation Metrics
- MAE
- RMSE
- R² Score

## Files
- Sales_Forecasting.ipynb
- sales_forecasting_model.pkl
- processed_sales_data.csv
- sales_predictions.csv

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Deep Learning models
- Forecasting future unseen dates