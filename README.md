# Empirical analysis of Bitcoin log-returns

## Overview
This project presents an empirical analysis of daily Bitcoin log-returns, focusing on their statistical properties and deviations from the Gaussian model. The study explores volatility, heavy tails, kurtosis, temporal dependence, and scaling behavior, highlighting the limitations of standard assumptions in financial modeling.

## Objective
The main goal is to characterize Bitcoin returns from a quantitative perspective:  
- Compare empirical returns with the Gaussian distribution.  
- Identify the presence of heavy tails and extreme events.  
- Analyze volatility clustering and autocorrelation patterns.  
- Investigate scaling behavior using the Hurst exponent.

## Tools and Libraries
The analysis was conducted using Python with the following libraries:  
- **yfinance**: for downloading historical Bitcoin prices.  
- **pandas**: for time series manipulation.  
- **numpy**: for numerical computations and logarithmic transformations.  
- **matplotlib**: for visualizations of distributions and time series.  
- **scipy** and **statsmodels**: for statistical tests, regressions, and autocorrelation analysis.

## Repository Structure


## Key Findings
- Bitcoin returns significantly deviate from Gaussian assumptions, showing **leptokurtic distributions** and heavy tails.  
- **Volatility clustering** is observed, with large returns tending to follow other large returns in magnitude.  
- Absolute returns display **long-term memory**, confirmed via Hurst exponent analysis, indicating persistent volatility.  
- Temporal aggregation reduces kurtosis, illustrating the effect of the **Central Limit Theorem** at longer horizons.

## References
- Mantegna, R. & Stanley, H. *An Introduction to Econophysics*. Cambridge University Press.  
- MIT OpenCourseWare: *Mathematics in Applications to Finance*.  
