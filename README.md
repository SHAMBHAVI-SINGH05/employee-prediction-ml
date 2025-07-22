# 🧠 Employee Prediction ML Project

This machine learning project predicts the number of delivery agents needed per hour based on:

- ✅ Order Volume  
- 🌦️ Weather  
- 🚦 Traffic Level  
- 📅 Holidays  
- ⏰ Time of Day  
- 📊 Additional operational metrics (e.g., temperature, delivery time deviation)

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `cleaned_encoded_delivery_dataset1.csv` | Cleaned dataset used for training |
| `finaltwo_delivery_dataset_with_promised_actual_and_nulls.xlsx` | Raw dataset with time and missing values |
| `agent_model.pkl` | Trained linear regression model |
| `agent_model_dt.pkl` | Trained decision tree model |
| `agent_model_rf_tuned.pkl` | Tuned random forest model |
| `ridge_model.pkl` | Ridge regression model |
| `lasso_model.pkl` | Lasso regression model |
| `agent_scaler.pkl` | StandardScaler used for preprocessing |

---

## 📊 Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor (with GridSearchCV)
- Ridge Regression
- Lasso Regression

---

## 📈 Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Approximate Accuracy (custom formula)

---

## 📌 How to Run

1. Clone the repo
2. Open the notebook or Python scripts
3. Install dependencies (`scikit-learn`, `pandas`, `joblib`, etc.)
4. Run the models or load `.pkl` files for prediction

---

## 🔗 Colab Link (if available)

[Open in Google Colab](https://colab.research.google.com/drive/1L5ZwRWgGipHaZd54uL6oSQ0RELDCh286)

---

## 📬 Contact

Created by [Shambhavi Singh](https://github.com/SHAMBHAVI-SINGH05)  
📧 shambhavisingh05@example.com
