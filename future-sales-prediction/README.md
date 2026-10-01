# Future Sales Prediction.

This project focuses on predicting the future sale price  based on advertising spend and target segmentjnjn.

## 📌 Features & Workflow
- **Data Preprocessing:** Handled missing values, outliers, and log transformation for skewed numerical features (`TV`, `Radio`).
- **Feature Scaling:** Used `StandardScaler` to scale features before model training.
- **Model Training:** Trained a Linear Regression model that achieved an **$R^2$ score of ~0.8994**.
- **Modular Inference Pipeline:** Saved `sales_prediction_model.pkl` separately to preprocess raw incoming user data during deployment.

## 📁 Files
- `sales_01.ipynb`: Data cleaning, EDA, and feature transformation.
- `sales_02.ipynb`: Model training, evaluation, and inference pipeline.
- `Sales_prediction_model.pkl`: Trained Linear Regression model.
  

## 🛠️ Tech Stack
- Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Joblib
-