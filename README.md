# US Honey Production Analysis

## Overview
This Jupyter Notebook (`US_Honey_Case.ipynb`) analyzes a dataset related to honey production in the United States from 1995 to 2021. The dataset includes information such as the number of colonies, yield per colony, production, stocks, average price, and value of production across various states.

## Dataset Description
The dataset (`US_honey_dataset.csv`) contains the following columns:
- `Unnamed: 0`: Index column (removed during analysis).
- `state`: The state where the honey production data was recorded.
- `colonies_number`: Number of honeybee colonies.
- `yield_per_colony`: Honey yield per colony (in pounds).
- `production`: Total honey production (in pounds).
- `stocks`: Honey stocks (in pounds).
- `average_price`: Average price per pound of honey (in dollars).
- `value_of_production`: Total value of honey production (in dollars).
- `year`: The year of the recorded data.

## Analysis Steps
1. **Data Loading and Initial Inspection**:
   - The dataset is loaded using `pandas`.
   - Basic exploration includes displaying the dataset, checking its shape, and summarizing statistics.

2. **Data Cleaning**:
   - The `Unnamed: 0` column is dropped as it is redundant.
   - Missing values are checked (none found in this dataset).

3. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics are generated to understand the distribution of numerical columns.
   - Unique states and their counts are examined.
   - The dataset is sorted by production to identify top honey-producing states.

4. **Visualizations**:
   - The notebook includes visualizations to explore trends over time or across states.

## Key Findings
- **Top Honey-Producing States**: California and North Dakota consistently rank among the highest honey-producing states.
- **Temporal Trends**: Honey production and related metrics vary significantly by year and state.
- **Price and Production**: There is an inverse relationship between average price and production in some years, suggesting economic factors at play.


