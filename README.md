# Stock Portfolio Tracker

## Project description
A simple Python console application. Users enter stock symbols and quantities. The program uses a dictionary of manually defined prices to calculate each holding's value and the total investment.

**Note:** The prices below are sample hardcoded values, not live market prices.

## Available sample stocks

| Stock | Price per share |
|---|---:|
| AAPL | $180 |
| TSLA | $250 |
| GOOGL | $140 |
| MSFT | $420 |
| AMZN | $175 |

## Features
- Enter stock symbols and share quantities.
- Look up prices from a hardcoded dictionary.
- Calculate individual holding values and total investment.
- Validate stock symbols and quantities.
- Optionally save a report in `portfolio_report.txt`.

## Concepts used
- Dictionary
- Input/output
- Basic arithmetic
- `while` loop and `if-else`
- Functions
- File handling (`open`, `write`, `with`)

## Requirements
Python 3.8 or newer. No external packages are required.

## How to run
1. Extract the ZIP file.
2. Open a terminal in this folder.
3. Run `python stock_portfolio_tracker.py`.
4. Enter a stock symbol and quantity.
5. Type `done` when finished.
6. Enter `y` when asked whether to save the report.

## Example calculation
For 2 shares of AAPL and 3 shares of TSLA:
- AAPL: 2 × $180 = $360
- TSLA: 3 × $250 = $750
- Total investment: **$1,110**

The report is saved as `portfolio_report.txt` in the current working directory.
