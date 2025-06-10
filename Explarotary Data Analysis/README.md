# Apartment Sale Listings Analysis

This project analyzes an archive of apartment sale listings from the Yandex Real Estate service, covering St. Petersburg and nearby localities over several years. The main goal is to identify the key factors that influence the market value of real estate properties and to build an understanding of the real estate market in the region.

## Dataset

The dataset contains user-provided and automatically generated information for each apartment listing, including:
- Total area, living area, kitchen area
- Number of rooms, floor, total number of floors
- Listing price, date of publication
- Distance to city center, parks, and bodies of water
- Number of parks, ponds, and balconies nearby
- Other features such as whether the property is an apartment

## Main Points and Research Goals

- Data cleaning and preprocessing: handling missing values, correcting data types, and removing duplicates
- Feature engineering: adding new columns such as price per square meter, day/month/year of publication, floor type, and distance to city center in kilometers
- Exploratory data analysis: studying the distributions and outliers of key features
- Identifying the main factors affecting property prices using correlation analysis and visualizations
- Analyzing the speed of apartment sales and identifying quick and long sales
- Comparing average price per square meter across the most popular localities
- Investigating how the distance from the city center affects property prices

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn

The project provides insights into the real estate market and can help in building automated systems for anomaly detection and price estimation.
