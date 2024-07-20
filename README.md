# Energy Consumption Time Series Forecasting

This project focuses on forecasting energy consumption using time series analysis and machine learning techniques. The dataset used is the PJM Interconnection LLC (PJME) hourly energy consumption data.

## Project Overview

The main objectives of this project are:
1. Data preprocessing and exploratory data analysis
2. Feature engineering for time series data
3. Implementation of XGBoost Regressor for forecasting
4. Model evaluation and performance analysis
5. Visualization of results

## Technologies Used

- Python 3.x
- Libraries: numpy, pandas, xgboost, matplotlib, seaborn, scikit-learn

## Dataset

The dataset used is the PJME_hourly.csv file, which contains hourly energy consumption data for the PJM Interconnection LLC (PJME) region.

## Key Features

1. Data preprocessing and datetime indexing
2. Creation of time-based features (day of month, month, day of year, week of year, day of week, hour)
3. Exploratory data analysis with visualizations
4. Train-test split based on a specific date
5. Implementation of XGBoost Regressor for forecasting
6. Model evaluation using RMSE and R-squared metrics
7. Time series cross-validation
8. Feature importance analysis
9. Learning curve analysis

## Results

The project demonstrates the application of machine learning techniques to forecast energy consumption. Key outcomes include:
- Visualization of actual vs predicted energy consumption
- Analysis of feature importance in the forecasting model
- Evaluation of model performance using various metrics
- Insights into the patterns and trends of energy consumption

### Model Performance Metrics

Training Metrics:
- R2 Score: 0.9539
- Accuracy (within 10%): 0.9748

Test Metrics:
- R2 Score: 0.9021
- Accuracy (within 10%): 0.9257

These results show strong performance on both training and test data, with high R2 scores and accuracy within 10% tolerance. The model performs slightly better on the training data, which is expected, but still maintains good performance on the test data.

## How to Use

1. Clone the repository
2. Install the required dependencies (numpy, pandas, xgboost, matplotlib, seaborn, scikit-learn)
3. Run the Jupyter notebook or Python script to execute the analysis

## Future Improvements

- Experiment with other machine learning algorithms
- Incorporate external factors like weather data
- Implement more advanced feature engineering techniques
- Explore deep learning models for time series forecasting
