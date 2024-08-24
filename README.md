# AirPredict: AQI Prediction using Classification Algorithms

AirPredict is a project that leverages machine learning classification algorithms to predict the Air Quality Index (AQI) of various cities. By using historical AQI data, the model can classify the air quality into categories, helping to forecast environmental conditions and potentially warn about poor air quality in advance.

## Table of Contents
- [AirPredict: AQI Prediction using Classification Algorithms](#airpredict-aqi-prediction-using-classification-algorithms)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Algorithms Used](#algorithms-used)
  - [Data](#data)
  - [How to Run](#how-to-run)
  - [Results](#results)
  - [Contributing](#contributing)
  - [License](#license)

## Introduction

Air pollution is a significant environmental risk to health, and monitoring air quality is essential for both public health and environmental policy. The Air Quality Index (AQI) is a measure used to communicate how polluted the air currently is or how polluted it is forecast to become. In this project, we use machine learning to predict AQI levels based on historical data from multiple cities.

## Features

- Predicts the AQI based on historical data.
- Classifies AQI into categories (Good, Moderate, Unhealthy, etc.).
- Supports multiple machine learning classification algorithms.
- Visualization of AQI trends and predictions.

## Algorithms Used

The project explores various machine learning classification algorithms to find the most accurate model for AQI prediction:

- **Logistic Regression**
- **Decision Trees**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **K-Nearest Neighbors (KNN)**

## Data

The dataset used in this project contains historical AQI data from 26 cities across India, spanning from 2015 to 2020. The data includes the following cities:

- Ahmedabad
- Delhi
- Mumbai
- Bengaluru
- Lucknow
- Chennai
- Hyderabad
- Patna
- Gurugram
- Visakhapatnam
- Amritsar
- Jorapokhar
- Jaipur
- Thiruvananthapuram
- Amaravati
- Brajrajnagar
- Talcher
- Kolkata
- Guwahati
- Coimbatore
- Shillong
- Chandigarh
- Bhopal
- Kochi
- Ernakulam
- Aizawl

### Data Sources

The AQI data is collected from various public sources, including government and environmental agencies.

## How to Run

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/darshan12345678910/Air-quality-prediction-ml-algorithms.git
    cd Air-quality-prediction-ml-algorithms
    ```

2. **Install Dependencies:**
    Ensure you have Python 3.7.10 installed. Then, install the necessary Python packages using pip:

3. **Run the Notebook:**
    Launch Jupyter Notebook and run the `AirPredict.ipynb` file to see the predictions and visualizations.
    ```bash
    jupyter notebook AirPredict.ipynb
    ```

## Results

This project demonstrates the effectiveness of various machine learning models in predicting AQI. The performance of each model is evaluated based on accuracy, precision, recall, and F1-score. The results help in identifying the most suitable algorithm for AQI prediction.

