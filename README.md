# Taxi Order Prediction

## Project Overview

The goal of this project is to develop a machine learning model that predicts the number of taxi orders in the next hour. This project utilizes historical data on taxi orders at airports, provided by the company "Chotenkoye Taxi". Accurate predictions will help attract more drivers during peak demand periods. The target metric for the model is RMSE, which should not exceed 48 on the test dataset.

## Project Steps

1. **Load and Resample Data**: Load the dataset and resample the data by one hour intervals.
2. **Data Analysis**: Perform an analysis of the data to understand patterns and correlations.
3. **Model Training**: Train various models with different hyperparameters. Use 10% of the original data as a test set.
4. **Evaluation**: Evaluate the models on the test set and draw conclusions.

## Dataset Description

The data is available in the file `/datasets/taxi.csv`. The column `num_orders` contains the number of taxi orders.

## Instructions

1. Load the data from `/datasets/taxi.csv`.
2. Resample the data to hourly intervals.
3. Analyze the data to identify trends and patterns.
4. Train different machine learning models, tuning their hyperparameters.
5. Split the data, using 10% as a test set.
6. Evaluate the models using the test set and ensure the RMSE does not exceed 48.

## Submission

Once you have completed the project, submit your work for review. The reviewer will provide feedback within 24 hours. Revise your project based on the feedback and resubmit it. You may need to make several iterations based on the reviewer's comments. The project is considered complete once all revisions are approved by the reviewer.
