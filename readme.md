# TradingView Bots
A list of bots for trading view, currently available:
1) Sma_bot

### Sma_bot

This is a simple trading bot for TradingView that uses the Simple Moving Average (SMA) indicator to generate buy and sell signals.
#### Installation
1) Open your TradingView chart
1) Click on the Pine Editor icon
1) Copy and paste the code from above into the Pine Editor
1) Click on "Save" and give your script a name
You can now add the script to your chart and start using it.
#### Inputs
1) Length: The length of the SMA indicators (default 14)
1) Oversold Threshold: The oversold threshold for the Stochastic RSI (default 35)
1) Overbought Threshold: The overbought threshold for the Stochastic RSI (default 65)
#### Outputs
Buy signals: Green arrows pointing up

Sell signals: Red arrows pointing down

#### Strategy
The bot uses two Simple Moving Averages (SMAs) to generate its signals. When the short-term SMA crosses above the long-term SMA, a buy signal is generated. When the short-term SMA crosses below the long-term SMA, a sell signal is generated. The bot will automatically enter a long or short position when these signals occur.

This bot is intended for educational purposes and is not guaranteed to make a profit. As always, make sure to backtest and thoroughly evaluate any trading strategy before using it with live capital.

