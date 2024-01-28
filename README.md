# Predictive Analysis of Sarajevo's AQI using Machine Learning Models for Varied Data Granularity and Prediction Windows

This repository is the official implementation of "Predictive Analysis of Sarajevo's AQI using Machine Learning Models for Varied Data Granularity and Prediction Windows" paper.

This project aims to predict Air Quality Index (AQI) using various machine learning models.

## Requirements

To install requirements run:
* pip install -r requirements.txt

## Directory Structure

- `Datasets_creation.ipynb`: Notebook for creating datasets.
- `Dataset/`: Contains all the datasets used in this project.
- `AQI Visualization/`: Contains notebooks for visualizing AQI data.
- `LSTM_air_quality_Sarajevo.ipynb`: Notebook for predicting AQI using LSTM model.
- `Prophet_air_quality_Sarajevo.ipynb`: Notebook for predicting AQI using Prophet model.
- `Fourier-ARIMA_air_quality_Sarajevo.ipynb`: Notebook for predicting AQI using Fourier-ARIMA model.
- `common_functions.py`: Contains common functions used across notebooks.
- `Results/`: Contains the results of the models.
- `Results_visualisation.ipynb`: Notebook for visualizing the results.

## Training and evaluating

To train and evaluate the models in the paper, uncomment experiment code in LSTM, Prophet and Fourier-ARIMA_air_quality_Sarajevo.ipynb and run all cells.

NOTE: Experiment execution will take very long time to finish.


