# Australia-s-food-retail-turnover-trends
Overview

This project analyzes and forecasts turnover trends within the Australian food retail trade sector using time series modeling techniques.
The dataset, “FoodRetailTurnover.csv”, was extracted from the Monthly Retail Business Survey and includes data from:

700 large and 2,700 small businesses

Covering supermarkets, grocery stores, convenience stores, liquor retailing, and specialized food retailing (e.g., meat, fish, fruit, and vegetable shops)

The dataset spans April 1982 – August 2022 with monthly observations (in $Million).
The project aims to forecast turnover for the next 12 months (Sept 2022 – Aug 2023).

🎯 Objectives

Build a robust time series forecasting model (SARIMA) to predict food retail turnover

Compare performance with two baseline models:

Random Walk

Last Value (Naïve)

Apply seasonal adjustment techniques to mitigate bias from recurring patterns

Evaluate model performance using Mean Squared Error (MSE)

🧰 Tools & Technologies

Python (R Studio) – Time series analysis and forecasting

Pandas, NumPy – Data preprocessing

Statsmodels – SARIMA modeling

Matplotlib / Seaborn – Visualization

GitHub – Version control and documentation

📈 Data Summary
Variable	Description
date	Monthly observation dates (1982–2022)
turnover	Turnover in $Million
Data size	485 monthly records
Missing values	None
Format issue	Date variable initially not in correct format (converted to datetime)
📊 Data Insights

Clear seasonal patterns observed (e.g., spikes during holiday periods)

Data shows non-normality and non-stationarity, requiring transformations

Seasonal adjustments applied to improve model performance

🧩 Modeling & Evaluation

SARIMA model used as the primary forecasting approach

Evaluated against Random Walk and Last Value baseline models

Mean Squared Error (MSE) used as the evaluation metric

SARIMA model achieved the lowest MSE, demonstrating strong predictive performance

⚖️ Scope, Limitation, and Application

The SARIMA model assumes future patterns will resemble historical data, which limits its ability to capture sudden disruptions (e.g., pandemics, recessions, or policy shifts).
However, it provides a reliable forecasting baseline for business and policy planning in the food retail sector.

🔍 Transparency and Accountability

Evaluation metric (MSE) included for quantifiable accuracy

Full documentation of:

Data preprocessing

Model selection

Validation and performance comparison

💡 Conclusion & Recommendations

The SARIMA model effectively captures the time series components, outperforming baseline models in accuracy.
Key recommendations include:

Continuous monitoring and model recalibration

Periodic reassessment to account for new data

Integration of external economic indicators to enhance forecast accuracy
