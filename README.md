# USD/JPY and Macroeconomic Drivers  
### Theory vs. Empirical Evidence

## Overview
This repository analyzes the relationship between USD/JPY and key macroeconomic variables 
(interest rates, risk sentiment, equities, and commodities), highlighting the gap between 
textbook theories and observed market behavior.

The project is designed as a research-oriented, replication-ready macro-finance analysis.

## Key Questions
- What macro variables have driven USD/JPY movements since the 2000s?
- Why have interest rate differentials lost explanatory power in recent years?
- How should yen depreciation be interpreted under the current global regime?

## Main Findings (Non-Technical)
- The yen has structurally shifted from a safe-haven currency to a funding currency.
- Short-term interest rates no longer explain USD/JPY dynamics post-2020.
- Global risk-on conditions and expected returns dominate exchange rate movements.

## Data
- US interest rates (FRED)
- USD/JPY exchange rate (FRED)
- VIX, equity indices, oil prices, shoort term rate, long term rate 

## Methods
- Correlation analysis
- Time-series visualization
- Regime-based interpretation (no structural estimation yet)\

## code
- double_axis.py is the code to compare USD/JP exchange rate to JP with simple graph.
- if you have FRED API key, you can execute  it quickely.
- SVAR_IRF is the code to plot IRF of each shocks.cholesky.py is the function to execute this file.
- SVAR is based on Structural Vector Autoregressive Analysis by by Lutz Kilian (Author), Helmut Lütkepohl (Author).
- mistake can exist.if you notice, plz let me.



## Status
Ongoing research project.  
The analysis is continuously updated and extended.

## Author
Independent research project by a macroeconomics student  
(focusing on open-economy macro and macro-finance).
