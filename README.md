# S&P 500 Historical Log Return Analysis
![image](https://github.com/sciencenerd880/statistical_analysis_snp500/assets/122241013/8315ec0f-0a6f-4960-974a-296602ce6b10)

## Overview
This repository contains a Python script for conducting a statistical analysis of the S&P 500 index's historical log returns over a 10-year period from January 1, 2010, to December 31, 2020. The analysis includes data retrieval, computation of log returns, statistical measurements, data visualization, and probability estimation of negative returns.

## Features
1. **Data Retrieval**: Fetch S&P 500 historical data using the `yfinance` library.
2. **Log Return Calculation**: Compute daily log returns for consecutive trading days.
3. **Statistical Analysis**: Calculate mean and standard deviation of daily log returns.
4. **Data Visualization**: Plot a histogram of log returns and a normal distribution curve for comparison.
5. **Probability Estimation**:
   - Calculate the daily probability of the index dropping by 1% to 5%.
   - Estimate the probability of the index dropping over 5% in a 30-day period.

## Usage
To run the script, navigate to the script's directory and execute the python notebook

## Requirements
- Python 3
- `pandas`
- `numpy`
- `matplotlib`
- `scipy`
- `yfinance`

Make sure to install all required libraries using `pip` before running the script.

