# Car-Price-Prediction-using-Machine-Learning
🚗 Machine Learning based system for predicting real-world used car prices using regression modeling, feature engineering, and hyperparameter tuning. Includes EDA, ML pipelines, model evaluation and deployment-ready saved model.

📌 Overview

This project builds a Machine Learning regression model that predicts used car prices based on real-world car listing data such as brand, model, year, engine size, fuel type, transmission, condition, mileage, and more.

The goal is to help understand how different car specifications influence market price and to build a predictive model that can be used in real-world automotive pricing systems.

🧠 Problem Statement

The used-car market heavily depends on expert judgement for pricing decisions, which often leads to inconsistent valuation. Buyers and sellers face difficulty estimating fair prices due to lack of transparency and manual pricing.

This project aims to develop an automated price estimation ML system that uses historical car listings and vehicle features to accurately predict market prices using regression analysis.

🎯 Objectives

Perform data analysis on used car listings

Identify key features affecting car resale price

Build machine learning regression models

Compare model performance

Predict car price using vehicle specifications

Perform hyperparameter tuning for improved accuracy

Evaluate model performance using regression metrics

📊 Dataset

Car Price Prediction Dataset (2025) – Kaggle
Author: Ali Hussain
Dataset Link: https://www.kaggle.com/datasets/aliiihussain/car-price-prediction

Features include:
Column	Description
Brand	Car manufacturer
Model	Car model name
Year	Manufacturing year
Engine Size	Engine capacity
Fuel Type	Petrol/Diesel/Electric/Hybrid
Transmission	Manual/Automatic
Mileage	Distance driven
Condition	New, Used, etc
Price	Target variable
🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Joblib

Jupyter Notebook

🔍 Steps Performed

✔ Data Loading
✔ Data Cleaning
✔ Handling Missing Values
✔ Exploratory Data Analysis
✔ Feature Engineering
✔ Preprocessing using ColumnTransformer
✔ ML Pipeline Setup
✔ Train/Test Split
✔ Model Training
✔ Hyperparameter Tuning
✔ Evaluation using

MAE

RMSE

R²
✔ Saving Trained Model
✔ Prediction on New Data

🤖 Models Implemented

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

XGBoost (optional)

🧪 Evaluation Metrics

Used regression metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

📌 Feature Engineering

Created additional features:

Car Age

High Mileage indicator

📎 Folder Structure
car_price_prediction/
│
├── car_price_prediction.ipynb
├── car_price_rf_model.joblib
├── data/
│     └── car_price_prediction_.csv
└── README.md

📦 How to Run
Clone Repository
git clone <repository-link>
cd car_price_prediction

Install dependencies
pip install -r requirements.txt

Run notebook
jupyter notebook car_price_prediction.ipynb

📌 Results

Mileage, Engine Size, Car Age, Brand, Condition highly influence car pricing.

Tuned RandomForestRegressor gives best performing estimation model.

Model saved for deployment using joblib.

🚀 Possible Real-World Applications

Used-car marketplaces (OLX, Cars24)

Dealership pricing

Insurance valuation

Financial auto-loans

Online pricing calculators

📍 Author

Priyanka Burra
