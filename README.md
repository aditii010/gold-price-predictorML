
# Gold Price Predictor using Regression

This project predicts the price of gold based on various financial indicators using regression models. The notebook performs data preprocessing, exploratory data analysis, model training, and performance evaluation to determine the most accurate model for gold price prediction.

 Overview

The notebook implements multiple regression techniques to predict gold prices. It compares models such as Linear Regression, Random Forest Regressor, and others to evaluate which model best fits the dataset.

Models tested:

* Linear Regression
* Random Forest Regressor

 Dataset

**File:** `gld_price_data.csv`

Source: [Kaggle - Gold Price Data](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data)
Description: Contains daily data of gold prices (GLD) and related financial indicators such as SPX, USO, SLV, and EUR/USD.


# Workflow

1. Data Import & Cleaning – Loading the dataset, checking for null values, and preparing it for analysis.
2. Exploratory Data Analysis (EDA) – Understanding correlations between features and the target variable (GLD).
3. Data Visualization – Using heatmaps, pairplots, and distribution graphs to study relationships and patterns.
4. Feature Selection – Selecting input variables that strongly influence gold prices.
5. Model Training – Implementing and training multiple regression models using Scikit-learn.
6. Evaluation – Comparing models using metrics like R² score and Mean Absolute Error (MAE).
7. Prediction – Testing the trained model with sample data to predict gold prices.

# Results

* Best Model: Random Forest Regressor
* R² Score: 0.989
* Mean Absolute Error (MAE): 1.04

# How to Run

Open directly on Google Colab:
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aditi-sikarwar/gold-price-predictor/blob/main/GLD_predictor.ipynb)

# Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

# Future Enhancements

* Deploy as an interactive Streamlit web app
* Integrate real-time gold price APIs
* Add time series forecasting (ARIMA / LSTM) for long-term predictions

## 👩‍💻 Author

**Aditi Sikarwar**
📍 Electronics and Computer Engineering Student
🔗 [LinkedIn](https://www.linkedin.com/in/aditi-sikarwar/) | [GitHub](https://github.com/aditii010)

