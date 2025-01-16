# Weather Data Analytics

This project focuses on exploratory data analysis (EDA) of a weather dataset. The goal is to derive meaningful insights into weather conditions, trends, and other statistics using Python and Jupyter Notebook.

## Project Overview

The weather dataset contains hourly observations of various weather-related attributes such as temperature, humidity, visibility, and wind speed. This project covers the following steps:

- **Data Loading and Cleaning:** Importing the dataset and preparing it for analysis.
- **Exploratory Data Analysis (EDA):** Investigating key trends and statistics.
- **Data Filtering and Insights:** Extracting meaningful insights based on specific conditions.

## Key Features

1. **Dataset Overview:**
   - Displayed dataset structure (shape, columns, data types, etc.).
   - Identified unique and missing values.
   - Renamed columns for better clarity.

2. **Statistics and Calculations:**
   - Calculated mean visibility, standard deviation of pressure, and variance of relative humidity.
   - Counted specific weather conditions (e.g., number of occurrences of 'Clear' weather).

3. **Filtering and Conditional Analysis:**
   - Filtered data for specific weather conditions:
     - Weather = 'Clear'
     - High wind speed and specific visibility levels
   - Combined conditions to analyze trends in 'Clear' weather with high humidity or visibility.

## Dependencies

This project uses the following Python libraries:

- **pandas:** For data manipulation and analysis.
- **numpy:** For numerical calculations.
- **jupyter:** To create and run interactive notebooks.
