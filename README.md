# Trilemma_BTC_Prediction

## Bitcoin ROI Prediction using LSTM and ARIMA Ensemble

This repository contains a Python script for predicting the weekly Return on Investment (ROI) of Bitcoin using a powerful combination of Long Short-Term Memory (LSTM) networks and Autoregressive Integrated Moving Average (ARIMA) models. The script leverages historical Bitcoin price data to forecast future ROI, potentially aiding in investment decisions.

### Key Features:

Ensemble Approach: Combines the strengths of LSTM for capturing non-linear patterns and ARIMA for modeling time series trends, potentially leading to more accurate predictions.

Automated ARIMA Parameter Optimization: Employs pmdarima's auto_arima function to automatically determine the optimal parameters for the ARIMA model, simplifying the modeling process.

Data Scaling: Uses MinMaxScaler to scale the input data, improving the performance and stability of the LSTM model.

Clear Data Splitting: Divides the data into distinct training, validation, and testing sets to ensure robust model evaluation and prevent overfitting.

Comprehensive Evaluation Metrics: Calculates the Mean Absolute Error (MAE) for each individual model and the ensemble on both validation and test sets, providing insights into prediction accuracy.

Future Forecasting: Demonstrates how to forecast the ROI for a specific future date.

### Requirements:
Python 3.7+

### Libraries: 
pandas, numpy, scikit-learn, tensorflow, pmdarima, matplotlib

### Instructions:
Install the necessary libraries.
Replace the placeholder data loading code with your actual Bitcoin price data from a reliable source.
Run the script.

### Output:
The script will print the following:
Summary of the optimized ARIMA model
Validation and Test MAE scores for the LSTM, ARIMA, and Ensemble models
Plots comparing actual ROI with predictions from each model
Forecasted ROI for the next Monday and a specified future date

### Customization:
Explore different LSTM architectures and hyperparameters.
Experiment with alternative ARIMA configurations.
Incorporate additional features like trading volume, market sentiment, or technical indicators.
