# 🚗 Car Price Prediction using Machine Learning

A complete **end-to-end Machine Learning project** for predicting real-world used car prices using regression techniques. The project covers **EDA, preprocessing, feature engineering, model building, hyperparameter tuning, evaluation, and model export** for deployment readiness.

---

## 📌 Overview

This project builds a predictive Machine Learning system to estimate **used-car market prices** based on historical listing attributes such as:

- Brand  
- Model  
- Manufacturing Year  
- Engine Size  
- Fuel Type  
- Transmission  
- Mileage  
- Vehicle Condition  

The objective is to understand how vehicle characteristics influence resale value and to automate price estimation for **automotive platforms, dealers, and consumers**.

---

## 🧠 Problem Statement

Used-car pricing is often **subjective and inconsistent**, relying heavily on manual expert judgment. This results in price variation, negotiation challenges, and lack of transparency.

This project addresses the issue by applying **Machine Learning-based regression models** to provide **data-driven, fair, and consistent price predictions** using historical market data.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Identify key price-influencing factors
- Implement and compare multiple regression models
- Build preprocessing and ML pipelines
- Apply feature engineering techniques
- Tune hyperparameters for optimal performance
- Evaluate models using standard regression metrics
- Export the final trained model for reuse and deployment

---

## 📊 Dataset

**Car Price Prediction Dataset (2025)**  
Source: Kaggle  
Author: *Ali Hussain*  
🔗 https://www.kaggle.com/datasets/aliiihussain/car-price-prediction

### Key Attributes

- Brand  
- Model  
- Year  
- Engine Size  
- Fuel Type  
- Transmission  
- Mileage  
- Condition  
- **Price (Target Variable)**

---

## 🛠 Technologies Used

- **Python**
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 🔍 Machine Learning Pipeline

✔ Data Loading  
✔ Data Cleaning  
✔ Missing Value Handling  
✔ Exploratory Data Analysis  
✔ Statistical Insights  
✔ Feature Engineering  
✔ Categorical Encoding  
✔ Feature Scaling  
✔ Train-Test Split  
✔ Regression Modeling  
✔ Hyperparameter Tuning  
✔ Model Evaluation  
✔ Model Serialization  

---

## 🤖 Models Implemented

- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost Regressor  

---

## 🧪 Evaluation Metrics

- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

---

## 📌 Feature Engineering

- Car Age (derived from manufacturing year)
- High Mileage Indicator

---

## 📁 Folder Structure

car_price_prediction/
│
├── car_price_prediction.ipynb
├── car_price_rf_model.joblib
├── data/
│ └── car_price_prediction_.csv
└── README.md

yaml
Copy code

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/burrapriyanka85-pixel/Car-Price-Prediction-using-Machine-Learning.git
Navigate to the project directory

bash
Copy code
cd car_price_prediction
Install required dependencies

bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook

bash
Copy code
jupyter notebook car_price_prediction.ipynb
📌 Results & Insights
Mileage, Engine Size, Car Age, and Brand significantly impact car prices

Random Forest Regressor delivered the best performance after tuning

Final trained model successfully exported for deployment use

🔥 Real-World Use Cases
Used-car marketplaces (OLX, Cars24, etc.)

Automobile dealerships for price estimation

Insurance valuation systems

Used-car valuation tools

Auto-loan and risk analytics platforms

👩‍💻 Author
Priyanka Burra
M.Sc. Bioinformatics
