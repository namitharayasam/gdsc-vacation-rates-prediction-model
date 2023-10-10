# vacation-rates-prediction-model

Predict vacation rates for tourist destinations based on environmental factors like temperature, humidity, and surface pressure using machine learning.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Models](#models)
- [Evaluation](#evaluation)


## Introduction
This project predicts vacation rates to assist travel booking companies in recommending destinations. It utilizes historical data and machine learning with environmental variables.

## Dataset
The dataset contains features like temperature, humidity, surface pressure, and vacation rates. It's split into a training set for model development and a test set for evaluation.

## Features
Feature engineering enhances model performance. Key features include temperature range squared, humidity-temperature interaction, and pressure differences.

## Models
Multiple models have been explored like Random Forest, MultiOutput Regressor, Decision Trees, xgboost, etc.

## Evaluation
Models are evaluated using Root Mean Squared Error (RMSE) on a holdout test dataset. Lower RMSE values indicate better predictions.
