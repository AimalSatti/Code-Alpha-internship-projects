# Iris Flower Classification.

This project focuses on classifying the type of iris-flower based on the measurements.

## 📌 Features & Workflow
- **Data Preprocessing:** Handled missing values, outliers, and log transformation for skewed numerical features like (`sepal_length`, `petal_width`).
- **Feature Scaling:** Used `StandardScaler` to scale features before model training.
- **Model Training:** Trained a LogisticRegression model that achieved an **Accuracy Score of ~1.0**.
- **Modular Inference Pipeline:** Saved `iris_model.pkl` separately to preprocess raw incoming user data during deployment.

## 📁 Files
- `iris_01.ipynb`: Data cleaning, EDA, and feature transformation.
- `iris_02.ipynb`: Model training, evaluation, and inference pipeline.
- `iris_model.pkl`: Trained LogisticRegression model.
  

## 🛠️ Tech Stack
- Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Joblib
-