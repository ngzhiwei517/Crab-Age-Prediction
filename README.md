# Crab Age Prediction Using Regression Models

This repository contains the implementation of a regression model to predict the ages of crabs (in months) based on various features such as sex, length, diameter, height, and others. The dataset used for this task is named `ModifiedCrabAgePrediction.csv`, and it is utilized to train, test, and evaluate multiple regression models.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
  - [Data Analysis](#1-data-analysis)
  - [Data Preprocessing](#2-data-preprocessing)
  - [Regression Model Development](#3-regression-model-development)
  - [Model Evaluation](#4-model-evaluation)
- [How to Run](#how-to-run)
- [Evaluation Criteria](#evaluation-criteria)


## Project Overview

The main objective of this lab work is to apply regression techniques to predict the age of crabs, a task that involves data analysis, preprocessing, model training, and evaluation. The project workflow includes loading the dataset, exploring its features, preprocessing data, training regression models, and evaluating their performance using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²).

## Dataset

- **Dataset Name**: `ModifiedCrabAgePrediction.csv`
- **Features**:
  - **Sex**: The sex of the crab (categorical)
  - **Length**: Length of the crab's body (numeric)
  - **Diameter**: Diameter of the crab's shell (numeric)
  - **Height**: Height of the crab's shell (numeric)
  - **Weight**: Weight of the crab (numeric)
- **Target**:
  - **Age**: Age of the crab in months (numeric)

## Project Workflow

### 1. Data Analysis

- Load and analyze the given dataset.
- Explore the data to identify features and the target variable (age).
- Gain insights into the dataset's structure and relationships between features.

### 2. Data Preprocessing

- Handle missing values in the dataset.
- Process categorical variables (e.g., encoding `Sex`).
- Scale/normalize numerical features (e.g., `Length`, `Diameter`, `Height`).
- Split the dataset into training and testing sets for model evaluation.

### 3. Regression Model Development

- Implement multiple regression models such as Linear Regression, Polynomial Regression, and others.
- Train each model using the training data and evaluate performance.
- Experiment with hyperparameters like regularization, learning rate, etc., to optimize the models.

### 4. Model Evaluation

- Evaluate the best performing model on the testing set.
- Report performance metrics such as:
  - **MSE (Mean Squared Error)**
  - **RMSE (Root Mean Squared Error)**
  - **R² (R-squared)**

## How to Run

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/ngzhiwei517/Crab-Age-Prediction.git
    cd crab-age-prediction
    ```

2. Install required dependencies (assuming you have Python and pip installed):

    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter notebook (`crab_age_prediction.ipynb`) in Google Colab or any Jupyter notebook environment.

4. Follow the instructions within the notebook to load the dataset, preprocess it, train models, and evaluate them.

## Evaluation Criteria

The performance of the regression models will be evaluated using the following metrics:
- **MSE (Mean Squared Error)**: Measures the average squared difference between the predicted and actual values.
- **RMSE (Root Mean Squared Error)**: Provides the square root of MSE, offering an error metric in the same units as the target variable.
- **R² (R-squared)**: Indicates how well the regression model fits the data.
