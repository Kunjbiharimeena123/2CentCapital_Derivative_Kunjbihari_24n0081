# 2CentCapital_Derivative_Kunjbihari_24n0081
# Options Trading Strategy Backtesting and Analysis

This project aims to develop and backtest different options trading strategies in the context of the Bank Nifty index. It involves analyzing their performance under different market scenarios and comparing the performance of different call calendar strategies.

## Project Overview

The project consists of two main tasks:

1.  **Options Strategy Backtesting:** Develop and backtest three distinct options trading strategies:
    *   Long Straddle: Utilized in high-volatility markets to capitalize on price fluctuations.
    *   Covered Call: A bullish strategy generating potential income from selling call options while holding the underlying asset.
    *   Protective Put: A bearish strategy aiming to limit potential losses on a long stock position by purchasing put options.
2.  **Call Calendar Strategy Analysis:** Compare the performance of call calendar strategies under different scenarios with varying time horizons and expiry dates.


## Dependencies

*   **pandas:** For data manipulation and analysis.
*   **numpy:** For numerical computing.
*   **matplotlib:** For data visualization.
*   **reportlab:** For generating PDF reports.


## Project Structure

The project is organized into the following sections:

1.  **Data Preparation:**  This section involves loading or generating the necessary data for the backtesting and analysis.
2.  **Task 1: Strategy Development and Backtesting:** This section contains the core logic for developing and backtesting the three options strategies.
3.  **Task 2: Difference Analysis Between Call Calendars:** This section analyzes the performance of different call calendar strategies under various scenarios.
4.  **Report Generation:** This section generates a PDF report summarizing the project's findings.


## Task 1: Strategy Development and Backtesting

This task involves backtesting three different options trading strategies.

### Subtasks:

1.  **Define functions for each strategy:** Develop functions that implement the logic for calculating profit and loss for each strategy based on the underlying price movement and premium values.
2.  **Generate sample data or load historical data:** Create sample data for demonstration purposes or load actual historical data for the Bank Nifty index.
3.  **Execute backtests:** Run the backtesting functions using the sample or historical data, simulating the trading strategy over a specified period.
4.  **Calculate P&L:** Compute the profit and loss (P&L) for each strategy based on the backtesting results.

**Example: Short Call Strategy**
