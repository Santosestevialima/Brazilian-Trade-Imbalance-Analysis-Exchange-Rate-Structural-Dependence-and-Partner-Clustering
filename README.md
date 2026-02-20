# Brazilian Trade Imbalance Analysis: Exchange Rate, Structural Dependence and Partner Clustering

## Overview

This project analyzes Brazil’s trade imbalance between 2015 and 2024, investigating whether the deficit is structurally concentrated among specific trade partners or broadly distributed.

---

## Data Collection

The dataset includes Brazilian trade data from 2015 to 2024, containing:

- Country (trade partner)
- Year
- Exports (USD)
- Imports (USD)
- Average exchange rate (USD/BRL)

The trade balance was calculated as:

Trade Balance = Exports – Imports

---

## Modeling

The analysis includes:

- Trade balance calculation (exports – imports)
- Structural dependence index
- Correlation analysis (exchange rate vs imports)
- Linear regression with R² evaluation
- Partner segmentation using K-Means clustering

### Regression Result

The linear regression model produced R² ≈ 0.09, indicating that exchange rate fluctuations explain only about 9% of import variation.

---

## Key Findings

- Trade imbalance is not homogeneously distributed across partners.
- Some countries show consistent structural deficit patterns.
- Exchange rate influence is limited.
- Clustering reveals distinct commercial relationship patterns.

---

## Conclusions

Results indicate that Brazil’s trade imbalance is predominantly structural and concentrated among specific commercial partners, rather than being solely driven by exchange rate variations.
