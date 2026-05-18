# Stock Portfolio Tracker

## Overview

This is a simple Python-based Stock Portfolio Tracker that allows users to manage and monitor their stock investments. The program stores stock information using dictionaries and provides basic portfolio management features such as adding stocks, removing stocks, and viewing the current portfolio.

The project was built to practice Python fundamentals including functions, dictionaries, conditional statements, and data handling.

## Features

- Add stocks to the portfolio
- Update stock quantity and average price if a stock already exists
- Remove selected stocks or delete them completely
- View the current portfolio details
- Display stock quantity and price information in an organized format

## Technologies Used

- Python 3

## Project Structure

```text
Stock-Portfolio-Tracker/
│
├── stock_portfolio.py
└── README.md
```

## How It Works

The portfolio is stored in a Python dictionary where:

- The stock symbol acts as the key
- Quantity and price are stored as values

Example structure:

```python
portfolio = {
    "AAPL": {
        "quantity": 15,
        "price": 151.67
    }
}
```

When additional shares of an existing stock are added, the program automatically recalculates the average stock price.

## Running the Project

1. Clone this repository:

```bash
git clone https://github.com/your-username/Stock-Portfolio-Tracker.git
```

2. Move into the project directory:

```bash
cd Stock-Portfolio-Tracker
```

3. Run the program:

```bash
python stock_portfolio.py
```

## Sample Output

```text
Added 10 shares of AAPL at $150 each.
Added 5 shares of GOOGL at $2800 each.
Added 5 shares of AAPL at $155 each.

Current Portfolio:

AAPL: 15 shares at $151.67 each
GOOGL: 5 shares at $2800.00 each
```

## Purpose

This project was created as a learning exercise to strengthen core Python concepts and understand how data structures can be used in real-world applications.

## Future Improvements

Possible enhancements for this project:

- Add a menu-driven interface
- Store portfolio data in a file or database
- Fetch live stock prices using an API
- Calculate total portfolio value
- Add profit/loss tracking

## License

This project is open for learning and personal use.
