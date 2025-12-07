🚗 Car Price Prediction using Machine Learning

A complete end-to-end Machine Learning project for predicting real-world used-car prices using regression models, feature engineering, model evaluation, and deployment-ready pipelines. This includes full EDA, preprocessing, ML pipelines, hyperparameter tuning, and trained model export.

📌 Overview

This project develops a predictive ML system that estimates used-car market prices based on historical listing attributes such as brand, model, year, engine size, fuel type, transmission, mileage and condition.
The aim is to understand how vehicle characteristics affect resale value and to automate price estimation for automotive platforms, dealers, and consumers.

🧠 Problem Statement

Car resale pricing is often subjective and inconsistent, depending on manual expert evaluation and personal judgement. This leads to price variation, negotiation challenges, and lack of transparency for buyers and sellers.
This project automates the valuation process using Machine Learning, enabling fair, data-driven, and consistent pricing based on historical market listings.

🎯 Objectives

Perform exploratory data analysis
Identify price-influencing factors
Implement regression models
Build preprocessing + ML pipelines
Compare multiple models
Tune hyperparameters
Evaluate performance using metrics
Export final trained model for reuse

📊 Dataset

Car Price Prediction Dataset (2025) — Kaggle
Author: Ali Hussain
https://www.kaggle.com/datasets/aliiihussain/car-price-prediction

Main attributes

Brand
Model
Year
Engine Size
Fuel Type
Transmission
Mileage
Condition
Price (target)

🛠 Technologies Used

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Joblib
Jupyter Notebook

🔍 Machine Learning Pipeline

✔ Data loading
✔ Data cleaning
✔ Missing-value handling
✔ Exploratory Data Analysis
✔ Statistical insights
✔ Feature engineering
✔ Categorical encoding
✔ Scaling numeric features
✔ Train/Test split
✔ Regression modeling
✔ Hyperparameter tuning
✔ Model evaluation
✔ Saving final model

🤖 Models Implemented

Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
XGBoost

🧪 Evaluation Metrics

MAE
RMSE
R² score

📌 Feature Engineering

Car Age
High Mileage indicator

📁 Folder Structure
car_price_prediction/
│
├── car_price_prediction.ipynb
├── car_price_rf_model.joblib
├── data/
│     └── car_price_prediction_.csv
└── README.md

🚀 How to Run

Clone
git clone <repository-link>
cd car_price_prediction
Install
pip install -r requirements.txt
Run
jupyter notebook car_price_prediction.ipynb

📌 Results

Mileage, Engine Size, Car Age and Brand strongly impact price
RandomForestRegressor performed best after tuning
Trained model exported for deployment

🔥 Real-World Use Cases

OLX, Cars24 selling platforms
Dealership price estimation
Insurance price evaluation
Used-car valuation tools
Auto-loan risk analytics

👩‍💻 Author

Priyanka Burra
