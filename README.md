# Binance-Arbitrage-Scanner-and-Auto-Trader
This is an arbitrage scanner and auto trading bot created using python code, this bot works for Bybit, Binance, Kucoin, OKX and Bitget, you just have to change the exchange you're using

EXPLANATION:-
The bot fetches the order book for the trading pairs (e.g., BTC/USDT).
It checks for triangular arbitrage opportunities by comparing bid and ask prices.
If a profitable opportunity is found, it executes the arbitrage by placing buy and sell orders.
Adjust the parameters (e.g., trading pair, profit threshold) as needed. The minimum profit threshold is 0.015 which is 1.5% after fees. 

The script continuously scans for triangular arbitrage opportunities in all high-volume trading pairs on Binance. The script adheres to this specified requirements:

Minimum profit threshold: 1.5%
Minimum order size: $10
Check frequency: Every 1 minute 

