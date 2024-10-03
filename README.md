# Tesla Stock Alert & News SMS Bot

This Python project tracks Tesla's stock price and alerts you with the latest price change and relevant news articles if the price fluctuates more than 1%. The project uses Alpha Vantage's stock market data, NewsAPI for fetching news, and Twilio for sending SMS alerts directly to your phone.

## Features

- Fetches daily stock prices for Tesla (TSLA) from Alpha Vantage.
- Calculates the percentage difference between the closing prices of two consecutive days.
- If the price difference exceeds 1%, it fetches the latest news articles for Tesla Inc. from NewsAPI.
- Sends an SMS containing the stock price change and top 3 related news headlines using Twilio.
