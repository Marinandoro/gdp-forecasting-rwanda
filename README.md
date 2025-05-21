
## Stochastic Modeling and Forecasting of Rwanda’s GDP: A Comparative Study of ARIMA and Geometric Brownian Motion.

This repository contains the implementation of a comparative study on modeling and forecasting Rwanda’s Gross Domestic Product (GDP) using two approaches: **Autoregressive Integrated Moving Average (ARIMA)** and **Geometric Brownian Motion (GBM)**. The goal is to assess which model better captures the growth dynamics of Rwanda's economy and provides more accurate forecasts.

### 📌 Motivation

Understanding and predicting a country’s economic growth is very important and useful for planning, investment, and policy-making. Rwanda has experienced notable growth in recent years, but detailed model-based forecasting studies on its GDP are still limited. This project aims to fill that gap by applying and comparing two different forecasting models using historical GDP data from Rwanda.

### 📊 Our methodology

- 1. ARIMA (Autoregressive Integrated Moving Average)
A widely used time-series model suited for linear and stationary data. ARIMA captures past trends and autocorrelations to forecast future values.
- 2. GBM (Geometric Brownian Motion)
A stochastic process that assumes continuous growth with randomness. It is often used in finance and offers an alternative way to model economic variables with uncertain dynamics.

### 📈 Conclusions

**ARIMA** performed well for capturing stable, short-term trends while, **GBM** provided a continuous and random growth path, which better reflected volatility in long-term forecasts. A visual and numerical comparison of the two models is included in the `results/` folder and in both notebooks.
