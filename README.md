Distribution Models and Portfolio Risk Management

Evidence from Technology and Energy Stocks

Overview

This project investigates how statistical models of stock returns affect tail-risk estimation and portfolio risk management.

Using 20 U.S. technology and energy stocks, we compare the Normal distribution, Student-t distribution, and Gaussian Mixture Model (GMM).

Research Questions

Which distribution best describes historical stock returns?

Do better distribution fits improve out-of-sample risk forecasts?

Does model-based risk management improve investment performance after accounting for opportunity costs?

Methodology

Assets: 20 U.S. technology and energy stocks

Training period: 2021–2023

Testing period: 2024–2025

Methods: Maximum Likelihood Estimation, BIC, VaR, Expected Shortfall, portfolio backtesting

Key Findings

Student-t provides the best in-sample BIC among the three candidate distributions for all 20 stocks.

Better historical distribution fitting does not consistently translate into better out-of-sample VaR performance.

VaR-based portfolio sizing substantially reduces volatility and drawdowns but sacrifices cumulative returns during the observed rising market.

Risk management should be evaluated not only by the losses it avoids, but also by the investment opportunities it gives up.

Tools

Python, NumPy, pandas, SciPy, scikit-learn, Matplotlib, yfinance

Research Outputs

Research paper

Statistical analysis and visualizations

Portfolio backtesting

Presentation slides

Limitations

Results are specific to the assets, sample period, and portfolio-sizing rules studied. They do not establish that fully invested portfolios will outperform in future market conditions.
