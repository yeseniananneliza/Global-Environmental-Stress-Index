# Global Environmental Stress Index

A Python and SQL project that creates a composite environmental stress index
using air-quality data from cities around the world.

## Project Overview

This project combines AQI, PM2.5, NO2, ozone, and carbon monoxide measurements
to compare environmental stress across countries and cities.

The analysis includes:

- Data cleaning and column standardization
- A weighted environmental stress index
- SQLite database creation
- SQL queries comparing countries, cities, and pollutants
- Country-level summary exports

## Technologies

Python, pandas, SQL, and SQLite

## Environmental Stress Index

The index is calculated using the following weighted measures:

- AQI: 40%
- PM2.5: 30%
- NO2: 15%
- Ozone: 10%
- Carbon monoxide: 5%

## Power BI Dashboard

[Download the Power BI dashboard](environmental_stress_dashboard.pbix)

## Files

- `environmental_stress_index.ipynb` — Main analysis notebook
- `global_air_pollution_dataset.csv` — Source dataset
- `country_summary.csv` — Country-level summary results

## Note

The environmental stress index is a custom analytical measure created for this
project. It is intended for comparison and exploration, not as an official
environmental-health rating.
