# Trading Strategy

This project implements a simple trading strategy using moving averages. It fetches stock price data from the Alpha Vantage API and applies the strategy to generate buy and sell signals. The results, including accuracy, total profit/loss, and visualization, are provided to evaluate the performance of the strategy.

## Usage

### Running Locally
1. Update the following variables in the script (`trading_strategy.py`):
   - `stock_symbol`: The stock symbol you want to trade (e.g., "IBM").
   - `timeframe`: The timeframe for the stock price data (e.g., "5min").
   - `investment`: The total investment amount for trading.
   - `stop_loss_percentage`: The percentage for the stop loss.
   - `target_percentage`: The percentage for the target.
   - `short_term_sma_periods`: The number of periods for the short-term Simple Moving Average (SMA).
   - `long_term_sma_periods`: The number of periods for the long-term Simple Moving Average (SMA).
   - `api_key`: Your Alpha Vantage API key.

2. Run the script.

### Running in Google Colab
1. Open the Jupyter Notebook `trading_strategy_colab.ipynb` in Google Colab.
2. Update the following parameters in the notebook:
   - `stock_symbol`: The stock symbol you want to trade (e.g., "IBM").
   - `timeframe`: The timeframe for the stock price data (e.g., "5min").
   - `investment`: The total investment amount for trading.
   - `stop_loss_percentage`: The percentage for the stop loss.
   - `target_percentage`: The percentage for the target.
   - `short_term_sma_periods`: The number of periods for the short-term Simple Moving Average (SMA).
   - `long_term_sma_periods`: The number of periods for the long-term Simple Moving Average (SMA).
   - `api_key`: Your Alpha Vantage API key.

3. Run the notebook cell-by-cell to execute the code and visualize the results.

## Results

After running the trading strategy, the following results will be displayed:

- Total Buy Signals: [number of buy signals]
- Total Sell Signals: [number of sell signals]
- Accuracy: [accuracy percentage]
- Total Profit/Loss: [total profit/loss amount]
- Elapsed Time: [execution time in seconds]

Additionally, a visualization of the trading strategy will be displayed, showing the closing price of the stock, buy signals, and sell signals.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
