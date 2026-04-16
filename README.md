# King County Housing Data Analysis

This repository contains an Exploratory Data Analysis (EDA) project analyzing home sales in King County, WA. This analysis was specifically commissioned for our buyer client, **Jacob Phillips**.

## Project Objectives

The goal is to explore housing sales data to validate hypotheses about property value drivers and identify potential real estate investments that meet the client's demanding criteria.

**Client Profile (Jacob Phillips)**
- Unlimited Budget
- Preferences: 
  - 4+ bathrooms (or space for a smaller house nearby)
  - Big lot (must support a tennis court & pool)
  - Golf nearby
  - Historic home (Built before 1950)
  - No waterfront property

## Key Hypotheses Validated

1. **Luxury Bathrooms:** Do homes with four or more bathrooms command a higher average sale price than homes with fewer bathrooms? (Validated)
2. **Historic Value:** Do older historic homes (built before 1950) differ in average price from newer homes? (Validated)
3. **Location Concentration:** Are high-price luxury houses highly concentrated in specific zipcodes? (Validated)

## Contents

- `data/`
  - Contains the original dataset `king_county_house_allData.csv` (Note: not tracked via Git).
  - Contains the compiled cleaned dataset `king_county_house_cleaned.csv`.
- `2_Fetching_the_Data.ipynb`
  - Jupyter Notebook for initial data exploration, cleaning, and preparation.
- `EDA.ipynb`
  - Main Jupyter Notebook containing all visualizations, statistical tests, hypothesis validation, and client-specific filtering.
  - The script and outline for the non-technical presentation mapping to the EDA findings.

## Highlights & Client Recommendations

Based on our EDA, Jacob is advised to focus his search strictly within the top 5 luxury zipcodes. Because 4+ bathrooms are exceptionally rare in homes built before 1950, we recommend purchasing a historic large-lot property with 3+ bathrooms and leveraging the unlimited budget to construct a modern guest house and the desired sporting facilities.

## Setup & Running

This project uses Python 3.11.3.

1. Ensure the dataset `king_county_house_allData.csv` is placed in the `data/` folder.
2. Install requirements using `pip install -r requirements.txt`.
3. Run `2_Fetching_the_Data.ipynb` via Jupyter Notebook.
4. Run `EDA.ipynb`.
