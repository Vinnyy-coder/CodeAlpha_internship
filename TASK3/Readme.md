# Car Price Prediction using Machine Learning

## Overview

This project focuses on predicting the selling price of used cars using Machine Learning techniques. A Linear Regression model was developed to estimate car prices based on various features such as present price, kilometers driven, fuel type, transmission type, ownership history, and car age.

## Objective

* Analyze car-related data.
* Perform data preprocessing and feature engineering.
* Train a regression model for price prediction.
* Evaluate model performance using regression metrics.
* Visualize relationships between features and selling price.

## Dataset

The dataset contains information about used cars including:

* Car Name
* Year
* Selling Price
* Present Price
* Driven Kilometers
* Fuel Type
* Selling Type
* Transmission
* Owner

Total Records: 301

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Project Workflow

### 1. Data Collection

Loaded the car dataset using Pandas.

### 2. Data Preprocessing

* Checked for missing values.
* Removed unnecessary columns.
* Created a new feature: Car_Age.
* Encoded categorical variables.

### 3. Exploratory Data Analysis

* Dataset statistics
* Correlation analysis
* Heatmap visualization

### 4. Model Building

Used Linear Regression for predicting car prices.

### 5. Model Evaluation

Evaluated the model using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 6. Visualization

Created:

* Correlation Heatmap
* Actual vs Predicted Price Plot
* Selling Price Distribution

## Results

The model successfully learned relationships between vehicle features and selling price, producing accurate predictions on unseen data.

## Project Structure

Car-Price-Prediction/

├── car_price_prediction.ipynb

├── car data.csv

├── README.md

├── Report.pdf


## Future Improvements

* Random Forest Regressor
* XGBoost Regressor
* Hyperparameter Tuning
* Deployment using Streamlit or Flask

## Conclusion

This project demonstrates how Machine Learning can be used to estimate vehicle prices and assist buyers and sellers in making informed decisions.
