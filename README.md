# Bitcoin vs Ethereum Market Analysis

This project analyzes historical price data for Bitcoin and Ethereum to compare trends, volatility, and return distributions.

## Overview
The goal of this project is to explore how two major cryptocurrencies behave over time and identify differences in their price movement and risk characteristics.

## Tools
- Python
- pandas
- matplotlib
- seaborn
- scipy (stats, optimize, curve_fit, pearsonr)

## Data
The dataset contains historical price data for:
- Bitcoin
- Ethereum

Files are stored locally in the `data/` folder and loaded into the notebook for analysis.

## Project Structure
crypto-analysis-btc-eth/
│
├── data/ # Raw CSV files
├── notebooks/ # Jupyter notebook analysis
├── outputs/ # Saved plots and visualizations
└── README.md

## Key Analysis
- Time series price trends
- Daily return calculations
- Volatility comparison
- Distribution of returns

## Results
- Bitcoin and Ethereum show similar overall trends but differ in volatility
- Ethereum tends to exhibit higher short-term fluctuations
- Return distributions highlight differences in risk between the two assets

## How to Run
1. Clone the repository
2. Navigate to the `notebooks/` folder
3. Open and run `crypto_analysis.ipynb`

Make sure the data files are located in the `data/` folder.

## Author
Terry White  
Michigan State University — Data Science