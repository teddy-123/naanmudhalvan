# Electricity-Prices-Prediction
This Project Aims to develop a predictive model that uses historical electricity prices and relevant factors to forecast future electricity prices. The objective is to create a tool that assists both energy providers and consumers in making informed decisions regarding consumption and investment by predicting future electricity prices.
## Table Of Contents
- [Installation]
- [Data Preprocessing]
- [Feature Engineering]
- [Model Selection]
- [Model Training]
- [Evaluation]
## Installation
- Download the Dataset via the [link](https://www.kaggle.com/datasets/chakradharmattapalli/electricity-price-prediction).
- Copy the Github link and Clone this Repository into your local Device
## Usage
- Head to the Repository Path and Upload ADS_Phase4 file into any of your ipynb Simulators
- Link the Downloaded Dataset into the ipynb File
## Data Preprocessing
- Convert the Datatype of the columns in the Dataset as per their Requirements
- Replace the Missing Values using NaN values by Pandas library
- Handle Missing Values using ffill method to replace NaN Values
## Feature Engineering
Create additional features that could enhance the predictive power of the model, such as time-based features and lagged variables.
## Model Selection
Arima Model is Preferred because it uses differenced data to make the data stationary, which means there's a consistency of the data over time. This function removes the effect of trends or seasonality, such as market or economic data.
## Model Training
- Resample the Dataset and Plot the New SubPlots
- Find P,D,Q Values
- Fit the Model using Resampled Dataset and P,D,Q Values
## Evaluation
- Train and Test the Arima Model by Splitting the Time Series dataset
- Fit the Target Data into Auto ARIMA model and Predict the Future Values by Forecasting
- Plot the Predicted Target Data
- Plot the Predicted Target Data for the Future Unseen Values
