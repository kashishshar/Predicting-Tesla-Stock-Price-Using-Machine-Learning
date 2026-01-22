# Tesla Stock Price Prediction

![CI](https://github.com/kashishshar/Predicting-Tesla-Stock-Price-Using-Machine-Learning/actions/workflows/python-ci.yml/badge.svg)
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-brightgreen)
![XGBoost](https://img.shields.io/badge/XGBoost-Model-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Overview
This project focuses on predicting whether the **closing price of Tesla (TSLA) stock will increase on the next trading day** using historical stock market data.  
The problem is formulated as a **binary classification task**, where machine learning models are used to generate a potential **buy signal** based on past price movements.

---

## Live Application
 **Streamlit App:**  
https://tesla-stock-price-prediction-project.streamlit.app/

---

## Dataset
The dataset contains **daily Tesla stock price data from January 2010 to December 2017**, sourced from historical market records.

### Key Features:
- **Open** – Opening price of the stock  
- **High** – Highest price of the day  
- **Low** – Lowest price of the day  
- **Close** – Closing price of the day  
- **Volume** – Number of shares traded  

---

## Feature Engineering
To enhance model performance, the following features were engineered:
- **Open–Close Spread** – Difference between opening and closing price  
- **High–Low Spread** – Indicator of daily volatility  
- **Quarter-End Indicator** – Binary flag for quarter-end trading days  

---

## Machine Learning Models Used
- Logistic Regression  
- Support Vector Machine (SVM)  
- XGBoost Classifier  

These models were trained to predict whether the next day’s closing price would be higher than the current day.

---

## Model Evaluation
- **Train–Validation Split:** 90% training, 10% validation  
- **Evaluation Metric:** ROC–AUC Score  

ROC–AUC was chosen to effectively measure classification performance, especially for financial prediction tasks.

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Streamlit  
- Matplotlib, Seaborn  

---

## Project Contribution
This project was developed as a **group project**.  
My contributions include:
- Data preprocessing and feature engineering  
- Model selection and evaluation strategy   
- Documentation and project deployment support  

> This repository is forked from the original group project to showcase individual understanding and contributions.

---

## Future Improvements
- Add technical indicators (RSI, MACD, Moving Averages)  
- Use time-series–based models (LSTM, GRU)  
- Extend dataset with recent stock data  
- Improve prediction confidence and explainability  
