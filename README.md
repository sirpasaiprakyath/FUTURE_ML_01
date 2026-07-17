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
  
## Model Performance

Two machine learning models were trained and compared.

| Model | MAE | RMSE | R² Score |
|------|------:|------:|------:|
| Random Forest | 47.39 | 269.81 | 0.8027 |
| XGBoost | 52.70 | 254.40 | 0.8246 |

### Best Model
Based on the evaluation metrics, **XGBoost** achieved the best overall performance with:

- **MAE:** 52.70
- **RMSE:** 254.40
- **R² Score:** 0.8246

The XGBoost model was selected as the final forecasting model because it achieved the highest R² score and the lowest RMSE among the evaluated models.

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
