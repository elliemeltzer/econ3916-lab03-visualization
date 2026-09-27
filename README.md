# Honest vs. Misleading Visualizations

## Objective

This project examines how statistical summaries and visualization choices can obscure, exaggerate, or accurately communicate patterns in economic data.

## Methodology

- Recreated Anscombe’s Quartet and compared four datasets with nearly identical means, variances, correlations, and regression lines.
- Plotted each dataset to reveal structural differences hidden by its summary statistics.
- Calculated a Lie Factor of 49.0 for a truncated-axis revenue chart and redesigned the visualization using an honest scale.
- Retrieved average hourly earnings and CPI data from FRED and converted nominal earnings into constant 2020 dollars.
- Presented the same real-wage series using full, truncated, cherry-picked, and logarithmic views to evaluate how design choices change interpretation.
- Applied a four-step exploratory data analysis workflow—structure, distributions, relationships, and anomalies—to World Bank GDP data covering 262 countries and 64 years.
- Built an interactive wage-chart tool with controls for the series, time window, y-axis floor, and linear or logarithmic scale.

## Key Findings

Anscombe’s Quartet demonstrated that nearly identical summary statistics can conceal fundamentally different data structures, reinforcing the need to visualize data before modeling it.

The truncated revenue chart transformed an actual increase of approximately 4.1% into an apparent increase of 200%, producing a Lie Factor of 49.0. Raising an axis floor can therefore dramatically exaggerate modest changes.

Nominal hourly earnings rose more than twelvefold over the wage sample, while real earnings increased only about 20%. This difference shows that inflation-adjusted values are necessary when comparing purchasing power across decades.

World Bank GDP was strongly right-skewed, with raw-data skewness of 8.4. A logarithmic transformation reduced the skewness to approximately 0.2 and made differences among economies substantially easier to examine.
