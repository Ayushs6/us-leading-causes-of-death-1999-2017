# Leading Causes of Death in the U.S. (1999–2017) — EDA & Visualizations

Exploratory analysis of state-level mortality trends across the United States, focusing on leading causes of death, geographic hotspots, and changes over time.

## Data Source
National Center for Health Statistics (NCHS) — Leading Causes of Death:
https://data.cdc.gov/National-Center-for-Health-Statistics/NCHS-Leading-Causes-of-Death-United-States/bi63-dtpu/about_data

Key columns: State, Year, Cause Name, Deaths, Age-adjusted Death Rate

## What I did
- Cleaned and standardized column names
- Converted numeric fields (deaths, age-adjusted death rate)
- Filtered out summary rows (United States, All causes)
- Aggregated by cause and by state to compare totals and rates

## Visualizations
- Choropleth map (Heart disease: avg age-adjusted death rate by state)
- Bubble map (Cancer: total deaths by state)
- Box plot (Age-adjusted death rate distribution by cause)
- Scatter plot (Cancer deaths by state)
- Interactive Plotly:
  - Animated time-series ranking of causes (1999–2017)
  - Animated choropleth by year for heart disease rates

