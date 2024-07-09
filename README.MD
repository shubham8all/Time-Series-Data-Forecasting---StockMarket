# Time Series Data Forecasting

## Project Overview
This project focuses on the forecasting of time series data using various machine learning models. The primary goal is to analyze and predict the future values of a given time series dataset.

## Project Structure
- **Data Preprocessing and Exploration**: This section includes importing libraries, setting up the environment, loading datasets, and initial data exploration.
- **Modeling and Forecasting**: Different models are implemented to forecast the time series data.
- **Evaluation**: The models are evaluated based on their performance metrics.

## Models Used
### 1. ARIMA (AutoRegressive Integrated Moving Average)
- **Description**: A classical statistical method used for time series forecasting.
- **Results**: Achieved a Mean Absolute Percentage Error (MAPE) of 8.51% on the test set.

### 2. SARIMA (Seasonal AutoRegressive Integrated Moving Average)
- **Description**: An extension of ARIMA that supports univariate time series data with a seasonal component.
- **Results**: Achieved a MAPE of 8.42% on the test set.

### 3. RandomForest Regressor
- **Description**: An ensemble learning method for regression that operates by constructing multiple decision trees.
- **Results**: Achieved a MAPE of 2.36% on the test set.

### 4. Support Vector Regressor (SVR)
- **Description**: A type of Support Vector Machine that supports linear and non-linear regression.
- **Results**: Achieved a MAPE of 4.41% on the test set.

### 5. LSTM (Long Short-Term Memory)
- **Description**: A type of recurrent neural network (RNN) capable of learning long-term dependencies.
- **Results**: Achieved a MAPE of 3.17% on the test set.

## Results
- **AR**: 8.96%
- **ARIMA**: 8.51%
- **SARIMA**: 8.42%
- **RandomForest**: 2.36%
- **SVM**: 4.41%
- **LSTM**: 3.17%

## Data Preparation
1. **Importing Important Libraries**: Necessary libraries for data manipulation, visualization, and modeling are imported.
2. **Setting Up Environment**: The working path and configurations are set up.
3. **Loading Datasets**: The datasets are loaded and initial data exploration is conducted.
4. **Data Cleaning**: The data is cleaned, and irrelevant values and outliers are removed.

## Data Understanding
- **Statistical Analysis**: Key statistics of the dataset are analyzed.
- **Visualization**: Data is visualized to understand its distribution, seasonality, trend, and noise components.