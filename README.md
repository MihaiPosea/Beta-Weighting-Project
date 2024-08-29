Overview
This script calculates the beta of a stock portfolio relative to a market reference using historical data from Yahoo Finance (yfinance).
Users input stock symbols and their weights, and the script calculates the portfolio's beta.

Requirements
You'll need the following Python libraries:

pandas
numpy
yfinance
Install them with:

Usage
Input the number of stocks, their symbols, and their respective weights.
Provide the market reference symbol (e.g., ^GSPC for the S&P 500).
The script fetches historical data, calculates log returns, and computes the beta of the portfolio.
Outputs:
Stock symbols and weights collected.
Portfolio beta value.
