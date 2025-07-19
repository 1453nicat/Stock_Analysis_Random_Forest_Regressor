# Stock_Analysis_Random_Forest_Regressor

In conclusion, this project demonstrates how to perform a comprehensive stock analysis using historical price data. We started by fetching stock and benchmark data for multiple years and calculated key financial metrics such as volatility, Sharpe ratio, and beta to assess risk and performance. Then, we explored important technical indicators including moving averages, RSI, MACD, and Bollinger Bands to understand price trends and momentum. We visualized these indicators to gain intuitive insights. For predictive modeling, we prepared lagged features and normalized data to train a Random Forest regression model. The model’s predictions were evaluated with Mean Squared Error and visually compared against actual returns, illustrating its ability to capture market behavior to some extent. Overall, this pipeline offers a solid foundation for stock analysis and forecasting by combining fundamental concepts, technical indicators, and machine learning techniques.

# Features  
- Fetches historical price data for stocks and benchmark indices using yfinance  
- Calculates annualized volatility, Sharpe ratio, and beta for risk and performance assessment  
- Computes technical indicators: Simple Moving Averages (SMA), Relative Strength Index (RSI), MACD, Bollinger Bands  
- Visualizes price data and technical indicators with interactive Plotly charts  
- Prepares data for machine learning by creating lagged features and normalizing volume  
- Builds and evaluates a Random Forest regression model to predict daily returns  
- Compares actual vs predicted returns visually and calculates prediction error (MSE)

MIT License
Copyright (c) 2025 *1453nicat*
