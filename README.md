# Tesla Stock Price Analysis and Forecasting

## Overview
This project focuses on analyzing and forecasting Tesla (TSLA) stock prices using historical data. The analysis includes data visualization using Plotly, statistical insights with Pandas, and future price prediction using Facebook Prophet.

## Features
- Download Tesla stock price data from Yahoo Finance
- Perform exploratory data analysis (EDA) with Pandas
- Visualize stock trends using Plotly
- Prepare data for time series forecasting
- Train a Facebook Prophet model to predict future stock prices

## Installation
To run this project, install the required dependencies:
```bash
pip install pandas numpy yfinance plotly matplotlib prophet
```

## Usage
1. **Download Stock Data**
   - Fetch Tesla's historical stock data using Yahoo Finance API.
   - Save the data as a CSV file.

2. **Data Analysis & Visualization**
   - Use Pandas to clean and process the dataset.
   - Generate area plots, line charts, and box plots using Plotly.

3. **Time Series Forecasting**
   - Rename the dataset columns to match Prophet's requirements (`ds` for Date, `y` for Close Price).
   - Train a Prophet model on historical stock prices.
   - Use the trained model to forecast future stock prices.


## Dependencies
- Python 3.x
- Pandas
- Numpy
- Yahoo Finance API (yfinance)
- Plotly
- Matplotlib
- Prophet

## License
This project is licensed under the MIT License.

