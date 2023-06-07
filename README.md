# TradingBOT
Objectives:

To develop an algorithmic trading bot that trades a specified stock.
To implement a simple trading strategy based on the 20-day moving average of the stock price.
To incorporate risk management through ensuring sufficient account equity before buying.
To handle exceptions and errors effectively during the trading process.
Description:

This Python-based algorithmic trading bot uses the Alpaca API for data retrieval and order execution. The trading strategy is simple: it buys when the stock price is lower than the 20-day moving average and sells when it is higher.

For risk management, the bot ensures that the account has enough buying power before attempting to buy. Additionally, it checks for an existing position before executing a sell order. The bot also implements basic error handling to deal with potential issues that might occur during the trading process.
