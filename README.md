# Time Series Forecasting with LSTM and GRU

## Project Overview

This project aims to predict future weather conditions based on historical weather data using time series forecasting techniques. We evaluate and compare several models, including Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), tuned LSTM, and Bidirectional LSTM, to determine which performs best for forecasting tasks.

## Objectives

- **Data Preparation**: Preprocess historical weather data, including scaling and creating sequences for modeling.
- **Model Building**: Construct and train various models including LSTM, GRU, Tuned LSTM, and Bidirectional LSTM.
- **Model Evaluation**: Assess the performance of each model using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²).
- **Comparison**: Compare models to identify the best-performing one based on evaluation metrics.

## Data

The dataset used for this project is historical weather data, which includes temperature readings over time. The data is loaded, scaled, and transformed into sequences suitable for time series forecasting.

## Models

### LSTM (Long Short-Term Memory)
A type of recurrent neural network designed to learn from sequences of data.

### GRU (Gated Recurrent Unit)
A variation of LSTM that is computationally more efficient.

### Tuned LSTM
An LSTM model with hyperparameters optimized for improved performance.

### Bidirectional LSTM
An LSTM model that processes data in both forward and backward directions to capture more contextual information.

## Code

The project includes the following code sections:

1. **Data Preparation**: Load and preprocess the data.
2. **Model Building**: Define and compile the LSTM, GRU, Tuned LSTM, and Bidirectional LSTM models.
3. **Model Training**: Train each model using the prepared dataset.
4. **Model Evaluation**: Evaluate the models using MSE, RMSE, and R² metrics and summarize the results.
