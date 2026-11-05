# Does the US Yield Curve Predict Recessions?

Python analysis (pandas, statsmodels, seaborn) using FRED data, 1976–2026.

## What I did
- Cleaned and merged nine FRED series (daily, monthly, quarterly) into a 604-month dataset
- Tested whether the 10Y-2Y and 10Y-3M Treasury spreads warn of US recessions (average lead time of about 16 months for 10Y-2Y)
- Regressed next-year GDP growth on the spread, with robustness checks (excluding the pandemic, robust regression)
- Reported limitations: small sample, one missed recession (2020), association rather than causation

## How to view
Download `Project - Neha.html` and open it in your browser to see all graphs and interpretations.

## How to run
Requires Python, pandas, numpy, matplotlib, seaborn, statsmodels and fredapi, plus a free FRED API key from fred.stlouisfed.org.
