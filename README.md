# Data Analytics Projects
This repository contains two data analytics projects focused on applying statistical modelling, machine learning, and optimisation techniques to real-world problems.

# Projects Overview 

## Stock Portfolio Optimisation
### Objective
To analyse historical stock data and develop an optimised investment portfolio based on predicted returns and risk.

### What was done
- Analysed ~1000+ US stocks over 26 years of historical data
- Cleaned data by handling large amounts of missing values using time-series imputation
- Performed exploratory data analysis (EDA) to identify trends, growth, and volatility
- Built multiple models (Linear, Ridge, Lasso, ARIMA, Random Forest, LSTM) for stock price forecasting
- Evaluated models using R² and Mean Squared Error
- Selected the best-performing model (Ridge Regression)
- Constructed low-risk and high-risk portfolios based on predicted returns and volatility

### Key Outcome 
- Successfully developed optimised portfolios tailored to different risk levels
- Demonstrated how data-driven strategies can support investment decision-making


## Solar Farm Optimisation 
### Objective
To forecast energy demand and solar power generation, and optimise energy scheduling to reduce costs.

### What was done
- Analysed time-series data for electricity demand, solar generation, and weather conditions
- Cleaned and processed datasets, including handling missing values and restructuring time-series data
- Engineered features such as lag variables, rolling averages, and seasonal indicators
- Built forecasting models (LightGBM, ARIMA) for energy demand and solar production
- Evaluated model performance using MAE, RMSE, and R²
- Developed an optimisation model using Gurobi to schedule energy usage and battery storage

### Key Outcome 
- Achieved ~13% reduction in energy costs
- Reduced peak electricity demand significantly through optimised scheduling
- Demonstrated integration of forecasting + optimisation in a real-world energy system

