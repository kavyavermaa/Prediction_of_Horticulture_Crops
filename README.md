# Horticulture Crop Production and Export Forecast (2025–2035)

This repository contains a time series forecasting analysis of horticultural crop production and export trends in India from 2025 to 2035. The study applies ARIMA and Exponential Smoothing State Space (ETS) models to major fruit crops including banana, mango, grape, papaya, pineapple, apple, orange, and guava.

## Overview

- **Forecasting Models**: ARIMA and ETS
- **Historical Data Range**: 1961–2023
- **Forecast Period**: 2025–2035
- **Data Source**: [FAO.org](https://www.fao.org)

## Key Findings

- ETS models outperform ARIMA in predictive accuracy.
- Strong production growth is expected in bananas, mangoes, and grapes.
- Export trends show rising demand, with notable growth in banana and grape exports.
- Forecasting model performance evaluated using RMSE, MAE, and MAPE metrics.

## Methodology

- **Models**:
  - ARIMA (Autoregressive Integrated Moving Average)
  - ETS (Error, Trend, Seasonality configurations)
- **Model Evaluation Criteria**: AIC, RMSE, MAE, MAPE
- **Validation Period**: 2016–2020

## Applications

- Strategic planning for policymakers and agri-businesses
- Crop production and export decision support
- Long-term investment planning in horticulture

## Repository Structure

- `data/`: Historical and processed datasets
- `notebooks/`: Model development and evaluation notebooks
- `models/`: Trained model files
- `results/`: Forecast outputs and evaluation metrics
- `report/`: PDF summary of the full research

## Future Work

- Integration of hybrid models combining ARIMA and machine learning
- Inclusion of climate, economic, and policy-based variables
- Expansion to cover other horticulture crops like spices and vegetables

## License

This project is licensed under the MIT License.
