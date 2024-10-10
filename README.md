This project is designed to retrieve stock data from various financial data sources.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before running the code, make sure you have the following installed:

- Python (version 3.x)

### Installation

To install the required packages, open a terminal or command prompt and run the following command:

```
pip install yfinance pandas numpy matplotlib scikit-learn
```

This will install all the necessary packages for the project.

## Usage

To use the code, follow these steps:

1. Open the Jupyter Notebook file `notebook.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the code cell by cell to retrieve stock data.

### Example

To retrieve stock data for Apple Inc. (AAPL) between January 1, 2020 and January 1, 2023, you can use the following code:

```python
stock_data = retrieve_stock_data("AAPL", "2020-01-01", "2023-01-01")
```

## Acknowledgments

- [Yahoo Finance](https://finance.yahoo.com/) for providing the stock data API.
- [Alpha Vantage](https://www.alphavantage.co/) for providing the stock data API.

## Contact

If you have any questions or need further assistance, please reach out to the maintainer of the project.

## Authors

- Henry Pai (https://github.com/halchemylab)