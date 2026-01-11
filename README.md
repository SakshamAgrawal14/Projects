# Monte Carlo Simulation for Portfolio Risk Analysis
## Overview
This project uses Monte Carlo simulation to analyze portfolio risk and return under uncertainty. 
By modeling correlated asset returns, the project compares different portfolio allocation decisions 
and evaluates their risk–return tradeoffs.

## Motivation
In financial and economic decision-making, uncertainty plays a central role. 
Point estimates such as average return often fail to capture downside risk.
Monte Carlo simulation provides a way to model a wide range of possible outcomes 
and assess decisions based on the full distribution of returns.

## Methodology
- Asset returns are modeled as correlated random variables using a multivariate normal distribution.
- Thousands of simulated return scenarios are generated using Monte Carlo methods.
- Portfolio returns are computed as weighted combinations of asset returns.
- Risk metrics such as volatility and downside risk (percentile-based) are used for comparison.
- Sensitivity analysis is performed by varying correlation to study diversification effects.

## Results
- Aggressive portfolios achieve higher expected returns but exhibit significantly higher risk.
- As correlation between assets increases, diversification benefits decrease and portfolio risk rises.
- Risk–return tradeoffs are better understood by analyzing distributions rather than averages alone.

## Assumptions and Limitations
- Asset returns are assumed to follow a normal distribution.
- Model parameters (returns, volatility, correlation) are hypothetical and not calibrated to real market data.
- The analysis does not include transaction costs, dynamic rebalancing, or tail-dependence effects.

## Possible Extensions
- Incorporating non-normal return distributions.
- Using real historical data for parameter estimation.
- Extending the framework to dynamic portfolio rebalancing.
