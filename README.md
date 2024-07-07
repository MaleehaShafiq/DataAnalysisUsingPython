# Project_1
# Diwali Sales Analysis
An exploratory data analysis (EDA) in Python on sales data to uncover insights and trends in the market.
This repository contains a Python script for analyzing Diwali sales data using pandas, matplotlib, and seaborn libraries. The analysis includes exploratory data analysis (EDA) to derive insights from the sales data, focusing on various aspects such as gender, age group, occupation, and product categories.

## Data
The dataset used in this analysis is `Diwali_Sales_Data.csv`, which includes information on sales transactions during Diwali.

## Requirements
To run the code, you need the following Python libraries:
- pandas
- matplotlib
- seaborn
- numpy

You can install the required libraries using pip:
```sh
pip install pandas matplotlib seaborn numpy



# Project_2
# Airbnb Data Analysis in Paris

## Overview
This repository contains Python code for analyzing Airbnb listings data in Paris. The analysis includes data import, cleaning, visualization, and insights drawn from the data.

## Dataset
- **Source:** Airbnb Listings dataset(Maven_Analytics)

## Analysis Steps
1. **Data Import and Cleaning:**
   - Imported the Airbnb Listings dataset using Pandas.
   - Converted 'host_since' column to datetime format for time-series analysis.
   - Filtered data to focus on listings in Paris.
   - Handled missing values by dropping rows with null values.

2. **Exploratory Data Analysis (EDA):**
   - Calculated summary statistics and explored distributions of accommodation prices and neighbourhoods.

3. **Neighbourhood Analysis:**
   - Identified neighbourhoods with the highest average prices.
   - Investigated accommodation prices in the most expensive neighbourhood (Elysee) based on different accommodation capacities.

4. **Time-Series Analysis:**
   - Resampled data to analyze trends over time, grouping by year.
   - Plotted the number of new hosts and average prices over time using line plots.

5. **Visualization:**
   - Visualized average prices by neighbourhood using a horizontal bar chart.
   - Examined how the number of hosts and prices have changed over time using a dual-axis line plot.

6. **Insights:**
   - **Decrease in New Hosts:** After the 2015 regulation on Airbnb listings in Paris, the number of new hosts decreased drastically.
   - **Price Increase:** The decrease in hosts led to higher prices, indicating reduced supply and higher demand.

## Tools Used
- Python
  - Pandas for data manipulation
  - Matplotlib and Seaborn for data visualization

## Conclusion
This analysis provides insights into the dynamics of Airbnb listings in Paris, highlighting the impact of regulatory changes on the market.import pandas as pd
import numpy as np





