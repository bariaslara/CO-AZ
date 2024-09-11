# CO-AZ
CO Concentration Analysis: 2022 vs 2023

## Project Overview

This project analyzes and compares carbon monoxide (CO) concentration levels in 2022 and 2023, using publicly available data. The analysis focuses on the average daily maximum 8-hour CO concentration for each month and for various monitoring sites. The project is built in Python, utilizing `pandas` for data manipulation and `matplotlib` for visualization.

## Data Source

The data used in this project is stored in CSV files:
- `ad_viz_plotval_data-2022.csv`: CO concentration data for the year 2022.
- `ad_viz_plotval_data-2023.csv`: CO concentration data for the year 2023.

Date obtained from EPA:
-https://www.epa.gov/outdoor-air-quality-data/download-daily-data

## Key Tasks
1. Data Loading & Preprocessing:
   - The CSV files are read using `pandas`, and the `Date` column is converted to a `datetime` data type.
   - Data was condensed to include only relevant columns: Date, CO concentration, and local site name.
   
2. Monthly CO Concentration Averages:
   - Extracted the month from the date.
   - Calculated the average monthly CO concentration for both 2022 and 2023.

3. Site-Specific CO Concentration Averages:
   - Calculated the average CO concentration at each monitoring site for 2022 and 2023.

4. Visualization:
   - Created line plots comparing monthly average CO levels between 2022 and 2023.
   - Plotted site-specific average CO concentrations for both years.

## Results

- Monthly Averages: CO concentration trends across months in 2022 and 2023 were plotted, showing year-on-year comparisons.
- Site-Specific Averages: Visualization of CO concentration levels across various local monitoring sites, highlighting differences between 2022 and 2023.

## Libraries Used
- `pandas`
- `matplotlib`
- `datetime`

## Visualizations

1. Monthly Average CO Concentration
2. Site-Specific Average CO Concentration



