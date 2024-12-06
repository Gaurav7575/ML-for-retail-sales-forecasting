# ML-for-retail-sales-forecasting
### Note - Uploading a single code file is not feasible for this project as it involves the use of SPSS and multiple interdependent code files. To provide better clarity, I have included a detailed report.

# Forecasting Retail Success: A Data-Driven Approach to Sales Prediction for Corporación Favorita

## Overview

This project focuses on predicting retail sales for Corporación Favorita, a leading grocery retailer in Ecuador. Leveraging a comprehensive dataset from Kaggle, the project employs advanced machine learning and time series models to forecast sales for the company's top product families across 54 stores. By incorporating external factors like holidays and oil prices, the project provides actionable insights to optimize inventory management, marketing strategies, and supply chain operations.

## Features

- Forecasts sales for top 5 product families and stores.
- Incorporates external factors like holidays, events, and oil prices.
- Explores advanced predictive models including:
  - ARIMA
  - Random Forest
  - XGBoost
  - Long Short-Term Memory (LSTM)
- Provides store-level performance tracking.

## Data Sources

The dataset includes:
- **Sales Data:** Store-level sales data (2013-2017).
- **Oil Prices:** Daily oil prices relevant to Ecuador’s economy.
- **Holiday Data:** Information on holidays and events affecting sales.
- **Transactions:** Store-specific transaction volumes.

## Methodology

1. **Data Preprocessing:**
   - Merging datasets with time-based and external features.
   - Handling missing values using techniques like linear interpolation.
2. **Exploratory Data Analysis (EDA):**
   - Identifying seasonality, trends, and correlations.
   - Assessing the impact of oil prices and holidays on sales.
3. **Model Training:**
   - Baseline models (ARIMA) for time series forecasting.
   - Machine learning models (Random Forest, XGBoost, LSTM) for handling external features.
4. **Evaluation Metrics:**
   - Root Mean Squared Error (RMSE)
   - Mean Absolute Error (MAE)

## Key Insights

- Strong seasonal patterns identified around holidays and weekends.
- Significant correlation between oil prices and sales for non-essential product families.
- XGBoost outperformed other models in accuracy and computational efficiency.



## Results

- The XGBoost model achieved the best performance with an R-square of 0.91 for Dairy products.
- Forecasts for the next 16 days provide actionable insights for inventory and resource allocation.

## Contributions

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request for review.

