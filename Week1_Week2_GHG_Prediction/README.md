# 🌱 Greenhouse Gas Emission Prediction – Shell + AICTE Skills4Future Internship

This repository contains my Week 1 and Week 2 submissions for the Shell + AICTE Skills4Future internship project.  
The objective is to analyze and predict **Greenhouse Gas Emissions** across various U.S. industries using data-driven techniques.

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

## 🧰 Tools & Libraries Used

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `Week1_Week2_GHG_Prediction.ipynb` | Full notebook with Week 1 + Week 2 work |
| `best_random_forest_model.pkl` | Exported tuned ML model |
| `SupplyChainEmission.csv` | Dataset used |
| `README.md` | Project summary |
| `plots/` | Folder containing exported charts (optional) |

---
