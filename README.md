# FINE3300-Stock-Plots
This repository contains jupyter files that plot stock data values for 'IVV' and 'AAPL'

## 📈 First Plot
  - The first plot uses the yfinance and mplfinance libraries
  - It plots a candlestick chart that displays the opening price, high price, low price, and close price for IVV with volume displayed in bar graph format

## 📈 Second Plot
  - The second plot uses Pandas and Matplotlib
  - It plots a line chart that shows the stock price of Apple in its first 250 trading days
  - A moving average is also plotted as an average of the 20 previous prices (not inclusive of current day)
  - Lastly, the lower and upper bands are plotted as 2 standard deviations below and above the moving average, respectively
