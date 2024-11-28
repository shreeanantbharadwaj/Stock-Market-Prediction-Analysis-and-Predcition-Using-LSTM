
# Stock Market Analysis and Prediction Using LSTM

![Stock Market](techAnalysis-1000x500.jpg.webp)

## Overview

This project focuses on time series analysis and prediction, specifically for stock market data. Time series data, which is a sequence of data points indexed in time order, is prevalent in many fields, making it a crucial aspect for data analysts and scientists.

In this notebook, we explore stock data from several major technology companies: Apple, Amazon, Google, and Microsoft. Using the `yfinance` library, we fetch historical stock prices and perform a range of analyses, including risk assessment based on historical performance. Additionally, we predict future stock prices using a Long Short Term Memory (LSTM) neural network model.

### Key Questions Addressed:

1. **Price Change Over Time:** How have the prices of the selected stocks changed over time?
2. **Average Daily Return:** What is the average daily return of these stocks?
3. **Moving Average Analysis:** What are the moving averages for the stocks over different time periods?

## Project Workflow

1. **Data Collection:**
   - Use the `yfinance` library to fetch stock data for Apple, Amazon, Google, and Microsoft.
   - Visualize stock prices using `Matplotlib` and `Seaborn`.

2. **Data Analysis:**
   - Analyze the stock prices over time.
   - Compute the daily returns to measure stock performance.
   - Calculate and plot the moving average of stock prices.

3. **Risk Assessment:**
   - Evaluate the historical risk of stocks based on performance volatility.

4. **Stock Price Prediction:**
   - Implement a Long Short Term Memory (LSTM) neural network to predict future stock prices based on historical data.

## Requirements

To run the notebook and reproduce the results, the following libraries are required:

```bash
pip install yfinance
pip install seaborn
pip install matplotlib
pip install tensorflow
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock-market-analysis-lstm.git
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook stock-market-analysis-prediction-using-lstm.ipynb
   ```

4. Run the cells to fetch stock data, analyze stock performance, and predict future prices.

## Results

The LSTM model provides future stock price predictions based on the historical data of the selected technology stocks. The predictions help illustrate the potential future movements in stock prices.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
