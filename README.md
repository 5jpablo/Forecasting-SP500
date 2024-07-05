# S&P 500 Index Price Forecasting

## Project Overview

This project aims to forecast future prices of the S&P 500 index using a combination of statistical and deep learning models. We implement and compare three different methodologies:

1. ARIMA (AutoRegressive Integrated Moving Average)
2. RNN (Recurrent Neural Network)
3. LSTM (Long Short-Term Memory)

## Objectives

- Develop accurate forecasting models for S&P 500 index prices
- Compare the performance of traditional statistical methods with deep learning approaches
- Provide insights for investors and financial analysts to make informed decisions

## Technologies Used

- Python
- Pandas for data manipulation
- Numpy for numerical computations
- Scikit-learn for model evaluation
- Statsmodels for ARIMA implementation
- TensorFlow/Keras for RNN and LSTM implementation
- Matplotlib and Seaborn for data visualization

## Project Structure

1. **Data Collection**: Historical S&P 500 data from Yahoo Finance API
2. **Data Preprocessing**: Cleaning, normalization, and splitting into train/test sets
3. **Model Implementation**:
   - ARIMA model
   - Simple RNN model
   - LSTM model
4. **Model Evaluation**: Using RMSE, MAE, and MAPE metrics
5. **Forecasting and Visualization**: Predicting future prices and visualizing results

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/5jpablo/Forecasting-SP500.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Forecasting-SP500
    ```
3. Create and activate a virtual environment:
    ```bash
    virtualenv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```