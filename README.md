\"\"\"
Stock Time Series Dataset

This dataset contains historical stock prices for 29 of the 30 DJIA companies, spanning the last 12 years.

Data Files:
  - all_stocks_2006-01-01_to_2018-01-01.csv: Contains 13 years of stock data for all companies.
  - all_stocks_2017-01-01_to_2018-01-01.csv: Contains stock data for the past year.
  - individual_stocks_2006-01-01_to_2018-01-01/: A folder containing individual stock files, labeled by ticker name.

Columns:
  - Date (yy-mm-dd)
  - Open: Opening price of the stock
  - High: Highest price during the day
  - Low: Lowest price during the day
  - Close: Closing price of the stock
  - Volume: Number of shares traded
  - Name: Stock ticker symbol

Example Usage:

import pandas as pd

# Load the dataset
data = pd.read_csv('all_stocks_2006-01-01_to_2018-01-01.csv')

# Explore data for a specific company (e.g., AAPL)
aapl_data = data[data['Name'] == 'AAPL']

# Data preprocessing...
# Model building...
# Model evaluation...

This should give you a good starting point for your project. Feel free to ask if you have any further questions or modifications!
\"\"\"

# Your code here...
# Data loading, preprocessing, model building, etc.
