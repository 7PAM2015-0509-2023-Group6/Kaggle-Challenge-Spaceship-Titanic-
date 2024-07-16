Spaceship Titanic Kaggle Challenge

Overview

This repository contains the code and documentation for the Spaceship Titanic Kaggle Challenge. The objective of the challenge is to predict which passengers were transported to an alternate dimension when the Titanic spaceship collided with a spacetime anomaly.

Project Description

The Spaceship Titanic challenge requires participants to analyze and model a dataset to predict the outcome of passengers' journeys. Our approach includes data preprocessing, feature engineering, and applying various machine learning models to achieve the best prediction accuracy.

Dataset

The dataset used for this challenge is provided by Kaggle and includes information about the passengers on the Spaceship Titanic. The dataset is split into training and test sets:

train.csv: Contains the training data with features and target labels.

test.csv: Contains the test data without target labels.

Methodology

Our approach involves the following steps:

Data Preprocessing: Handling missing values, encoding categorical variables, and scaling numerical features.

Feature Engineering: Creating new features based on domain knowledge and exploratory data analysis.

Model Training: Training various machine learning models, including Random Forest , Gradient Boosting, XG-Boost, LightGBM

Model Evaluation: Evaluating models using cross-validation and selecting the best performing model based on accuracy and other metrics.

Prediction: Making predictions on the test set and preparing the submission file.

Results

Our best model achieved an accuracy of 80.07% on the validation set. The final submission file is available in the submissions directory.

