# Deep Learning CO2 Forecasting Using LSTM Networks

## Introduction
This project focuses on forecasting daily CO2 emissions using deep learning model LSTM. The goal is to predict the next-day CO2 emission for multiple countries using historical environmental, economic, and energy related data.

## Problem Definition
The objective of this project is to predict future CO2 emissions based on historical time-series data. Given past observations of environmental conditions, energy usage, and economic indicators for each country, the model learns temporal dependencies to estimate the next-day CO2 emission.

This is formulated as a supervised time-series regression problem where the input is a sequence of past values and the output is a continuous numerical prediction.

## Dataset Description
The dataset used in this project is the Climate & Energy Consumption Dataset (2020–2024), w
hich contains historical records of environmental indicators across 20 countries collected from 2020-2024.

Each record includes the following features:
• CO2 emission  
• Average temperature  
• Humidity  
• Energy consumption  
• Renewable energy share  
• Urban population  
• Industrial activity index  
• Energy price  
• Country name  
• Date of observation  
## Kaggle Notebook
The full implementation is available here:  
https://www.kaggle.com/code/smanevskaa/co2forecaster

For modeling, additional engineered features were created, including lagged CO2 values and cyclical time features (month, day of year, day of week). The final dataset is used to construct sequential input windows for LSTM-based forecasting.
