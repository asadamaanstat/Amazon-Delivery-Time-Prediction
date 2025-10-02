# Delivery Time Prediction Project

## Project Overview
This project focuses on predicting delivery times for orders using machine learning. It aims to provide accurate estimates based on various features related to orders, geographic locations, weather, traffic, and vehicle types to enhance logistics efficiency and customer satisfaction.

## Dataset
The dataset includes details such as:
- Agent demographics and ratings
- Store and drop-off latitude/longitude
- Order dates and times
- Weather and traffic conditions
- Vehicle and area information
- Delivery time as the target variable

## Features and Engineering
- Geodesic distance calculated between store and drop locations
- Date/time features such as order hour, pickup hour, and day of the week extracted
- Categorical variables encoded using one-hot encoding
- Outlier treatment applied for data quality

## Models Trained and Evaluated
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor (final selected model)

Model performance was measured using RMSE, MAE, and R2 metrics, with Gradient Boosting achieving the best results.

## How to Use
1. Clone this repository.
2. Load and preprocess the data.
3. Train the models or load the saved model.
4. Use the model to predict delivery times given input features.

## Future Work
- Apply model explainability tools to better understand feature impacts.
- Experiment with other models and hyperparameter tuning.
- Deploy the model with UI for real-time predictions.

## Technologies Used
- Python, pandas, scikit-learn
- MLflow for experiment tracking
- Joblib for model saving/loading

## Author
***Asad Amaan***

---

Feel free to explore the notebooks and scripts for more details on implementation and results.
