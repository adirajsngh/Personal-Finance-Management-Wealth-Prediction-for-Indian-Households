# Indian Household Wealth Predictor

This project implements a machine learning-based system to predict whether an individual from an Indian household will be considered wealthy by the age of 60 and estimate their projected wealth using financial behavior data.

## Objective

To apply classification and regression models on synthetic Indian household data and analyze how income, expenses, and saving patterns contribute to long-term wealth accumulation.

## Features Engineered

- `Monthly_Savings`: Income minus total expenses
- `Savings_Rate`: Monthly savings divided by income
- `Projected_Wealth`: Estimated wealth at age 60 (without compounding)
- `Wealthy_By_60`: Binary label for classification (based on a specified wealth threshold)

## Models Implemented

### Classification
- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  
- Multi-layer Perceptron (MLP) Classifier  

### Regression
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

## Key Insights

- Engineered features like savings rate and monthly savings proved to be strong indicators of financial success.
- Models effectively distinguished between high savers and low savers across income brackets.
- Classification and regression approaches complemented each other to give both binary decisions and numerical forecasts.

## Visualizations

- Confusion matrices comparing classifier performance
- Residual and prediction plots for regression models
- Comparison of MAE, RMSE, and R² scores across regressors

## How to Run

1. Upload the `data.csv` file in a Jupyter or Google Colab environment.
2. Open `Personal_Finance_Management_and_Wealth_Prediction_using_Machine_Learning_for_Indian_Households.ipynb`.
3. Execute all cells in order to preprocess data, train models, and visualize results.
4. Modify model parameters or threshold values as needed.

## Acknowledgments

This project is based on financial behavior data modeling and aims to raise awareness about the importance of early savings and expense tracking, particularly in the context of Indian households.

## Contact

For suggestions or collaboration, feel free to reach out via GitHub or email.
