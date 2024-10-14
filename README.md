# TIME-SERIES-PROJECT-

Twitter Stock Market Trend and Seasonality Analysis

Overview

This project analyzes the Twitter Stock Market Dataset to calculate trend and seasonality using simple moving averages.

Requirements

- Python 3.x
- matplotlib library for plotting
- csv library for data loading

Dataset

- Twitter Stock Market Dataset.csv

Code Structure

- Data loading: Loads the dataset into dates and data lists.
- Trend calculation: calculate_trend function calculates trend using simple moving averages.
- Seasonality calculation: calculate_seasonality function calculates seasonality.
- Main script: Calculates trend and seasonality, prints results, and plots data.

Usage

1. Install required libraries: pip install matplotlib
2. Download Twitter Stock Market Dataset.csv
3. Run the script: python (link unavailable)
4. View results in console and plot.

Functions

- calculate_trend(data, q): Calculates trend using simple moving averages.
- calculate_seasonality(data, trend, q): Calculates seasonality.

Variables

- data: List of closing stock prices.
- dates: List of corresponding dates.
- trend: List of calculated trend values.
- seasonality: List of calculated seasonality values.
- q: Window size for moving averages.

License

MIT License

Author

A.Divyadharshini
