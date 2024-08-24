# AQI Prediction Using Classification Algorithms

## Description

This project aims to predict the Air Quality Index (AQI) using various classification algorithms. The AQI is a crucial indicator of air pollution levels and plays a significant role in public health awareness. By analyzing historical air quality data from multiple cities across India, the project develops a predictive model capable of assessing the AQI based on several key pollutants, including PM2.5, PM10, NOx, SO2, CO, NH3, and O3.

## Key Features

- **Data Collection:** Utilizes a comprehensive dataset containing air quality measurements from 26 cities in India, covering the period from January 2015 to July 2020.
- **Data Preprocessing:** Includes handling missing values, normalizing data, and calculating subindices for each pollutant using established AQI guidelines.
- **Model Development:** Implements and trains a Decision Tree classifier to predict the AQI based on the subindices of the pollutants.
- **Prediction Interface:** Provides a user-friendly interface built with Gradio for inputting pollutant levels and receiving real-time AQI predictions.
- **Visualizations:** Offers visual analysis through bar plots and grouped data to illustrate the distribution and levels of different pollutants across various cities.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Gradio
- **Machine Learning Algorithm:** Classification and Regression Algorithms
- **Visualization:** Seaborn and Matplotlib for creating insightful plots
- **Interface:** Gradio for building a simple yet effective user interface for AQI prediction

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/darshan12345678910/Air-quality-prediction-ml-algorithms.git

