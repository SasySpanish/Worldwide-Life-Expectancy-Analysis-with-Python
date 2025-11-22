# data/

This folder contains the cleaned and processed life expectancy dataset used throughout the project.

### lifexp.csv
- **Source**: Our World in Data – "Life expectancy"  
  Link: https://ourworldindata.org/grapher/life-expectancy  
  Original authors & sources:  
  James C. Riley (2005), Zijdeman et al. (2015), Human Mortality Database (2025), UN World Population Prospects (2024)  
  License: CC-BY

- **Modifications applied in this project** (see `src/main.py` for exact cleaning steps):
  - Only years 1950–2023 are kept (pre-1950 data is sparse and fragmentary)
  - Removed rows with missing values in key columns
  - Kept only entities with ISO-3 country codes + major regional aggregates (World, Africa, Europe, etc.)
  - Standardized column names and data types

This cleaned version is optimized for fast analysis and consistent plotting.

Last dataset update: November 2025
