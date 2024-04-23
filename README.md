# Time Series Analysis of United States Labor Force Participation Rate

**Authors:** Michael Cao, Winston Park

## Introduction

In this project, we analyze the United States Labor Force Participation Rate (LFPR) using time series analysis techniques. LFPR is a crucial economic indicator that reflects the proportion of individuals in the population who are 16 years or older and actively participating in the labor force. Our goal is to forecast LFPR and understand its relationship with other economic variables like inflation, unemployment rate, and population level.

## Motivation

LFPR is a key factor in economic growth, and understanding its trends can provide valuable insights into the broader economy. By analyzing LFPR alongside other economic metrics, we aim to identify patterns, forecast future trends, and explore underlying relationships.

## Methodology

We collected non-seasonally adjusted LFPR data along with other economic indicators from January 1948 to December 2019. Our analysis includes data preparation, model building, and interpretation of results. We employed two main models: SARIMA + GARCH and VARX, to forecast LFPR and investigate its relationships with other variables.

## Results

- **Model 1 (SARIMA-GARCH):** Forecasted LFPR shows a stable trend with slight variations over the forecast period.
- **Model 2 (VARX):** Identified significant relationships between LFPR, inflation, and population level. Granger causality tests suggest a causal link between LFPR and inflation.

Below we used an out-of-sample approach to access the short-term model performance of several time series models (SARIMA-GARCH, VARX, and TBATS):
  <p align="center">
  <img src="https://github.com/mic-cao/Time_Series_LFPR/blob/main/tbats.png" alt="OOS" width="650">
  </p>

## Conclusion

Our analysis provides insights into short-term LFPR trends and its relationship with key economic factors. The models presented offer valuable tools for forecasting and understanding labor market dynamics.

---

For more details, refer to the [full report](https://github.com/mic-cao/Time_Series_LFPR/blob/main/Final_Report.pdf).
