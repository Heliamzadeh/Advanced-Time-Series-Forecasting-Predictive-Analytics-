# Advanced-Time-Series-Forecasting-Predictive-Analytics-

# Advanced Time Series Forecasting & Predictive Analytics  
**Statistical Learning · Forecasting Models · Model Evaluation & Analytics**

---

## Project Overview

This project implements a **comprehensive time series forecasting framework** using real-world datasets from transportation, retail, and macroeconomic domains. The objective is to **analyze temporal structure, model seasonality and trend, and rigorously compare forecasting methodologies** under realistic train–test evaluation settings.

The project emphasizes **diagnostic analysis, model adequacy testing, and forecast accuracy comparison**, reflecting professional practices in **forecasting, business analytics, and applied econometrics**.

---

## Problem Context

Accurate forecasting is critical for:
- Transportation demand planning
- Retail inventory and sales forecasting
- Macroeconomic monitoring and policy analysis

However, time series data often exhibit:
- Strong **trend and seasonality**
- Autocorrelation and persistence
- Non-stationarity
- Structural variability over time

This project addresses these challenges by:
- Diagnosing temporal patterns using ACF/PACF
- Applying a wide range of forecasting models
- Evaluating forecasts using out-of-sample accuracy metrics
- Selecting models based on **both performance and theoretical suitability**

---

## Datasets & Use Cases

### 1. Boston Bluebike Daily Trips
- Daily bike-sharing trips near MIT (2015–2018)
- Clear upward trend and strong annual seasonality
- Used to study:
  - Autocorrelation structure
  - Naive forecasting limitations
  - Residual diagnostics

### 2. Australian Liquor Retail Sales
- Monthly retail liquor sales data
- Strong multiplicative seasonality
- Used to compare:
  - Simple benchmarks
  - Smoothing methods
  - ETS models

### 3. Consumption Expenditure 
- Quarterly macroeconomic data (1970–2016)
- Focus on consumption growth
- Used to evaluate:
  - ARMA / ARIMA / SARIMA models
  - Structural time series modeling

---

## Methodology

### 1. Exploratory Time Series Analysis
- Time series visualization
- Trend and seasonality identification
- Multiplicative decomposition
- Structural pattern assessment

### 2. Autocorrelation Diagnostics
- **ACF (Autocorrelation Function)**
  - Long-memory detection
  - Seasonality identification
- **PACF (Partial Autocorrelation Function)**
  - Short-run dependency structure
  - AR order identification

These diagnostics guide appropriate model selection.

---

## Forecasting Models Implemented

### Benchmark Models
- Naive Forecast
- Average (Mean) Forecast
- Drift Method

### Smoothing Methods
- Simple Moving Average (SMA)
- Simple Exponential Smoothing (SES)

### State-Space & Exponential Models
- ETS (Error–Trend–Seasonal)

### Stochastic Time Series Models
- ARMA
- ARIMA
- SARIMA (Seasonal ARIMA)

All models are evaluated using **strict train–test splits**, ensuring valid out-of-sample assessment.

---

## Model Evaluation

### Accuracy Metrics
- **MAPE (Mean Absolute Percentage Error)**
- Forecast error diagnostics
- Residual analysis and white-noise testing

### Key Findings
- Naive and average methods perform poorly on trending and seasonal series
- Smoothing and ETS methods significantly improve accuracy in retail data
- ARIMA-based models outperform simple benchmarks in macroeconomic forecasting
- Model suitability depends strongly on **data structure**, not model complexity alone

---

## Residual Diagnostics
- Time plot inspection
- Residual ACF analysis
- Normality and randomness assessment

These diagnostics ensure forecasts are not only accurate but **statistically valid**.

---

## Technical Stack

### Languages & Tools
- **R**

### Libraries
- `fpp2`
- `forecast`
- `smooth`
- `readxl`
- `ggplot2`

### Core Skills Demonstrated
- Time series decomposition
- Stationarity assessment
- Forecast model selection
- Residual diagnostics
- Forecast accuracy evaluation
- Applied statistical learning

---

## Project Structure
```text
├── Assignment 3_Completed.docx
├── MGSC_Assignment3_Example1.R
├── MGSC_Assignment3_Example2.R
├── MGSC_Assignment3_Example3.R
├── README.md
