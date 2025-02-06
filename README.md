# [Portfolio Optimization and Visualization]

## Overview:
This is a Python-based analysis for portfolio optimization and visualization. It focuses on constructing and analyzing portfolios, applying modern portfolio theory, and visualizing key financial metrics. The project includes an **All-Equity Portfolio** and a **Multi-Asset Class (MAC) Portfolio**, incorporating diversification strategies. 
**We also use harry Markowitz's seminal 1952 paper on modern portfolio theory, using the actual solutions to generate the efficient frontiers of well diversified portfolios.***

## Features:
- **Portfolio Construction:** Defines asset allocations for both All-Equity and Multi-Asset Class portfolios.
- **Optimization:** Uses Modern Portfolio Theory (MPT) and risk-return tradeoff analysis.
- **Risk Management:** Evaluates portfolio volatility.
- **Performance Visualization:** Generates key charts like the efficient frontier, and **Markowitz bullet**.
- **Multi-Asset Diversification:** Expands asset classes in the MAC portfolio for enhanced risk-adjusted returns.

## Portfolios:
### 1. All-Equity (Benchmark/Traditional) Portfolio:
- **Focus:** A collection of major stocks, typically reflecting broad market trends, against which the performance of the MAC portfolio can be compared. Diversification of such a portfolio can only go so far to minimise non-systematic market risk.

### 2. Multi-Asset-Class Portfolio:
- **Focus:** A well-diversified set of assets across various asset classes, designed for a balanced risk-return profile.

### 2. Multi-Asset Class (MAC) Portfolio:
- **Diversification Strategy:** Incorporates equities, bonds, real estate, and gold. Highly defensive in times of market crashes.

## Visualisations:
- **Efficient Frontier:** Plots risk-return tradeoff for optimal portfolios.
- **Markowitz Bullet:** Shows risk-return combinations of various asset allocations.

## Modules used:
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Financial Data:** `yfinance`

## Sugegstions for future improvements:
- Implementing machine learning for return forecasting.
- Out of sample forecasting strategies to analyze portfolio robustness.

## Contributors:
[Reetom Ghosh]
