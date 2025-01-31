# Life Expectancy Analysis

## Overview
This project analyzes life expectancy data across various countries and years. It includes a dataset and a Power BI dashboard for visualization and insights.

## Files Included
- **Life-Expectancy-Data.csv**: A dataset containing life expectancy indicators, health factors, and economic conditions for multiple countries.
- **Life_Expectancy.pbix**: A Power BI report visualizing trends, correlations, and insights related to life expectancy.

## Dataset Description
The dataset includes:
- **Country, Region, Year**: Identifiers for each record.
- **Health Indicators**: Infant deaths, under-five deaths, adult mortality, alcohol consumption, Hepatitis B, measles cases, BMI, polio, diphtheria, HIV incidents.
- **Economic Indicators**: GDP per capita, population, schooling level, economy status (developed/developing).
- **Target Variable**: Life expectancy.

## Power BI Dashboard
The Power BI report provides interactive visualizations, showing:
- Life expectancy trends by country and region.
- Correlations between health/economic indicators and life expectancy.
- Key insights into global and regional disparities.

## How to Use
1. **Dataset**: Open the CSV file in Python, Excel, or any data analysis tool.
2. **Power BI Report**: Open the PBIX file in Power BI to explore visualizations.

## Installation
If you want to analyze the data programmatically:
```python
import pandas as pd
df = pd.read_csv('Life-Expectancy-Data.csv')
df.head()
```

## License
This project is open-source. Feel free to use and modify it.

