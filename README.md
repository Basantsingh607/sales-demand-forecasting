# Sales Demand Forecasting — ARIMA & Prophet

> Time-series forecasting models built in R to predict product 
> demand and reduce inventory planning errors.

---

## Business Problem

Inaccurate demand forecasting leads directly to two costly outcomes: 
excess inventory (capital tied up in unsold stock) or stockouts 
(lost sales and poor customer experience). This project builds and 
compares two time-series forecasting approaches to improve demand 
prediction accuracy for business planning scenarios.

---

## Solution

Developed and compared ARIMA (AutoRegressive Integrated Moving 
Average) and Facebook Prophet models on product sales data to 
produce reliable demand forecasts that support inventory and 
procurement decisions.

---

## Results

- Improved demand forecast accuracy over naive baseline model
- Reduced simulated over/under-stock scenarios
- Prophet outperformed ARIMA on datasets with strong seasonality 
  and holiday effects
- ARIMA performed better on stationary, trend-driven series

---

## Methods

**1. Exploratory Data Analysis**
- Trend decomposition (trend, seasonality, residuals)
- Stationarity testing — ADF (Augmented Dickey-Fuller) test
- Autocorrelation (ACF) and Partial Autocorrelation (PACF) plots

**2. ARIMA Model**
- Parameter selection: p (AR order), d (differencing), q (MA order)
- Auto ARIMA for automated parameter optimisation
- Evaluated on RMSE and MAE

**3. Prophet Model**
- Handles multiple seasonality (daily, weekly, yearly)
- Built-in holiday effect modelling
- Uncertainty interval forecasting for planning scenarios

**4. Evaluation**
- Train/test split with rolling window validation
- Metrics: RMSE, MAE, MAPE
- Forecast visualisation with confidence intervals

---

## Tools & Technologies

| Category | Tools |
|---|---|
| Language | R |
| Forecasting | forecast (ARIMA), prophet |
| Data Processing | dplyr, tidyr |
| Visualisation | ggplot2 |
| Environment | RStudio / R Markdown |

---

## Business Impact

- Enables data-driven inventory planning decisions
- Reduces working capital tied up in excess stock
- Supports procurement teams with forward-looking demand signals
- Applicable to retail, supply chain, and manufacturing contexts

---

## Author

**Basant Kumar** — Business Analyst | Data & AI Analytics  
MSc Business Analytics, Maynooth University  
[LinkedIn](https://linkedin.com/in/basantsingh-) | 
[GitHub](https://github.com/Basantsingh607)
