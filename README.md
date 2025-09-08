# NASDAQ-Futures-True-Range-Forecasting
A programme designed to forecast the True Range of NASDAQ Futures

NOTE: This script is for educational and research purposes only. It should not be considered financial advice.
NOTE: The forecasted ranges/percentages may slightly differ from official exchange data, as yfinance was used.

This script downloads 5 years of daily NASDAQ-100 futures data from YahooFinance and calculates the True Range (TR) to measure market volatility. It then applies a 60-day rolling average to forecast the expected range for the next trading day, displaying results in both points and percentage terms. The project provides a simple way to explore volatility forecasting and includes a visualization of daily TR compared to the rolling forecast. True Range was used because it is better than simply (High−Low) when gaps matter, which is relevant for futures and overnight moves. A 60-day forecast period is a medium-term smoothing period that balances responsiveness and noise reduction. Below is an example of the ran code. I found the forecasting helped with identifying profitable trading setups for my discretionary trading strategies.


<img width="1470" height="394" alt="Screenshot 2025-09-08 at 17 54 08" src="https://github.com/user-attachments/assets/916bde18-964d-407a-839c-f5e6da70840f" />
