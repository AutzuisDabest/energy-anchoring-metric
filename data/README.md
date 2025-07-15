Data Sources
This directory contains information about data sources used in the CEIR analysis. Due to size limitations, only documentation and small samples are included here.
Primary Data Sources

Bitcoin Price Data: Daily prices from CoinGecko (2018-2025)
Energy Consumption: Cambridge Bitcoin Electricity Consumption Index
Mining Distribution: Cambridge Centre for Alternative Finance hash rate data
Electricity Prices: IEA industrial rates by country

Key Files

cambridge_mining_distribution.csv: Geographic distribution of Bitcoin mining
electricity_prices_detailed_by_year.csv: Country-specific electricity rates
fear_greed_index.csv: Market sentiment indicator (control variable)

Data Processing Overview
The CEIR calculation combines these datasets to create geographically-weighted energy costs, which are then compared to market capitalization. The China mining ban (June 2021) and Ethereum Merge (September 2022) provide natural experiments for analyzing energy anchoring effects.
Full datasets available upon request.
