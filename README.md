# Australia-Rainfall-Prediction

## Project Overview

This project aims to design and develop a machine learning model that predicts whether it will rain the next day in Australia. Using historical weather data, the model classifies the target variable RainTomorrow (Yes/No) based on several meteorological features, including temperature, humidity, wind speed, cloud cover, atmospheric pressure, and rainfall from the current day.
The goal is to improve weather forecasting accuracy, providing valuable insights for agricultural planning, daily activities, and safety measures.

## Problem Statement

Design a machine learning model to predict whether it will rain the next day in Australia. Using historical weather data, the model should accurately classify the target variable "RainTomorrow" (Yes/No) based on features such as:  

- Temperature
- Humidity
- Wind speed
- Cloud cover
- Atmospheric pressure
- Rainfall
  
  The outcome of the model will help improve the accuracy of weather forecasting, supporting timely decision-making in agriculture, safety planning, and other daily activities.

## Dataset

- Date: Observation date
- Location: City/town where the weather is recorded
- MinTemp: Minimum temperature of the day
- MaxTemp: Maximum temperature of the day
- Rainfall: Amount of rainfall (mm)
- Humidity9am, Humidity3pm: Humidity levels in the morning and afternoon
- WindSpeed9am, WindSpeed3pm: Wind speed at different times
- RainToday: Whether it rained today (Yes/No)
- RainTomorrow: Target variable, indicates whether it will rain the next day (Yes/No)

## Project Workflow

1. Exploratory Data Analysis (EDA)
2. Data Preprocessing
3. Model Building
4. Evaluation Metrics

## Models used

1. Logistic Regression
2. Random Forest
3. KNN Algorithm 
4. Decision Tree

## Results

1. Best Model:
-  Out of all above models Random forest Classifier gives the highest Accuracy of 91 % and F1-Score 91%.
  
2. Insights:
-  Humidity and RainToday were the most influential features.
-  Wind speed also played a significant role, especially at 9 AM.
-  Cloud cover and atmospheric pressure had moderate predictive power.
