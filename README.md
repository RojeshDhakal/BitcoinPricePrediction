# Bitcoin Price Analysis and Prediction

## Overview
This project focuses on analyzing historical Bitcoin price data using statistical modeling techniques and LSTM neural networks for predictive modeling.

## Dataset
- **Source**: yfinance API
- **Features**: Includes daily open, high, low, close prices, and volume.

## Steps and Analysis

### Data Preparation
- Cleaned the dataset by removing duplicates and unnecessary columns.
- Visualized Bitcoin price trends over time.

### Exploratory Data Analysis
- Explored relationships between Bitcoin prices and other variables using regression plots.
- Identified key dates and highest price points in Bitcoin's history.

### Time Series Analysis
- Conducted stationarity tests (ADF test) on Bitcoin closing prices.
- Applied ARIMA modeling to capture time series patterns and make predictions.

### LSTM Neural Network Modeling
- Prepared data for LSTM modeling by scaling and reshaping.
- Built an LSTM model architecture with multiple layers and dropout for regularization.
- Trained the LSTM model using historical Bitcoin price data.

### Model Evaluation
- Evaluated the LSTM model performance using RMSE and Mean Absolute Percentage Error (MAPE).
- Compared LSTM predictions with actual test data.

## Results
- Achieved an RMSE of approximately 437.93, indicating the average difference between actual and predicted Bitcoin prices.
- MAPE of 3.53% suggests the model's accuracy in predicting Bitcoin price movements.

## Future Work
- Fine-tune LSTM model parameters for better performance.
- Explore ensemble methods or deep learning architectures for enhanced predictive capabilities.

## Author
- Your Name
- Contact Information

