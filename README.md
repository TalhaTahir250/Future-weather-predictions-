🌦️ Weather Temperature Prediction Using Machine Learning
🧠 Overview

This project predicts the average daily temperature using historical weather data.
It demonstrates a complete end-to-end machine learning workflow, from data collection via an API to model training, evaluation, and visualization.

The goal is to showcase regression modeling skills and the ability to work with real-world time-series data.

⚙️ Tech Stack

Python 🐍

Pandas, NumPy → data cleaning & manipulation

Meteostat API → for fetching weather data

Matplotlib, Seaborn → data visualization

Scikit-learn → model training, evaluation, and metrics

🧩 Features

✅ Fetch real-time and historical weather data via Meteostat API
✅ Clean and preprocess raw weather data (handle missing values, drop irrelevant columns)
✅ Engineer time-based features (Month, Day, Day_of_Week)
✅ Train and compare multiple regression models:

Linear Regression

Lasso Regression

Random Forest Regressor
✅ Evaluate model performance using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score
✅ Create advanced Actual vs Predicted visualizations for model performance

📊 Dataset

Weather data is collected from the Meteostat API, which provides:

Average, minimum, and maximum temperature

Precipitation

Wind speed

Atmospheric pressure

Time-based features derived from the date column

🚀 Machine Learning Pipeline

Data Collection → Fetch historical data (e.g., 2023–2024)

Data Cleaning → Handle missing/null values, drop unused columns

Feature Engineering → Extract Month, Day, Day_of_Week

Train-Test Split → 80% training, 20% testing

Model Training & Evaluation → Compare Linear, Lasso, Random Forest

Visualization → Actual vs Predicted, trend plots, error distributions
