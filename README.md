# WIA1002-DS-Assignment-Topic5

## Stock Trading Website

This is a stock trading website built using Java Object-Oriented Programming (OOP) principles. The website allows users to buy and sell stocks and keep track of their portfolios.

### Classes

Here are the main classes used in the system:

**Stock**: Represents a single stock in the trading system.
**Portfolio**: Represents a user's portfolio, which contains a list of the stocks they own and the number of shares they own of each stock.
**Order**: Represents an order to buy or sell a stock.
**TradingEngine**: Represents the trading engine that executes orders and updates stock prices.
**User**: Represents a user of the trading system.
**TradingApp**: Represents the main application that users interact with.


### Usage

To use the system, first create some Stock objects and add them to a list. Then create a TradingEngine object with that list of stocks. Next, create some User objects and add them to a list. Finally, create a TradingApp object with the list of users and the trading engine.

To place an order, call the placeOrder method on the TradingApp object, passing in the user who is placing the order and the order itself.

To update the stock prices, call the updatePrices method on the TradingEngine object.

### Disclaimer

This is just an example implementation of a stock trading website using Java OOP. It is not intended to be used in production or for actual trading purposes. Always consult a professional financial advisor before making any investment decisions.
