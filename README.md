# 🕒 Time Predictor – ML Model for Estimating Product Delivery Time

A machine learning project that predicts the **estimated delivery time** of a product using structured historical data. The model leverages feature engineering, data normalization, and advanced regression algorithms to deliver high accuracy.

---

## 📌 Key Highlights

- ✅ **Complete ML pipeline** from preprocessing to prediction.
- 🧹 **Feature extraction and normalization** using `StandardScaler`.
- 🤖 **Evaluated multiple models**:
  - XGBoost ✅ (best performing)
  - CatBoost
  - Random Forest
- 🧠 Final model: **XGBoost Regressor**

---

## 🧰 Tools & Technologies

| Category       | Tools / Libraries                                |
|----------------|--------------------------------------------------|
| Language       | Python                                           |
| Notebook       | Google Colab                                     |
| ML Libraries   | Scikit-learn, XGBoost, CatBoost                   |
| Data Handling  | Pandas, NumPy                                     |
| Visualization  | Matplotlib, Seaborn                               |

---

## 🧪 Workflow

1. **Data Loading**  
   Load dataset from CSV.

2. **Feature Engineering**  
   - Extract features from raw columns  
   - Encode categorical data  
   - Handle missing values

3. **Normalization**  
   Applied `StandardScaler` for consistent scaling.

4. **Model Training & Evaluation**  
   - Used Train/Test split  
   - Trained XGBoost, CatBoost, and Random Forest  
   - Selected **XGBoost** based on RMSE and R²

5. **Prediction**  
   Predict delivery times on new input data.

---

## 📈 Model Performance

| Metric         | Value (Example)  |
|----------------|------------------|
| R² Score       | 0.89             |
| RMSE           | 1.42             |
| MAE            | 1.10             |

> *Replace with your actual evaluation metrics after running the notebook.*

---

## 🚀 Use Cases

- Delivery & Logistics ETA Forecasting  
- Supply Chain Optimization  
- E-commerce Tracking Systems  
- Timeline Estimation for Products or Projects

---

## 📄 License

This project is licensed under the **MIT License** – feel free to use, modify, and distribute.

---
