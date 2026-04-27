# WorldQuant Data Science Lab: Housing in Mexico / Brazil Real Estate Analysis

This workspace contains a WorldQuant Data Science Lab Jupyter notebook for cleaning, combining, and exploring real-estate datasets from Mexico and Brazil.

## Contents

- `015-assignment.ipynb` - main notebook with the data-cleaning and exploratory analysis steps.
- `015-assignment.html` - exported HTML version of the notebook.
- `data/mexico-real-estate-1.csv`, `data/mexico-real-estate-2.csv`, `data/mexico-real-estate-3.csv` - Mexico housing data used in the notebook.
- `data/brasil-real-estate-1.csv`, `data/brasil-real-estate-2.csv` - Brazil housing data used in the notebook.

## What the notebook does

The notebook focuses on:

- loading multiple real-estate CSV files with pandas,
- cleaning missing values and text-formatted prices,
- splitting coordinate fields into latitude and longitude columns,
- extracting state and region fields from location strings,
- converting Brazilian prices from BRL to USD,
- combining the cleaned datasets,
- exploring the merged data with summary statistics and visualizations,
- comparing home prices by region and checking the relationship between area and price.

## Data format

The CSV files include columns such as:

- `property_type`
- `state`
- `region`
- `lat` / `lon`
- `area_m2`
- `price_usd` or `price_brl`
- location helper fields like `place_with_parent_names` and `lat-lon`

## How to use

1. Open `015-assignment.ipynb` in VS Code or Jupyter.
2. Run the notebook cells top to bottom.
3. The CSV files are stored in the `data/` folder, which matches the paths used in the notebook.

## Requirements

The notebook uses:

- pandas
- matplotlib
- plotly

## Source

This notebook is part of a WorldQuant Data Science Lab assignment and includes a WorldQuant University copyright notice.