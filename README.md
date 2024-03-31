# Airbnb Listings & Reviews Exploratory Data Analysis

## Project Overview
This project involves a detailed exploratory data analysis of the Airbnb Listings & Reviews dataset. The primary goal is to uncover insights into the factors that influence listing prices, understand the characteristics of the listings, and provide a data-driven view of the Airbnb market landscape.

## Dataset
The dataset includes several features related to Airbnb listings such as physical attributes, host information, pricing, availability, and guest reviews. The data spans multiple cities and includes a diverse range of accommodation types.

## Key Features Analyzed
- Room types and their impact on pricing
- Price distribution and its normalization
- Correlations among listing attributes, especially related to price
- Presence and impact of outliers in the data
- Review scores and their relationship with listing attributes


## Key Findings
The EDA revealed:
- Room type as a significant determinant of pricing.
- Price distribution's right skewness, normalized through log transformation.
- Positive correlations between price and the number of guests a listing can accommodate, number of bedrooms, and review scores related to location.
- Outliers indicating luxury listings or potential data entry errors.

## Conclusions & Recommendations
The analysis suggests potential for price optimization based on room type, size, and location quality. Hosts and Airbnb could use these insights to adjust pricing strategies and enhance listing quality for better guest satisfaction.

## Usage
To explore the Jupyter notebooks and run the analysis:
1. Ensure Python and Jupyter are installed on your system.
2. Install the required packages using `pip install -r requirements.txt`.
3. Navigate to the `notebooks/` directory and open `Exploratory_Data_Analysis.ipynb`.

## Future Work
Suggested areas for further analysis include predictive modeling to determine pricing strategies and deep dives into guest preferences.
