# Stock-Trading-Bot
   A script that has the ability to generate and execute buy and sell signals in financial markets automatically.
## Tools & Technology
- Python
- Selenium
- REST API
- Alpaca Brokerage Account
- VS Code

## Workflow
1. Checks if the market is open.
2. Executes main method
    - Web Scrapes tradable stocks from Yahoo Finance website.
    - Starts placing bracket orders with 5% limit price and 10% stop loss on a particular ticker if the stock is not already currently owned according to the strategy (very basic).
    - Sends an email notifying you about the changes in the portfolio after the market closes.
