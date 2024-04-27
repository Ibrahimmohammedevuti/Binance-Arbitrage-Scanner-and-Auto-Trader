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

CHANGELOG V3

Here’s what each feature on version 3 does:

Logging and Alerts:
- The script logs events (opportunities found, executed trades, errors) to a file named arbitrage_bot.log.

- When an opportunity arises, it sends a Telegram alert with details.

- If an error occurs, it logs the error and sends a Telegram alert.

  
Dynamic Order Sizing:
The order size is calculated dynamically based on available balance or account equity.

Risk Management:
Risk management features are not explicitly implemented in this script, but you can add them based on your risk tolerance (e.g., stop-loss orders).

User Configuration:
The script currently uses hardcoded parameters. You can modify it to read parameters from a configuration file or command-line arguments.

Error Handling and Retry Mechanism:
The script handles errors gracefully and logs them.

It retries failed requests with exponential backoff.

Remember to adapt the script further based on your specific requirements and risk tolerance. Happy trading! 🚀📈
