An R-based analysis using IMF CPI data to illustrate how inflation erodes real investment returns over time. The project compares nominal and inflation-adjusted wealth accumulation for G7 economies using time-series visualization.
# Nominal vs Real Returns: Inflation as the Silent Tax

This project demonstrates how inflation erodes real wealth over time using
IMF CPI data for G7 economies.

## Data
- Source: IMF Consumer Price Index (Monthly)
- Transformation: CPI Index (All Items)

## Methodology
1. Convert CPI data from wide to long format
2. Compute month-over-month inflation
3. Simulate nominal vs real wealth accumulation
4. Visualize divergence over time

## Key Insight
Even moderate inflation significantly reduces real returns over long horizons,
highlighting inflation as a silent but persistent tax on capital.

## Tools
- R
- tidyverse
- ggplot2
- lubridate
