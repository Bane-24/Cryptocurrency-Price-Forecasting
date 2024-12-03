# Cryptocurrency Price Forecasting Using Machine Learning

## Overview

This project predicts **Bitcoin prices** using **Long Short-Term Memory (LSTM)** models, leveraging historical data for daily, weekly, and monthly forecasting. By combining machine learning and data analysis techniques, it aims to provide insights into the volatile cryptocurrency market.

---

## Key Features

- **Automated Data Collection**: Historical cryptocurrency data via `cryptocmd` and stock data using `yfinance`.
- **Machine Learning Modeling**: Forecasting using **LSTM** with hyperparameter tuning.
- **Visual Analytics**: Predicted vs. actual prices plotted for better insights.
- **Version Control**: Managed through GitHub for seamless collaboration.

---

## Tech Stack

- **Languages**: Python  
- **Libraries**:  
  - Data Handling: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `tensorflow`, `scikit-learn`, `keras-tuner`  
  - Data Scraping: `cryptocmd`, `yfinance`  
- **Tools**:  
  - Notebook Environment: Google Colab  
  - Version Control: GitHub  

---

## Workflow

1. **Data Collection**:  
   - Bitcoin price data (`cryptocmd`)  
   - S&P 500 stock data (`yfinance`)  
2. **Preprocessing**:  
   - Missing value handling via interpolation.  
   - Feature scaling with `MinMaxScaler`.  
3. **Model Building**:  
   - Time-series forecasting with **LSTM**.
   - Hyperparameter tuning using `RandomizedSearchCV`.
4. **Evaluation**:  
   - Metrics: **R² = 0.90**, **MAE = 1901.04 USD**, **MSE = 7,075,554 USD**.

---

## Results

- **Daily Forecast**: Most accurate with R² = 0.90.
- **Weekly & Monthly Forecast**: Requires more extensive data for improved accuracy.
- **Visualization**: Interactive plots showcasing predicted vs. actual values.

---

## Future Enhancements

- Include external factors such as **social media sentiment** and **interest rates**.
- Improve forecasting with hybrid/ensemble models.

---

Feel free to fork and contribute! For any issues, raise a ticket in the repository.
