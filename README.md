# Portfolio Optimization with Efficient Frontier

This project implements a portfolio optimization tool that downloads historical stock data, calculates returns and volatility, computes the efficient frontier, and visualizes the results. It's designed to help investors and financial analysts optimize their portfolios based on the modern portfolio theory.

## Features

- Download historical stock data from Yahoo Finance
- Calculate daily returns and volatility of stocks
- Compute the efficient frontier for a set of stocks
- Visualize the efficient frontier

## Requirements

- Python 3.x
- yfinance
- pandas
- numpy
- matplotlib

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/portfolio-optimization.git
   cd portfolio-optimization
   ```

2. Install the required packages:
   ```
   pip install yfinance pandas numpy matplotlib
   ```

## Usage

The project consists of several main components:

1. **Downloading Stock Data**: Use the `download_stock_data` function to fetch historical stock data from Yahoo Finance.

2. **Calculating Returns and Volatility**: Utilize the `calculate_daily_returns` and `calculate_volatility` functions to compute the daily returns and volatility of the stocks.

3. **Computing the Efficient Frontier**: The `compute_efficient_frontier` function calculates the efficient frontier for a given set of stock returns.

4. **Visualizing the Efficient Frontier**: Use matplotlib to plot the efficient frontier.

Detailed usage instructions and examples can be found in the project's Jupyter notebook or Python script.

## Example Output

The script will output:

- Daily returns of the selected stocks
- Volatility of each stock
- A scatter plot representing the efficient frontier

## Customization

You can customize the following parameters:

- Stock tickers
- Date range for analysis
- Number of portfolios to simulate for the efficient frontier
- Plot styling and dimensions

## Disclaimer

This tool is for educational and research purposes only. It is not financial advice, and should not be used as the sole basis for making investment decisions. Always consult with a qualified financial advisor and do your own research before making any investment.

## License

[MIT License](LICENSE)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
