# 🚗 Car Price Prediction with Linear Regression  

## 📖 Introduction  
This project aims to **predict car prices** using linear regression.  
It demonstrates the **end-to-end data science pipeline**, from data cleaning to model evaluation and diagnostics.  

> Notebook language: **French (explanations)** + **English (code & comments)**  

---

## 🏗️ Workflow  

### 🔹 1. Data Acquisition & Inspection  
- Load dataset `CarPrice_Assignment.csv`  
- Initial exploration of variables  

### 🔹 2. Preprocessing & Cleaning  
- Remove irrelevant columns  
- Fix missing values & duplicates  
- Ensure data consistency  

### 🔹 3. Exploratory Data Analysis (EDA)  
- Histograms, scatter plots, boxplots  
- Correlation heatmaps  
- Outlier detection (Cook’s distance, boxplots)  

### 🔹 4. Feature Engineering  
- Dummy encoding for categorical variables  
- Normalization of numerical features  

### 🔹 5. Modeling  
- Train/test split  
- Models trained with **statsmodels** & **scikit-learn**  
- Different experiments:  
  1. OLS with all features  
  2. Reduced OLS with significant predictors  
  3. Box-Cox transformation model  
  4. Encoded categorical OLS  

### 🔹 6. Evaluation & Diagnostics  
- Metrics: **R², RMSE, MSE**  
- Residual tests: Shapiro-Wilk (normality), Breusch-Pagan (homoscedasticity)  
- ANOVA for categorical variables  
- Model comparison using **AIC & RMSE**  

---

## 🎯 Skills Highlighted  

✔️ Data Wrangling (missing values, duplicates, invalid entries)  
✔️ Exploratory Data Analysis (EDA)  
✔️ Feature Engineering & Encoding  
✔️ Outlier Detection (statistical & graphical)  
✔️ Regression Modeling (OLS, assumptions, multicollinearity)  
✔️ Advanced Diagnostics (Box-Cox, ANOVA)  
✔️ Python Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`  

---

## 📊 Results  

- **Model 1** → Baseline OLS (all variables)  
- **Model 2** → Reduced OLS (significant predictors only)  
- **Model 3** → OLS + Box-Cox transformation  
- **Model 4** → OLS with categorical encodings  

🏆 **Best model selected** based on **R², AIC, RMSE** ensuring accuracy and statistical reliability.  

---

## 📌 Importance  

- Supports **automotive pricing strategies**  
- Helps in **market analysis & inventory management**  
- Demonstrates **rigorous regression validation** in applied data science  

---

## ⚙️ Setup & Usage  

### 🔧 Requirements  
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels scikit-learn
```
## ▶️ Run Project

**1.** Place CarPrice_Assignment.csv in project directory

**2.** Open Car_price_prediction.ipynb in Jupyter Notebook/Lab

**3.** Run all cells in sequence

## ✅ Key Takeaways

*Data preprocessing is critical for reliable models

*Always check regression assumptions before interpretation

*Feature engineering & transformations can boost model robustness

*Visualization + statistics = better insights
