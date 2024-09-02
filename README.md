# Early Detection and Prediction of Liquidation Cascades in Cryptocurrency Markets
This repository contains a master’s thesis focused on predicting Bitcoin futures liquidation cascades using machine learning models. The study combines GARCH, HAR, and LSTM models, leveraging hourly data from 2021 to 2024. It aims to provide early warnings and mitigate investor losses. Please cite this work appropriately if used.

## Abstract

	•	Predicts liquidation cascades in Bitcoin futures using hourly market data from January 2021 to July 2024.
	•	Aims to protect investors by providing early warnings against significant losses.
	•	Analyzes key market indicators such as futures-to-spot price ratio, CVD, funding rate, open interest, volume, and price     fluctuations.
	•	Incorporates Ethereum market data to enhance prediction accuracy.
	•	Employs advanced feature selection methods like correlation analysis and XGBoost feature importance.
	•	Uses HAR, GARCH, GJR-GARCH, and HAR-GARCH models for volatility estimation.
	•	Integrates insights into an LSTM model for accurate Bitcoin price trend predictions.

## Introduction

	•	Topic Overview: High volatility characterizes cryptocurrency markets, posing substantial risks and opportunities.
	•	Research Problem: Focuses on early detection of liquidation cascades in BTCUSDT pairs to mitigate investor losses.
	•	Thesis Structure:
	•	Literature review on volatility and liquidation cascades.
	•	Methodology for data collection and model application.
	•	Conclusion on model effectiveness.
	•	Future developments to improve predictive accuracy.
 
## Methodology

### Data Description & Initial Feature Augmentation

	•	ETF Data Creation
	•	Cumulative Volume Delta Calculation
	•	Liquidation Cascades Description & Creation
	•	Logarithmic Returns Calculation
	•	Volatility Calculation

### Feature Selection

	•	Correlation Coefficient
	•	XGBoost Feature Importance
	•	Permutation Feature Importance
	•	Mutual Information Regression
	•	Multicollinearity Detection via Heat Map

### In-Depth Analysis of Critical Features

	•	BTC Coin Volume
	•	BTC Open Interest
	•	BTC Funding Rate
	•	Futures BTC CVD
	•	Futures-to-Spot Price Ratio
	•	BTC ETF Dates
	•	General Findings and Discussion

### Feature Augmentation

	•	Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF)
	•	Granger Causality Test
	•	Lagged Cross-Correlation Analysis
	•	Final Selection of Predictive Features

### Machine Learning Models

	•	HAR Model
	•	GARCH Models
	•	Model Creation (GARCH, HAR-GARCH, GJR-GARCH)
	•	Long Short-Term Memory (LSTM)

## Conclusion

	•	Robust models were developed to predict liquidation cascades.
	•	Feature engineering and machine learning techniques were employed to create the models.
	•	HAR, GARCH, and LSTM models played a crucial role in predicting market volatility and liquidation events.
	•	The GJR-GARCH and LSTM models demonstrated the best performance.
	•	A hybrid model was created by using HAR and GJR-GARCH predictions within the LSTM.

## Future Developments

	•	Enhance model accuracy, especially during extreme market conditions.
	•	Explore additional features like option data.
	•	Combine traditional models with advanced neural networks (e.g., LSTM).
	•	Incorporate sentiment analysis and external factors for more robust predictions.

## Dataset

	•	Features extracted from VeloData API. (https://velo.xyz)
	•	Key features include volume, open interest, funding rate, and price ratios.


This project is intended for educational and research purposes. If you use any part of this research in your work, please cite it properly.
