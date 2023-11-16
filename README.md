# Prediction-of-Smoker-Status

## Table of Contents

- Overview
- Data
- Project Workflow
## Overview

This project revolves around predicting the smoker status of individuals based on bio-signals. The dataset, derived from a deep learning model trained on the Smoker Status Prediction using Bio-Signals dataset, consists of both training and test datasets. 
The primary objective is to predict the probability of positive smoking for individuals.

## Data
Datasets are from Kaggle competition - Binary Prediction of Smoker Status using Bio-Signals
https://www.kaggle.com/competitions/playground-series-s3e24/data

## Project Workflow
* Data Visualization Overview: The project initiates with a comprehensive visualization overview of the dataset. This step aids in understanding the data's characteristics and identifying potential patterns.

* Model Building with XGBoost: The core of the project involves building a predictive model using the XGBoost algorithm. This model aims to predict the smoker status based on the bio-signals provided in the dataset.

* Evaluation Metrics:

  - Log Loss: The model's performance is evaluated using log loss, providing insights into the accuracy of probability predictions.
  - ROC AUC: Another crucial metric is the Receiver Operating Characteristic (ROC) Area Under the Curve (AUC), which measures the model's ability to distinguish between positive and negative cases.

