DEMA + SUPERTREND Strategy BTC bot. Built for coinbase but could work with more. 
Right now there is a version operating with the supertrend at 1 minute time frame (updating every 1 min) and DEMA at 200 days timeframe, and a copy version that is running supertrend at 15 minute time frame. 
Period of 12 and multiplier of 3 for the supertrend settings. 

Working Version: working-version.py is the most up to date version of the bot. Supertrend on 15 minutes timeframe, and supertrend calculation bugs fixed.


Before Running/Installation - 
Set Coinbase REST API keys (The non pro/advanced one), in all three spots. 
pip install all required libraries. 



IMPROVEMENTS TO BE MADE - 
  1. Create a way to properly backtest the exact strategy being used. Need historical data by the hour for the DEMA, and need historical data by the minute for supertrend. Stoploss ordrs in backtesting?  
 
  3. Adding some sort of RSI index to the buy and sell conditions. 
