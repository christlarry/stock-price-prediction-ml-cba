# Stock Price Prediction using Machine Learning (CBA.AX)

This repository contains an **end-to-end machine-learning framework** for predicting short-term stock price movements of the **Commonwealth Bank of Australia (CBA.AX)** between 2020 and 2024.  
The project was completed as part of **COS60011 – Technology Design Project (Swinburne University, 2025)** and demonstrates how financial factor construction can be combined with machine-learning techniques to produce interpretable, data-driven trading insights.

---

## 🧩 Project Overview
- **Goal:** Predict 1–5 day stock price direction using daily OHLCV data.  
- **Data:** Yahoo Finance historical data (2020 – 2024).  
- **Methods:** Feature engineering, factor selection (LASSO / Elastic Net), and walk-forward validation.  
- **Models:** Logistic Regression, XGBoost, Elastic Net Logit (Scikit-Learn).  
- **Evaluation Metrics:** AUC, F1 Score, Profit Factor, Expectancy, Annualised Return.  
- **Tools:** Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Jupyter Notebook).

---

## 📊 Key Results
- Reduced 9 financial factors to 5 stable predictors via LASSO regularisation.  
- Achieved ~11 % annualised return and Profit Factor > 1.5 under walk-forward back-testing.  
- Stress testing across R/R ratios (1:1 → 3:1) showed expectancy improvement up to ~23 %.  
- Demonstrated reproducible and economically interpretable ML workflow.

---

## 🧠 Files
| File | Description |
|------|-------------|
| **BobLin_StockPricePrediction_ML_Notebook.ipynb** | Full Python code and model workflow |
| **BobLin_StockPricePrediction_ML_NotebookPreview.pdf** | PDF view of the Notebook |
| **Stock_Price_Prediction_ML_Project_BobLin.pdf** | Final technical report and visualisations |

---

## 🚀 Usage
1. Clone this repository:  
   ```bash
   git clone https://github.com/BobLin-AU/stock-price-prediction-ml-cba.git
   cd stock-price-prediction-ml-cba
