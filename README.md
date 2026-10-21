# Los Angeles Airbnb Pricing Analysis

## Overview

This project analyzes Airbnb listing prices in Los Angeles County using March 2025 data from Inside Airbnb. The analysis examines how nightly prices vary by property type, location, and listing characteristics, with a focus on factors relevant to short-term rental investment decisions.

## Project Files

- **[Jupyter Notebook](los_angeles_airbnb_pricing_analysis.ipynb)** - Full Python analysis, including data cleaning, exploratory data analysis, statistical inference, and probability modeling.
- **[Presentation](presentation/airbnb_pricing_analysis.pdf)** - Summary of key findings, visualizations, and recommendations.

## Tools and Methods

**Tools:** Python, pandas, NumPy, Matplotlib, Seaborn, SciPy, Jupyter Notebook

**Methods:**
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Correlation analysis and data visualization
- Bootstrap resampling and confidence intervals
- Probability distribution modeling

## Key Findings

- **Price distribution:** Nightly prices are right-skewed, with a median of $144 and a mean of $231.60.
- **Room type:** Entire homes and apartments have higher average nightly prices than private rooms. The bootstrap 95% confidence interval for the difference in means was $170.86–$186.43.
- **Listing characteristics:** Property size, room type, and location are associated with differences in nightly prices.
- **Investment considerations:** Nightly price alone does not determine profitability. Occupancy, operating costs, and seasonal demand would need to be considered.

## Dataset

**Source:** [Inside Airbnb](https://insideairbnb.com/get-the-data/)

The analysis uses the March 2025 Los Angeles County listings dataset, containing 45,031 listings before cleaning.

To reproduce the analysis, download the corresponding detailed listings dataset and save it as `aan505_fa_listings.csv` in the project directory.

## Limitations

The analysis uses advertised nightly prices rather than actual booking revenue. Results may also be affected by missing data, excluded observations, and differences in listing characteristics.

Future analysis could incorporate occupancy rates, seasonal pricing, and operating expenses to better assess investment profitability.
