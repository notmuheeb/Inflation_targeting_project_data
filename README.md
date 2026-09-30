# Inflation Targeting in India: Volatility and Persistence Since 2016

Data and calculations for a paper examining whether the volatility and 
persistence of inflation in India changed following the adoption of 
flexible inflation targeting in October 2016.

## Data

- **Series**: CPI-Combined, All-India, General Index, base 2012=100
- **Frequency**: Monthly
- **Index period**: January 2011 – December 2025
- **Inflation period**: January 2012 – December 2025 (164 observations)
- **Source**: MOSPI. Pre-2013 values from the back series via RBI's 
  Database on Indian Economy.

## Method

Inflation is the year-on-year percentage change in the index. Volatility 
is measured by the standard deviation and coefficient of variation of 
monthly inflation within each period; persistence by the first-order 
autocorrelation coefficient.

## Exclusions

CPI was not published for April and May 2020, when field price collection 
was suspended. MOSPI's imputed values for those months are excluded, as 
the technical note cautions against their use in time-series comparison. 
Year-on-year inflation is consequently also unavailable for April and 
May 2021.

## Files

- `datafile -Copy.xlsx` — index values, computed inflation, period 
  classifications, and summary statistics
