#  Yelp Rating Regression Predictor

## Overview
The Yelp Rating Regression Predictor project aims to predict restaurant ratings on Yelp using a Multiple Linear Regression model. By analyzing a comprehensive dataset provided by Yelp, this project identifies key factors influencing restaurant ratings and forecasts the potential success of a new restaurant, Danielle's Delicious Delicacies.

## Goals
Data Integration: Combine multiple datasets from Yelp into a single, cohesive DataFrame.
Feature Analysis: Identify features that significantly impact Yelp ratings.
Model Development: Build and evaluate regression models to predict ratings.
Prediction: Forecast ratings for a new restaurant using the best-performing model.

## Dataset Description
The project utilizes six .json files from Yelp:

yelp_business.json: Contains business details.
yelp_review.json: Contains review metadata.
yelp_user.json: Contains user profile data.
yelp_checkin.json: Contains check-in data.
yelp_tip.json: Contains tip data.
yelp_photo.json: Contains photo metadata.


## Methodology
1. Data Preparation
Loading Data: Import data from .json files into Pandas DataFrames.
Data Cleaning: Handle missing values and remove unnecessary columns.
Data Merging: Combine DataFrames using the business_id column.

2. Exploratory Data Analysis (EDA)
Correlation Analysis: Calculate correlation coefficients to identify significant features.
Visualization: Use scatter plots to visualize relationships between features and ratings.

3. Model Building
Feature Selection: Choose subsets of features for model training.
Model Training: Train Multiple Linear Regression models on selected features.
Model Evaluation: Assess model performance using R² scores and visual inspections.

4. Prediction
Forecasting: Predict the Yelp rating for Danielle's Delicious Delicacies using the best model.

## Tools and Libraries
Pandas: Data manipulation and analysis.
NumPy: Numerical operations.
Scikit-learn: Machine learning model development.
Matplotlib & Seaborn: Data visualization.
