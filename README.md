# ✈️ Flight Price Prediction using Machine Learning

This project predicts the price of airline tickets using historical flight data and multiple Machine Learning regression models.

Objective:
To analyze flight fare patterns and build a Machine Learning model that accurately predicts flight ticket prices for unseen data.

Project Structure:

flight-price-prediction/
│
├── data/
│   ├── Data_Train.xlsx
│   ├── Test_set.xlsx
│   └── Sample_submission.xlsx
│
├── outputs/
│   └── flight_price_predictions.csv
│
├── notebook/
│   └── Flight_price_prediction.ipynb
│
└── README.md

Dataset Description:

Data_Train.xlsx        -> Training dataset with target prices
Test_set.xlsx          -> Test dataset without prices
Sample_submission.xlsx -> Sample prediction format

Data Preprocessing:

- Removed missing and invalid values
- Extracted date and time features
- Encoded categorical columns using Label Encoding
- Applied Route Frequency Encoding
- Log transformation on target variable
- Scaled back predictions using exponential transformation

Machine Learning Models Used:

- Linear Regression
- ElasticNet
- Ridge Regression (RidgeCV)
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- AdaBoost Regressor
- Support Vector Regressor (SVR)
- XGBoost Regressor (Best Model)

Best Performing Model:

XGBoost Regressor achieved the highest R² score and lowest RMSE among all models.

Output:

The predicted flight prices are stored in:
outputs/flight_price_predictions.csv

How to Run:

1. Open the notebook:
   notebook/Flight_price_prediction.ipynb
2. Run all cells
3. The prediction file will be generated automatically in the outputs folder.

Author:
Kalpana Bhardwaj
