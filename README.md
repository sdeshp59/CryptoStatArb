# Statistical Arbitrage Strategy - Cryptocurrency Markets

Implementation of the Avellaneda & Lee (2010) statistical arbitrage methodology applied to cryptocurrency markets for ISYE 6767 Final Project.

## Project Overview

This project implements a PCA-based statistical arbitrage trading strategy using:

- **Data**: Hourly cryptocurrency prices (2021-2022)
- **Method**: Principal Component Analysis + Ornstein-Uhlenbeck mean-reversion
- **Strategy**: S-score based trading signals with dynamic position management

## Project Structure

```sh
CryptoStatArb
├── data
│   ├── coin_all_prices_full.csv.      # Hourly prices for 120+ tokens
│   └── coin_universe_150K_40.csv      # Top 40 tokens by market cap
├── outputs
├── src
├── tests
└── requirements.txt
```
