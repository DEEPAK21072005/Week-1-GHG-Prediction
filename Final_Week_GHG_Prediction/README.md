# 🌱 Greenhouse Gas Emission Prediction – Shell + AICTE Skills4Future Internship

This repository contains my Week 1, Week 2, and Week 3 submissions for the Shell + AICTE Skills4Future internship project.  
The objective is to analyze and predict **Greenhouse Gas Emissions** across various U.S. industries using data-driven machine learning techniques.

---

## 📘 Week 1 – Data Cleaning & Visualization

**Objective:**  
Understand and prepare the emission dataset for further modeling.

### ✅ Tasks Completed:
- Loaded and explored the **Supply Chain Emission Factors dataset**
- Removed null values and duplicate rows
- Cleaned the data using `pandas`
- Used `matplotlib` and `seaborn` to visualize:
  - Emission levels by industry
  - Histogram of emission distributions
- Identified key insights and patterns to support ML modeling

---

## 🤖 Week 2 – Machine Learning Modeling

**Objective:**  
Build regression models to predict supply chain emission factors and analyze model performance.

### ✅ Tasks Completed:
- Selected numeric features and handled missing values
- Split data into training and testing sets
- Trained 3 ML models:
  - `Linear Regression`
  - `Decision Tree Regressor`
  - `Random Forest Regressor`
- Evaluated all models using:
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
  - R² Score
- Performed **hyperparameter tuning** using `GridSearchCV` (on Random Forest)
- Visualized:
  - RMSE comparison (bar chart)
  - Actual vs Predicted emissions (scatter plot)
  - Residual distribution (error analysis)
  - Top 10 Feature Importances (bar chart)
- Exported final tuned model as `.pkl` file for future use

---

## 🚀 Week 3 – Advanced Modeling & Explainability (XGBoost + SHAP)

**Objective:**  
Enhance prediction performance and interpretability using advanced modeling and explainability tools.

### ✅ Tasks Completed:
- Performed **Feature Engineering**:
  - Created interaction-based and normalized emission features
- Scaled features using `StandardScaler`
- Trained advanced ML models:
  - `XGBoost Regressor`
  - `Gradient Boosting`
  - `HistGradientBoosting`
- Compared all models on:
  - RMSE
  - MAE
  - R² Score
- Selected best model based on performance (XGBoost)
- Performed **SHAP Explainability**:
  - Generated summary plots to explain feature importance
  - Highlighted impactful features using SHAP values
- Saved final best model (`Week3_XGBoost_Model.pkl`)

---

## 🧰 Tools & Libraries Used

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost
- SHAP
- Joblib

---

## 📂 Files Included

| File                          | Description                                           |
|-------------------------------|-------------------------------------------------------|
| `Week1_Week2_GHG_Prediction.ipynb` | Jupyter Notebook for Week 1 and Week 2                |
| `Week3_XGBoost_Model.pkl`     | Saved XGBoost model after Week 3 training             |
| `best_random_forest_model.pkl`| Saved Random Forest model from Week 2                 |
| `SupplyChainEmission.csv`     | Dataset used throughout the project                   |
| `README.md`                   | Project summary and documentation                     |

---

## 📌 Status
✅ All 3 weeks completed    
💡 Standing out with advanced model, feature engineering & SHAP explainability
