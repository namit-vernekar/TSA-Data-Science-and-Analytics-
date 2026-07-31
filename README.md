# TSA Data Science and Analytics - Housing Data Analysis

Gold Medal project for the **Technology Student Association (TSA) Data Science & Analytics** event — Ardrey Kell High School Chapter.

This repository contains the data, analysis, and final portfolio submitted during the 2025 NCTSA State Conference

## Overview

This project explores the relationship between household income and housing costs across U.S. states, examining income-to-housing cost ratios to identify patterns of regional affordability and disparity. The analysis combines data wrangling, statistical exploration, and visualization to surface insights on where housing costs are outpacing income growth.

## Recognition

- Gold Medalist – TSA NC Western Regional Conference (Data Science & Analytics)

## Repository Structure

```
TSA-Data-Science-and-Analytics/
├── datasets/
│   └── ZillowStateHousingData_original.xlsx   # Raw housing cost data (Zillow)
├── portfolio/
│   └── TSA Documentation Portfolio.pdf         # Full write-up: methodology, process, and results
└── README.md
```

## Tools & Technologies

- **Python** — Pandas, Matplotlib, Seaborn
- **Excel** — data cleaning and supplementary analysis
- **Zillow Housing Data** — primary dataset sources

## Methodology

1. Collected and cleaned different types of pricing data from Zillow
2. Merged with income data to compute income-to-housing cost ratios
3. Structured the dataset with Pandas
4. Used Matplotlib and Seaborn to create visualizations
5. Looked at conclusions/analysis from correlations and visualizations created
6. Documented the full process in the TSA competition portfolio

## Key Insights

Housing prices have grown faster than median household income for the past 25 years, and the gap has grown since the pandemic. At the state level, house prices and income are strongly correlated (0.8) but at the county level only moderately so (0.65), suggesting that other factors also drive affordability. States such as California and Hawaii are showing extreme unaffordability, and the top 20 metro areas — where nearly 40% of the U.S. population lives — are seeing the steepest price-to-income differences in the country.

## Full Documentation

See [`portfolio/`](./portfolio) for the complete TSA Documentation Portfolio, including detailed methodology, charts, and competition write-up.
