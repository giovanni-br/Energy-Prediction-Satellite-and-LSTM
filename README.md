# Energy Consumption Prediction in Rio Grande do Sul using Night-Time Satellite Light Images

![energy_prediction](https://github.com/user-attachments/assets/a5566b3a-1ea9-411d-9f24-f4a95117bd2a)



## Project Overview

This project explores the relationship between night-time satellite light images and electricity consumption in Rio Grande do Sul, Brazil. Leveraging open data from the VIIRS-DNB satellite and energy consumption statistics from the Brazilian Energy Research Company (EPE), the aim is to create predictive models that can optimize energy resource management at a low cost.

The project evaluates statistical and econometric relationships, such as correlation, causality, and cointegration, to determine how well night-time lights can serve as a predictor for energy consumption. Two different forecasting models are compared:
- A classical **ARIMA (Auto-Regressive Integrated Moving Average)** model
- A modern **LSTM (Long Short-Term Memory)** deep learning model

## Objectives
- Explore how night-time satellite images can improve energy consumption forecasting.
- Provide a low-cost solution for optimizing energy management in Rio Grande do Sul.
- Compare the performance of ARIMA and LSTM models, with and without the inclusion of night-time light data.

## Methodology
1. **Data Collection**:
   - **Night-time light data**: Collected from the VIIRS-DNB satellite and pre-processed.
   - **Energy consumption data**: Obtained from the Brazilian Energy Research Company (EPE).

2. **Data Processing & Analysis**:
   - Statistical analysis: Correlation, causality (Granger causality test), and cointegration tests were performed to explore relationships between the datasets.
   - Time-series forecasting: Models were built using Python, utilizing the `statsmodels`, `Scikit-Learn`, and `Keras` libraries.

3. **Model Comparison**:
   - **ARIMA Model**: A classical statistical model that uses historical data to make future predictions.
   - **LSTM Model**: A deep learning model that can capture complex time-series relationships by learning from past sequences.

## Results
Preliminary results show that incorporating night-time light data can improve the accuracy of energy consumption predictions. The ARIMA model performed better when night-time lights were included, while the LSTM model also showed promise in forecasting energy consumption.
