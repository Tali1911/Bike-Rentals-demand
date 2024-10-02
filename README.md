# Bike-Rentals-demand
# Machine Learning Project: K-Nearest Neighbors - Predicting Bike Rentals Demand

## Overview

This repository contains a project that utilizes K-Nearest Neighbors (KNN) regression to predict the daily demand for bike rentals based on various influential factors. The aim is to assist bike-sharing services in accurately forecasting bike demand, thereby optimizing bike allocation across different locations.

## Problem Statement

The primary objective of this project is to build a KNN regression model to predict the daily demand for bike rentals. The prediction is based on features such as weather conditions (temperature, humidity, wind speed), the day of the week, and whether it is a holiday. By accurately predicting bike rental demand, bike-sharing services can enhance their operational efficiency.

## Dataset

The dataset includes hourly and daily bike rental data, featuring essential attributes such as:
- **Date:** The date of rental
- **Temperature:** Daily temperature (in Celsius)
- **Humidity:** Relative humidity percentage
- **Wind Speed:** Daily wind speed (in km/h)
- **Season:** The season during the rental period
- **Holiday Status:** Whether the day is a holiday
- **Bike Rentals:** The number of bikes rented on that day

## Project Steps

1. **Data Exploration and Cleaning:** Investigate the dataset for inconsistencies, handle missing values, and perform necessary data cleaning.
2. **Feature Selection and Engineering:** Identify and create relevant features that can improve the model’s accuracy.
3. **Data Splitting:** Split the dataset into training and testing sets to evaluate model performance effectively.
4. **Build and Train the KNN Model:** Develop the KNN regression model using the training set and optimize it for better predictions.

By following these steps, the project aims to provide a robust model that can serve as a valuable tool for bike-sharing services to manage their fleet efficiently.
