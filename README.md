## 📊 Project Description

This project focuses on forecasting daily page views for over 145,000 Wikipedia articles across different languages and regions, spanning 550 days. The objective is to build an end-to-end time series forecasting pipeline that helps **AdEase**, an AI-driven advertising platform, **optimize ad placement by predicting future traffic patterns**.

Using powerful time series models like **ARIMA**, **SARIMAX** (with exogenous campaign data), and **Facebook Prophet**, we analyze and forecast user behavior on Wikipedia to uncover patterns, seasonality, and anomalies. The multilingual and multiregional nature of the data allows for targeted insights into how ads might perform in specific demographics or content categories.

### Key components of this project include:

- **Exploratory Data Analysis (EDA):** Understanding the structure and trends in Wikipedia traffic data.
- **Data Preprocessing:** Parsing page metadata (language, access type, origin), handling missing values, and formatting time series.
- **Stationarity Checks:** Using ADF tests, differencing, and decomposition to prepare data for modeling.
- **Modeling:** Building and tuning ARIMA, SARIMAX (with campaign events for English pages), and Prophet models.
- **Forecasting & Evaluation:** Generating forecasts for multiple series, evaluating performance using MAPE, and comparing results across languages.

The ultimate goal is to support businesses in making **data-driven advertising decisions**, ensuring **maximum engagement at minimum cost**, through intelligent view forecasting and campaign planning.
