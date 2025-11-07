# Medical-cost-prediction
Medical cost prediction using multiple linear regression
# 🏥 Medical Insurance Cost Prediction

Predicting individual **medical insurance charges** using **Multiple Linear Regression** on the [Kaggle Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance).

---

## 🔍 Project Overview
The aim of this project is to explore how **age**, **BMI**, **number of children**, **smoking status**, and **region** influence medical insurance costs, and to build a regression model capable of estimating those charges accurately.

**Dataset Summary**
- **Source:** Kaggle – Medical Cost Personal Dataset  
- **Records:** 1,338  
- **Features:** 7 (age, sex, bmi, children, smoker, region, charges)

**Model Used**
- Multiple Linear Regression (baseline model)

**Libraries**
- NumPy  
- Pandas  
- Matplotlib  
- scikit-learn

---

## ⚙️ Workflow

1. **Data Loading & Cleaning**  
   - Read dataset, check for missing or invalid values  
   - Handle categorical variables and encode them  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize feature relationships  
   - Identify correlations and outliers  

3. **Model Building**  
   - Apply Multiple Linear Regression  
   - Train-test split for validation  

4. **Model Evaluation**  
   - R² (Coefficient of Determination)  
   - Adjusted R²  
   - MAE (Mean Absolute Error)  
   - RMSE (Root Mean Squared Error)

5. **Visualization**  
   - Compare actual vs predicted charges  

---

## 📊 Results

| Metric | Value (Approx.) |
|--------|----------------|
| R² | 0.75 |
| Adjusted R² | 0.74 |
| MAE | 0.07 (normalized scale) |
| RMSE | 0.10 | Low, indicating strong fit |

The model performs well in capturing the linear trends between medical cost and influencing factors.

---

## 🚀 Future Improvements
- Implement **Polynomial Regression** to capture non-linear effects  
- Experiment with **Random Forest** or **XGBoost** regressors  
- Add **regularization** (Ridge/Lasso) to handle feature correlation  
- Perform **cross-validation** for better generalization  

---

## 📁 Repository Structure

📦 medical-cost-prediction
 
->📜 medical_cost_prediction.ipynb

->📜 README.md
 


---

## 🧠 Author
**Developed by:** Pankaj Maity
**Goal:** To understand and predict medical insurance costs using machine learning fundamentals.

---

## 🏷️ License
This project is for educational and research purposes only. Dataset provided by [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance).
