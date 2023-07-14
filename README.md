# Air Quality Index (AQI) Prediction

This project aims to predict the Air Quality Index (AQI) based on various air pollutant parameters such as PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, and Xylene.

## Problem Statement

The goal of the AQI Prediction project is to develop a machine learning model that accurately predicts the AQI based on historical air pollutant data. This information is crucial for assessing air quality and making informed decisions for public health and environmental management.

## Architecture of the Project

The project follows the following steps:

## 1. Exploratory Data Analysis (EDA)

- **Description of Data:** Provide a description of the dataset, including the meaning of each column and its significance in predicting the AQI.
- **Identify Numerical and Categorical Columns:** Differentiate between numerical and categorical columns for further analysis and preprocessing.
- **Check Missing Values:** Identify missing values in the dataset and visualize them using graphs and percentages.
- **Drop Unnecessary Columns:** Remove unnecessary columns, such as the AQI_Bucket column, which is not required for the prediction task.
- **Outlier Detection:** Identify outliers in the numerical columns and handle them using techniques such as mean, median, mode, or by using the interquartile range (IQR).
- **Handling Missing Values:** Impute missing values using appropriate techniques such as mean, median, mode, or other suitable methods.
- **Ordinal Encoding:** Convert the categorical column "City" into numeric values using ordinal encoding.
- **Save Modified Dataset:** Save the preprocessed dataset into a CSV file for further feature selection and model training.

## 2. Feature Selection and Model Training

- **Feature Score Calculation:** Calculate feature scores using various techniques such as correlation, chi-square test, or information gain to identify the most important features for predicting the AQI.
- **Train Multiple Models:** Train multiple machine learning models using the selected features, considering algorithms such as linear regression, decision tree regression, random forest regression, or gradient boosting regression.
- **Select Best Model:** Evaluate the performance of each model using appropriate evaluation metrics and select the best-performing model for AQI prediction.

## Usage

1. Prepare your dataset containing air pollutant parameters and corresponding AQI values in the desired format (e.g., CSV, Excel).
2. Execute the Exploratory Data Analysis (EDA) script to perform data preprocessing steps, including handling missing values, outliers, and categorical encoding.
3. Save the modified dataset for feature selection and model training.
4. Execute the Feature Selection and Model Training script to calculate feature scores, train multiple models, and select the best model for AQI prediction.
5. Evaluate the model's performance using appropriate evaluation metrics such as mean squared error (MSE), root mean squared error (RMSE), or R-squared (R2) score.
6. Utilize the trained model to make AQI predictions for new air pollutant parameter data.


