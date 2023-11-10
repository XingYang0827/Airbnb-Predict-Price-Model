# Airbnb-Predict-Price-Model
## Overview
The Airbnb Rent Price Prediction project is designed to predict the rental prices of properties on the Airbnb platform based on location information such as neighborhood safety and distance to the town center. The project consists of three main parts: data preprocessing, model training, and model evaluation.

## Features
### 1. Data Preprocessing
OneHot Encoder: Categorical variables are encoded using OneHot encoding, ensuring compatibility with machine learning models.

Handling Missing Values: Missing values are replaced with means, maintaining data integrity and completeness.

Outlier Removal: Outliers are identified and replaced, preventing them from adversely affecting model training.

Correlation Analysis: Features with a small correlation with the label are identified and deleted, streamlining the dataset for more focused model training.

### 2. Model Training
Linear Model: A linear regression model is trained to capture linear relationships between input features and rent prices.

Decision Tree Model: A decision tree regression model is employed to capture non-linear relationships in the data.

Stacking Model: Models are stacked to combine their predictions, harnessing the strengths of different algorithms for enhanced predictive performance.

GridSearch for Parameter Tuning: GridSearch is utilized to find the best parameters for each model, optimizing their performance.

### 3. Model Evaluation
Accuracy: The accuracy of the models in predicting rent prices is measured, providing an indication of their overall correctness.

Root Mean Squared Error (RMSE): RMSE is calculated to quantify the difference between predicted and actual rent prices, providing insights into the model's precision.

R2 Score: R2 Score is used to assess the goodness-of-fit of the models, indicating the proportion of the variance in the dependent variable that is predictable.

## Requirements
Python 3.x
Scikit-learn
Pandas
NumPy
