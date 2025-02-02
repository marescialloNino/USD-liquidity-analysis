# USD Liquidity Conditions Index & BTC Price Analysis

This project downloads financial data from the Federal Reserve Economic Data (FRED) and Yahoo Finance to compute and visualize a custom USD Liquidity Conditions Index, which Arthur Hayes defined in his essay "Teach Me Daddy".

reference: https://ehandbook.com/teach-me-daddy-33e7a66dfe76

The index is built from three components:

- **Fed Balance Sheet (WALCL)** – Total assets held by the Federal Reserve.
- **Reverse Repo (RRPONTTLD)** – Total amount of accepted reverse repo bids (originally in billions of dollars, converted to millions).
- **Treasury General Account (D2WLTGAL)** – Balance of the US Treasury’s general account held at the NY Fed.

In addition, the project downloads Bitcoin (BTC-USD) price data from Yahoo Finance to compare trends and analyze correlations between BTC price movements and liquidity conditions.


