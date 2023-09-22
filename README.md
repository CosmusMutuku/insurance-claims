# Insurance Claim Prediction Project

## Overview

This repository contains the code and data for an insurance claim prediction project. The project aims to develop machine learning models to predict the average claim amount for insurance policyholders. The code in this repository includes data preprocessing, feature engineering, model training, and evaluation.

## Table of Contents

- [Data Exploration](#one)
- [Data Visualization](#two)
- [Data Preprocessing](#three)
- [Modelling](#four)
- [Model Performance](#five)

## 1. Data Exploration <a id="one"></a>

In the initial phase of the project, we explore the dataset to understand its structure and characteristics. This involves loading the data and performing basic data analysis to identify any missing values or anomalies.

## 2. Data Visualization <a id="two"></a>

Data visualization is an essential step in understanding the data and its underlying patterns. In this phase, we create various visualizations to gain insights into the data. This includes histograms, bar plots, and correlation heatmaps to visualize relationships between features and the target variable.

## 3. Data Preprocessing <a id="three"></a>

Data preprocessing is a critical step to prepare the data for model training. This phase involves:
- Replacing missing values with appropriate defaults.
- Cleaning and standardizing categorical features such as occupation, model, colour, and industry type.
- Creating new features, such as age, vehicle age, exposure, and claim frequency.
- Encoding categorical features using one-hot encoding.
- Binarizing selected features and scaling numerical features.

## 4. Modelling <a id="four"></a>

In the modeling phase, we create and train machine learning models to predict the average claim amount. The code includes the following steps:
- Splitting the dataset into training, validation, and test sets.
- Binarizing and scaling the data as needed.
- Training a linear regression model on the training set.
- Making predictions on the validation and test sets.

## 5. Model Performance <a id="five"></a>

The model's performance is evaluated using various metrics, including root mean squared error (RMSE) and mean absolute error (MAE). Visualizations are also provided to compare predicted and actual values.

## Repository Structure

- `data/`: Contains the dataset used for this project.
- `code/`: Contains the Jupyter Notebook with the code used for data analysis and modeling.
- `images/`: Stores images generated during data visualization.
- `README.md`: The file you are currently reading, providing an overview of the project and code.

## Getting Started

To run the code and reproduce the results, follow these steps:

1. Clone this repository to your local machine.
2. Set up a Python environment with the required libraries (see `requirements.txt`).
3. Open the Jupyter Notebook in the `code/` directory and run each cell in sequence.

## Acknowledgments

- Special thanks to the team members who contributed to this project.
  
## Contacts
if you have any question you can email: cosmuskavithi@gmail.com
