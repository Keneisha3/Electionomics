# Electionomics
This repository contains the data, scripts, and models developed for predicting stock market prices based on U.S. presidential election results. This project aimed to analyze the impact of political shifts on stock market behavior, leveraging machine learning techniques to create a predictive model.  

## Objectives
* Analyze potential correlations between U.S. presidential election outcomes and stock market performance.
* Build a machine learning model to predict stock price movements during a presidential term.
* Compare multiple machine learning techniques to determine the most effective predictive approach.

## Repository Structure

### `data/`
Contains all datasets used throughout the project, including:

* Raw data collected from Kaggle and other public sources.
* Cleaned and processed datasets prepared for training and evaluation.

### `dataset_creation/`
Python scripts for data preprocessing, cleaning, feature engineering, and dataset generation.

### `eda/`
Exploratory data analysis scripts used to uncover trends, identify relationships between variables, and inform model development.

### `trial_models/`
Experimental models evaluated during the model selection process, including:

* Random Forest
* K-Means Clustering
* K-Nearest Neighbors (KNN)
* Support Vector Machines (SVM)

This directory documents model comparison and performance assessment across different approaches.

### `random_forest/`
Final implementation using a Random Forest Regressor, featuring:

* K-Fold Cross Validation for reliable performance evaluation.
* Hyperparameter Tuning to optimize model accuracy.
* XGBoost integration for enhanced predictive performance.
* Prediction outputs, actual vs. predicted comparisons, and statistical performance summaries.
