Portfolio Optimization Engine

A modular, research-grade engine for building and backtesting optimized investment portfolios using quantitative strategies and machine learning. The system supports multiple allocation models, historical data analysis, performance metrics, and risk constraints.

Overview
This project enables data-driven portfolio construction by combining classical optimization techniques with flexible modeling. It is designed to test portfolio strategies, analyze trade-offs between risk and return, and simulate realistic investment behavior.
Features include allocation optimizers, dynamic rebalancing, custom constraints, and visual analytics.

Key Features

Portfolio optimization using:
- Mean-Variance (Markowitz)
- Minimum Variance
- Maximum Sharpe Ratio
- Equal Risk Contribution (ERC)
- Black-Litterman (optional)
- Support for custom constraints (sector caps, turnover limits, etc.)
- Historical backtesting with rebalancing frequency
- Performance metrics: Sharpe, Sortino, max drawdown, volatility
- Visualizations: efficient frontier, asset weights, risk-return charts
- Plug-and-play architecture for experimenting with ML strategies
  
Technology Stack:
- Python
- NumPy / Pandas / CVXPY / SciPy
- Matplotlib / Seaborn / Plotly

Setup Instructions:
1. Clone the Repository

```bash
git clone https://github.com/Iza-3435/portfolio-intelligence.git
cd portfolio-intelligence

