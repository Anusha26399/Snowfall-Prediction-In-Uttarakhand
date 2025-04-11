# ❄️ Snowfall Prediction in Uttarakhand

A machine learning project focused on **predicting the annual mean snowfall rate** in Uttarakhand, India using a range of statistical and ML models.

---

## 🎯 Objective

To develop a reliable snowfall prediction model using climate and meteorological data.  
The aim is to understand which factors contribute most to snowfall and predict annual snowfall rates effectively.

---

## 🧪 Dataset Overview

- 📍 **Region**: Uttarakhand, India
- 📊 **Total Features**: 36
- 🧵 **Features Used**: Selected based on **VIF (Variance Inflation Factor)** and **correlation heatmap**
- 📁 **Label**: Annual Mean Snowfall Rate

### 🌡️ Key Input Features

```python
[
  'longitude', 'latitude', 'time', 'u100', 'v100', 'u10n', 'v10n', 'fg10',
  'd2m', 't2m', 'anor', 'isor', 'bld', 'blh', 'cbh', 'cin', 'csf', 'csfr',
  'lgws', 'ewss', 'zust', 'z', 'gwd', 'hcc', 'lsf', 'lssfr', 'lcc', 'msl',
  'mser', 'msr', 'mcc', 'ptype', 'sp', 'tcsw', 'tcslw', 'deg0l'
]
```
🧠 Models Used
🔹 Linear Regression

🔹 Logistic Regression

🔹 Random Forest Regressor

🔹 Ridge Regression

🔹 Gradient Boosting Regressor

🧰 Tech Stack
Python

📦 Libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, `statsmodels`

📊 Feature Selection
✅ Correlation Heatmap: Visualized with `seaborn.heatmap` to identify multicollinearity

✅ VIF Analysis: Features with high VIF scores were removed to prevent overfitting and redundancy

📈 Evaluation Metrics
🔹 R² Score

🔹 Mean Absolute Error (MAE)

🔹 Root Mean Squared Error (RMSE)


