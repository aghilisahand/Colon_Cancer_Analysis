# Colon Cancer Analysis

This project explores colon cancer case patterns across locations and age groups, alongside selected lifestyle risk factors. It combines cancer registry data with tobacco-use and salt-intake data to create interactive charts and maps.

## Interactive dashboard

View the published visualizations on [GitHub Pages](https://aghilisahand.github.io/Colon_Cancer_Analysis/).

The dashboard includes:

- Colon cancer cases by location and age group
- Tobacco use compared with colon cancer cases, with country, gender, and age-group details
- A heatmap of cancer cases by continent, gender, and age group
- Country maps for salt intake and colon cancer cases
- A correlation matrix comparing cancer incidence with alcohol consumption, obesity prevalence, and physical inactivity

These visualizations are exploratory. Correlations and comparisons show patterns in the data; they do not establish that a risk factor caused a cancer outcome.

## Notebooks

Run the notebooks in this order:

1. **`Analysis.ipynb`** loads and reviews the source data, applies cleaning and validation checks, and prepares the CSV tables used by the dashboard.
2. **`Visualize.ipynb`** loads those prepared tables and builds the interactive dashboard.

## Data sources

- [NCD Risk Factor Collaboration Data Portal](https://ncdportal.org/)
- [IARC Cancer Incidence in Five Continents (CI5), previous downloads](https://ci5.iarc.who.int/previous/download)

## Project files

- `Analysis.ipynb` — data review, cleaning, validation, and preparation
- `Visualize.ipynb` — interactive charts and dashboard layout
- `docs/` — HTML visualizations published through GitHub Pages
- CSV files — source datasets and prepared tables used by the notebooks

