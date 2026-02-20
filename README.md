📌 Demand Forecasting Project


🔹 Project Overview


This project focuses on monthly demand forecasting using a dataset of demand values from 2020–2021.
The goal is to build models that predict future demand, helping businesses plan inventory, staffing, and logistics.


I implemented multiple approaches:
- Machine Learning Models: Linear Regression, Random Forest
- Time-Series Models: ARIMA, Prophet
This demonstrates both technical versatility and business relevance.

🔹 Dataset
- Columns:
- date_column: Monthly timestamps (Jan 2020 – Dec 2021)
- demand: Demand values (numeric)
- Size: 24 rows (2 years of monthly data)
- Source: Synthetic dataset created for portfolio demonstration

🔹 Workflow
- Data Loading & Cleaning
- Robust function to handle missing values, strip column names, and rebuild date column if needed.
- Checked for duplicates, missing values, and ensured correct datatypes.

- Exploratory Data Analysis (EDA)
- Line chart of demand trend.
- Boxplot for outlier detection.
- Growth rate calculation.
- Feature Engineering
- Lag features (lag1, lag2, lag3).
- Rolling averages (3-month mean).
- Time-based features (month, year).
- Modeling
- Linear Regression → baseline model.
- Random Forest → non-linear relationships, feature importance.
- ARIMA → classical statistical forecasting.
- Prophet → modern, interpretable forecasting with trend + seasonality.
- Evaluation
- Metrics: MAE, RMSE, MAPE.
- Random Forest achieved ~85% accuracy.
- Visualization
- Actual vs Predicted demand (line chart).
- Feature importance (bar chart).
- Prophet component plots (trend + seasonality).

🔹 Key Results
- Random Forest outperformed Linear Regression with lower error rates.
- ARIMA provided interpretable forecasts extending beyond 2021.
- Prophet revealed clear seasonal patterns and long-term growth trends.

🔹 Business Impact
- Forecasting demand helps businesses avoid stockouts, optimize inventory, and plan production.
- Combining ML and time-series models provides both accuracy and interpretability.
- This project demonstrates how data analysis translates into real business decisions.

Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels, Prophet)
- Jupyter Notebook for development and visualization
- GitHub for portfolio presentation

