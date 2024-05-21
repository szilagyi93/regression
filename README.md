# Regression Models for Combined Cycle Power Plant (CCPP)

This repository contains the implementation of various regression models to predict the full load electrical power output of a CCPP based on environmental variables such as Temperature (AT), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V). The analysis is inspired by the paper "Prediction of full load electrical power output of a base load operated combined cycle power plant using machine learning methods."

## Project Overview

This project aims to demonstrate the application of machine learning regression techniques to predict the power output of a combined cycle power plant. Different regression models are explored, evaluated, and compared to identify the most effective model for this prediction task.

## Repository Contents

- `eda_ccpp.ipynb`: Exploratory Data Analysis (EDA) notebook analyzing the datasets and visualizing important characteristics.
- `modelfitting_ccpp.ipynb`: Notebook containing the training and validation of regression models.
- `score_evaluation_ccpp.ipynb`: Notebook for evaluating the models using various metrics such as MSE, R2, and Cross-Validation scores.
- `data/`: Directory containing training and testing datasets.
- `figures/`: Directory where visualizations from the analysis are saved.

## Models Implemented

- Linear Regression
- Ridge Regression
- K-Nearest Neighbors (KNN)
- Support Vector Regression (SVR)
- Decision Trees and Random Forest
- Multi-layer Perceptron (Neural Network)

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/szilagyi93/regression.git
