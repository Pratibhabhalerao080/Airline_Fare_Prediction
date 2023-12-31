# Predict Airline Fare Ticket using Machine Learning

This is a Machine Learning project that aims to predict airline ticket fares based on various features and data collected. In this README, you will find an overview of the project, steps taken, and important information for understanding and replicating the project.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Collection](#data-collection)
- [Data Cleaning](#data-cleaning)
- [Data Preprocessing and Feature Extraction](#data-preprocessing-and-feature-extraction)
- [Data Analysis](#data-analysis)
- [Feature Encoding](#feature-encoding)
- [Model Building](#model-building)
- [Evaluation Metrics](#evaluation-metrics)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Conclusion](#conclusion)

## Project Overview
The project focuses on predicting airline ticket fares using machine learning techniques. It involves collecting, cleaning, and preprocessing data, as well as extracting relevant features. The data is then used to build a predictive model, and the model's performance is evaluated.

## Data Collection
The project begins with data collection from an Excel file, which is loaded into a Pandas DataFrame. The data consists of various features related to flight tickets, including departure times, arrival times, airline information, source, destination, total stops, and more.

## Data Cleaning
Data cleaning involves handling missing values, converting data types, and making the dataset ready for analysis and modeling. Missing values are dropped from the dataset, and data types are converted where necessary.

## Data Preprocessing and Feature Extraction
The project preprocesses the data, including converting timestamps to datetime objects, extracting useful features from timestamp data, and converting the duration of flights to minutes. This step also includes feature encoding for categorical variables.

## Data Analysis
Exploratory data analysis is performed to gain insights into the data. This includes analyzing the distribution of flight departure times and visualizing how different airlines affect ticket prices.

## Feature Encoding
Categorical features are encoded using one-hot encoding and manual encoding for specific variables. Unnecessary features are dropped to streamline the dataset.

## Model Building
A random forest regressor model is built to predict ticket prices. The data is split into training and testing sets, and the model's performance is evaluated using various metrics.

## Evaluation Metrics
The project defines evaluation metrics, including mean absolute percentage error (MAPE), and visualizes the model's performance by comparing predicted and actual ticket prices.

## Hyperparameter Tuning
Hyperparameter tuning is performed to optimize the random forest regressor model. A randomized search is conducted to find the best hyperparameters for the model.

## Conclusion
This README provides an overview of the project, including its purpose and the steps involved. It is a guide for anyone interested in understanding and replicating the project for predicting airline ticket fares using machine learning techniques.

For more detailed information and code implementation, please refer to the project files and code.
