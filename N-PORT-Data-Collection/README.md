## Overview
This folder provides the data-scraping tools (Python) and additional data-cleaning functions (R). We have provided a small Python script to generate the SQL tables, but database creation and data import are left to the user.

## File Descriptions
- nport_data_scraping.ipynb provides functions that the user can utilize to create their own Form N-PORT holdings database.
- SQL_table_structure.ipynb is the SQL table format necessary to run R2000_Deltas.qmd
- R2000_Deltas.qmd provides functions in R that were used to create the holding deltas, which are the focus of my work on analyzing the data. This file can be used to reproduce the results in my thesis.
- cleaned_crsp_with_universe.RDS is a necessary data file needed to run R2000_Deltas.qmd. This file provides CRSP daily price data for the R3000 2023 composition. 
