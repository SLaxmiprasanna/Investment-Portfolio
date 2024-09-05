 Okama

[![PyPI version](https://badge.fury.io/py/okama.svg)](https://badge.fury.io/py/okama) [![Build Status](https://travis-ci.org/mbk-dev/okama.svg?branch=master)](https://travis-ci.org/mbk-dev/okama)

Okama is a Python library designed for financial data analysis and asset allocation modeling. It provides tools to analyze portfolios, run historical simulations, and calculate performance metrics, such as expected returns, volatility, drawdowns, and other risk indicators. The library is built with simplicity and flexibility in mind, making it a valuable tool for investors, financial analysts, and researchers alike.

 Features

- Asset Allocation Analysis: Analyze individual assets and portfolios using a wide range of financial metrics.
- Historical Data: Retrieve historical prices and returns for stocks, bonds, ETFs, and other financial instruments.
- Risk & Performance Metrics: Calculate metrics like volatility, Sharpe ratio, drawdowns, and VaR.
- Efficient Frontier: Generate efficient frontiers and model portfolio optimizations based on modern portfolio theory (MPT).
- Scenario Simulations: Perform scenario-based simulations to evaluate different investment strategies.
- Integration: Seamlessly integrates with external financial databases to access up-to-date market data.
- Visualization Tools: Easily visualize portfolio performance, risk exposures, and optimization results with built-in plotting functions.

 Installation

Install the latest version from PyPI:

```bash
pip install okama
```

 Quick Start

Here is a simple example to get started with okama:

```python
import okama as ok

 Create a portfolio of assets
portfolio = ok.Portfolio(['AAPL.US', 'GOOG.US', 'TSLA.US'], currency='USD')

 Get expected returns and other statistics
portfolio.summary()

 Generate the efficient frontier
portfolio.plot_ef()

 Visualize the historical performance
portfolio.plot()
```

 Documentation

You can find the full documentation and user guide on the official [documentation website](https://okama.readthedocs.io/en/latest/).

 Contributing

We welcome contributions to improve okama! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a pull request.

Before submitting a pull request, ensure that your code adheres to the coding standards and passes all tests.

 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
