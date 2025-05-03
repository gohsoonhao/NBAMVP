# 🏀 NBA MVP Prediction (ML Project)

This project uses machine learning to predict NBA MVP vote shares based on player and team statistics. The goal is to understand which factors consistently influence MVP voting and to generate data-driven predictions for each season.

I break down the full process in this Medium article:  
👉 [Predicting the NBA MVP Race Using Machine Learning](https://medium.com/@soonhaogoh/from-stats-to-superstars-using-data-science-to-predict-the-nba-mvp-e4d1d8474079)

## 🔍 Project Summary

- **Target:** MVP Share (vote points / max possible points)  
- **Data:** Player box score stats, team wins, availability, and standings  
- **Years Covered:** 20 NBA seasons  
- **Source:** [Basketball Reference](https://www.basketball-reference.com/)

## ⚙️ Models Used

An ensemble model combining:
- Linear Regression  
- Gradient Boosting  
- XGBoost  

Combined using a **Voting Regressor** to balance individual model strengths and improve overall prediction quality.

