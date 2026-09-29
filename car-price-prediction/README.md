# 🚗 Car Price Prediction

This project focuses on predicting the resale price of used cars based on historical data using Machine Learning techniques.

## 📌 Features & Workflow
- **Data Preprocessing:** Handled missing values, outliers, and log transformation for skewed numerical features (`Present_Price`, `Driven_kms`).
- **Categorical Encoding:** Applied One-Hot Encoding to categorical variables (`Fuel_Type`, `Selling_type`, `Transmission`).
- **Feature Scaling:** Used `StandardScaler` to scale features before model training.
- **Model Training:** Trained a Linear Regression model that achieved an **$R^2$ score of ~0.9177**.
- **Modular Inference Pipeline:** Saved `car_model.pkl` and `scaler.pkl` separately to preprocess raw incoming user data during deployment.

## 📁 Files
- `car_01.ipynb`: Data cleaning, EDA, and feature transformation.
- `car_02.ipynb`: Model training, evaluation, and inference pipeline.
- `car_model.pkl`: Trained Linear Regression model.
- `scaler.pkl`: Fitted StandardScaler object.

## 🛠️ Tech Stack
- Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Joblib
-