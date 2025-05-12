# Sales Forecasting for Samsung Semiconductors

This project was developed as part of the **Global Operations** course at **Inha University** to improve sales predictions for **Samsung Semiconductors**. By learning from past mis-forecasts, we aim to build a transparent and reliable forecasting system that anyone can understand.

---

## 📖 Background

In recent years, Samsung Electronics faced unexpected downturns in its semiconductor division. For example, in Q3 2024 the company warned its profits would fall below market expectations due to delays in its AI chip business and rising competition from Chinese chipmakers ([Reuters](https://www.reuters.com/technology/samsung-electronics-estimates-274-jump-q3-operating-profit-2024-10-07/?utm_source=chatgpt.com)). This led to a rare public apology and leadership reshuffle in the semiconductor unit, as Samsung admitted to underestimating market demand for high-bandwidth memory (HBM) chips ([WSJ](https://www.wsj.com/tech/samsung-electronics-appoints-new-chief-for-chip-business-ed6511b3?utm_source=chatgpt.com)). These mis-forecasts illustrate the challenge of anticipating fast-changing chip demand and price fluctuations.

---

## 🛠️ Models Used

We evaluate a variety of forecasting approaches to find the best fit:

* **Time-series models**

  * Autoregression (AR)
  * ARIMA (AutoRegressive Integrated Moving Average)
  * ARMA (AutoRegressive Moving Average)
  * Simple Exponential Smoothing (SES)
  * Holt–Winters Exponential Smoothing (HWES)
  * Moving Average (MA)

* **Machine-learning regressors**

  * Linear Regression
  * Lasso Regression
  * Ridge Regression
  * Passive Aggressive Regression
  * K-Nearest Neighbors (KNN)
  * Support Vector Machine Regression (SVMR)
  * Decision Trees (CART)
  * Random Forest
  * AdaBoost
  * Bagging
  * Least Angle Regression (LLARS)

---

## 🚀 How It Works

1. **Data Input**
   Historical sales data is loaded (monthly or quarterly figures).

2. **Data Cleaning**
   Missing values, outliers, and seasonal patterns are handled automatically.

3. **Model Testing**
   Each of the models listed above is trained and evaluated on past data. We calculate accuracy using RMSE (Root Mean Squared Error).

4. **Ensemble Forecast**
   The top-performing models are combined to balance individual strengths and reduce overall error.

5. **Output**
   A clear sales forecast is generated for the requested period, along with simple accuracy metrics.

> **Non-technical summary**: We feed in past sales, let the computer try different proven forecasting recipes, pick the best mix, and get a reliable sales forecast to help Samsung avoid future surprises.

---



