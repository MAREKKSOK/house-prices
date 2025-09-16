# House Prices Prediction

This repository contains my solution for the **House Prices: Advanced Regression Techniques** competition on [Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

The goal of the competition is to predict the final prices of houses based on 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa.

---

## Project Structure
- `house_prediction.ipynb` – Jupyter Notebook with data preprocessing, feature engineering, model training and prediction steps.
- `submission.csv` – Output file ready for Kaggle submission (generated from the notebook).

---

## Methods Used
- Data preprocessing with **Pandas & NumPy**
- Handling missing values and categorical variables
- Model training with **XGBoost Regressor**
- Evaluation using **Root Mean Squared Logarithmic Error (RMSLE)**

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/MAREKKSOK/house-prices.git
