# 📈 CodeAlpha Stock Portfolio Tracker

A simple **Stock Portfolio Tracker built using Python 3** that helps users record and manage their stock investments. The program accepts stock tickers, share quantities, and purchase prices, then calculates the total investment and displays a structured portfolio summary.

This beginner-friendly project demonstrates core Python programming concepts, input validation, error handling, and basic financial calculations.

## 🛠️ Features

- 📊 **Add Multiple Stocks:** Enter multiple stock tickers into your portfolio.
- 🔢 **Record Share Quantities:** Specify the number of shares purchased for each stock.
- 💵 **Track Purchase Prices:** Enter the buying price per share.
- 🧮 **Calculate Investment:** Automatically calculates the investment amount for each stock.
- 💰 **Total Portfolio Investment:** Displays the total amount invested across all entries.
- 📋 **Tabular Summary:** Presents portfolio details in a clean, readable format.
- ⚠️ **Input Validation:** Handles invalid entries, such as incorrect numeric inputs.
- 🔄 **Interactive Input:** Continue adding stocks until you type `done`.

## 💻 Technologies Used

- **Programming Language:** Python 3
- **Concepts:** Variables, lists, loops, conditional statements, functions, exception handling, and arithmetic operations.
- **Libraries:** Core Python; no external libraries required.

## ⚙️ How It Works

1. The program welcomes the user to the Stock Portfolio Tracker.
2. The user enters a stock ticker, such as `AAPL` or `TSLA`.
3. The user provides the number of shares and the purchase price per share.
4. The program calculates the investment for each entry using:

   **Investment = Number of Shares × Purchase Price**

5. The user can add more stocks or type `done` to finish.
6. The program displays a tabular portfolio summary and the total investment.

## 🚀 Getting Started

### Prerequisites

Ensure that Python 3 is installed on your system.

Check your Python version:

```bash
python --version
```

Alternatively, use:

```bash
python3 --version
```

### Installation and Execution

**1. Clone the repository**

```bash
git clone <your-repository-url>
```

**2. Navigate to the project folder**

```bash
cd codealpha_stock_portfolio_tracker
```

**3. Run the program**

If your Python file is named `stock_portfolio_tracker.py`, execute:

```bash
python stock_portfolio_tracker.py
```

On systems using `python3`, run:

```bash
python3 stock_portfolio_tracker.py
```

*Note: Replace the filename with your actual Python source filename if it differs.*

## 🖥️ Example Usage

### Sample Input

```text
📈 Welcome to the Stock Portfolio Tracker!
Enter your stocks. Type 'done' to finish.

Enter stock ticker (e.g., AAPL): AAPL
Enter number of shares for AAPL: 10
Enter buy price for AAPL ($): 145

Enter stock ticker (e.g., AAPL): TSLA
Enter number of shares for TSLA: 5
Enter buy price for TSLA ($): 720

Enter stock ticker (e.g., AAPL): done
```

### Sample Output

```text
📊 Portfolio Summary:

Ticker  Shares  Buy Price ($)  Invested ($)
AAPL    10      145.0          1450.0
TSLA    5       720.0          3600.0

💰 Total Investment: $5050.0
```

## 🧠 Python Concepts Demonstrated

- Variables and data types
- Lists and data storage
- `while` and `for` loops
- Conditional statements
- User input and output
- Arithmetic calculations
- Exception handling with `try` and `except`
- Formatting tabular output

## 🎯 Project Objective

The objective of this project is to build a simple investment-tracking application while strengthening Python programming skills. It demonstrates how user-provided financial data can be stored, processed, and summarized through basic calculations.

## ⚠️ Important Note

This project calculates investment amounts using the purchase prices entered by the user. It does **not** fetch live market prices or provide real-time stock valuations unless live market data functionality is implemented separately.

## 🔮 Future Enhancements

- Integrate a stock market API for live stock prices.
- Calculate current portfolio value and profit or loss.
- Save portfolio data to a CSV or JSON file.
- Add stock search and portfolio editing functionality.
- Display portfolio performance using charts.
- Build a graphical user interface (GUI).

## 👩‍💻 Internship Details

- **Organization:** CodeAlpha
- **Project:** Stock Portfolio Tracker
- **Programming Language:** Python 3
- **Project Type:** Beginner-level Python application

---

⭐ If you find this project useful, consider giving the repository a star!


