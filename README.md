# Gold-price-prediction
Gold Price Prediction using XGBoost with Macroeconomic Indicators for Financial Forecasting

Overview

This project focuses on predicting gold prices (GLD) using advanced machine learning techniques. The model leverages macroeconomic indicators such as stock market index (SPX), oil prices (USO), silver prices (SLV), and currency exchange rates (EUR/USD) to perform accurate financial forecasting.

An XGBoost Regressor, a powerful ensemble learning algorithm, is used to capture complex non-linear relationships between these variables.

Objectives
- Predict gold prices using economic indicators
- Apply advanced ML techniques (XGBoost)
- Analyze feature importance affecting gold prices
- Build a scalable predictive model for financial analysis

Dataset
The dataset contains the following features:
- SPX – S&P 500 Index
- USO – Oil Price
- SLV – Silver Price
- EUR/USD – Currency Exchange Rate
- GLD – Gold Price (Target Variable)
- Date – Timestamp of observation

Technologies Used
- Python 
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Matplotlib

Model Used
XGBoost Regressor
- Ensemble boosting technique
- Handles non-linear relationships effectively
- Provides feature importance insights
- High accuracy compared to traditional models

Methodology
1. Data preprocessing and cleaning  
2. Feature engineering (Year, Month extraction)  
3. Train-test split  
4. Model training using XGBoost  
5. Performance evaluation (MAE, R² Score)  
6. Feature importance visualization

Results
- Achieved high prediction accuracy using XGBoost
- Identified key influencing factors such as silver price and stock index
- Demonstrated improved performance over baseline models like Linear Regression

 Future Enhancements
- Implement LSTM for time-series forecasting
- Deploy model using Streamlit web app
- Hyperparameter tuning for improved performance
- Real-time gold price prediction integration

Conclusion

This project demonstrates how machine learning can be effectively applied to financial markets. By leveraging advanced algorithms like XGBoost, we can model complex relationships and make accurate predictions for gold prices.

