# Oil-Prices-And-Geopolitics-EDA

This repository contains a detailed exploratory data analysis (EDA) of global oil price fluctuations in relation to geopolitical risk and market volatility.

## Notebook Overview

The DataAnalysis.ipynb notebook provides a comprehensive workflow for cleaning, visualizing, and analyzing the relationship between crude oil prices and various macroeconomic indicators. It uses statistical tests and time-series visualization to identify patterns and quantify the market's reaction to geopolitical shocks.

## Problem Statement

The energy market is highly sensitive to global instability. The primary objective of this project is to understand how geopolitical events shape oil price dynamics, volatility regimes, and market uncertainty.

## Dataset Source

The data used in this analysis was sourced from Kaggle.

## Key Concepts 

| Feature                  | Description |
|--------------------------|------------|
| brent_price              | The global benchmark for oil prices |
| wti_price                | US benchmark crude oil. Generally slightly cheaper than brent crude price |
| gpr_index                | Geopolitical Risk Index measuring uncertainty from wars, terrorism, tensions |
| vix                      | Fear Gauge indicating expected stock market volatility |
| dxy_index                | US Dollar Index reflecting USD strength (often inverse to oil) |
| brent_volatility_7d/30d  | Rolling std. deviation capturing short and sustained volatility |

## Notebook Structure

The analysis is organized into the following logical sections:
1. Imports and Data Loading: Setting up the environment and initial data inspection.
2. Correlation Analysis and Hypothesis Testing: Testing relationships (e.g., GPR vs. Volatility, DXY vs. Price).
3. Statistics: Summary of price distributions and central tendencies.
4. Time Series Analysis: Long-term visualization of Brent/WTI trends against key geopolitical milestones.
5. Volatility Analysis: Evaluating how risk spikes during crisis periods.
6. Geopolitical Event Impact Analysis: Comparing market behavior on event days vs. stable periods.
7. Annual and Temporal Patterns: Year-over-year growth and volatility trends.
8. Key Findings and Insights: Final summary of market behaviors and trends discovered.
