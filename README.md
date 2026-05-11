# public-transport-delay-prediction
# Public Transport Delay Prediction

## Overview
This project builds a machine learning model to predict public transport arrival delays using real-world factors such as weather conditions, traffic congestion, time of day, and special events. The goal is to understand what factors most influence delays and to build a predictive model that can estimate delay times accurately.

---

## Problem Statement
Public transport delays affect commuters, scheduling systems, and overall urban mobility. This project aims to:
- Analyze key factors contributing to delays
- Visualize patterns in delay behavior
- Build predictive models to estimate delay duration

---

## Dataset Features
The dataset includes the following variables:

- `date` – Date of travel
- `time` – Scheduled time of trip
- `weather_condition` – Weather during travel
- `temperature_C` – Temperature in Celsius
- `traffic_congestion_index` – Traffic severity score
- `event_type` – Special events affecting traffic
- `actual_arrival_delay_min` – Target variable (delay in minutes)

---

## Data Processing & Feature Engineering
- Converted date into **month, day, and year**
- Extracted **hour** from time column
- Handled missing values in event data
- Encoded categorical variables using label encoding

---

## Exploratory Data Analysis (EDA)
The project includes multiple visualizations:
- Average delay by weather condition
- Average delay by event type
- Delay patterns by hour of the day
- Relationship between temperature and delays
- Relationship between traffic congestion and delays

---

## Machine Learning Models

### 1. Linear Regression
Used as a baseline model to predict delay duration.

### 2. Random Forest Regressor
An ensemble model used to improve prediction accuracy and capture nonlinear relationships.

---

## Model Evaluation Metrics
Models are evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Random Forest performed better compared to Linear Regression in capturing complex patterns.

---

## Feature Importance
The most influential features affecting delay prediction include:
- Traffic congestion index
- Weather conditions
- Hour of travel
- Event type

---

## Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## Project Structure
