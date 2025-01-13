# Spot Price Optimization Project

## Overview

This project explores the relationship between electricity spot prices, weather conditions, and energy production and consumption data in Norway. By analyzing this data, the project aims to develop an optimization model that can minimize price volatility and enhance market efficiency in the Norwegian energy market. The goal is to uncover patterns and insights that can inform decision-making and optimize electricity pricing strategies.

## Project Goals

- **Data Analysis:** Analyze the impact of weather factors (precipitation, temperature, snow depth) on electricity spot prices and how these factors correlate with production and consumption.
- **Outlier Detection:** Identify and handle outliers in the data, which may arise from issues such as incorrect formatting or data recording errors.
- **Optimization Model:** Build an optimization model based on the analysis to suggest strategies for reducing price volatility and improving efficiency in energy trading.
- **Visualization:** Create visual representations of the data, including plots and graphs, to better understand the relationships between different variables.

## Data Sources

- **Spot Price Data:** Historical spot prices for electricity in Norway.
- **Weather Data:** Precipitation, snow depth, and temperature data for different locations in Norway.
- **Energy Production & Consumption Data:** Data on electricity production and consumption across various periods.

## Methodology

1. **Data Preprocessing:**
   - Cleaning data (handling missing values, correcting formatting issues such as incorrect decimal placements).
   - Merging datasets to integrate weather and energy production/consumption data with spot price data.
  
2. **Exploratory Data Analysis (EDA):**
   - Using statistical analysis and visualizations (e.g., scatter plots, boxplots) to explore the relationships between spot prices, weather data, and production/consumption metrics.
   - Identifying potential outliers and errors in the data using techniques like the Interquartile Range (IQR).

3. **Model Development:**
   - Developing an optimization model to predict price fluctuations and suggest operational adjustments that minimize volatility.
   - Exploring machine learning approaches, including regression analysis or other predictive models, to forecast future spot prices based on weather and energy consumption patterns.

4. **Evaluation & Results:**
   - Evaluating the model’s performance using metrics such as Mean Squared Error (MSE) or other relevant indicators.
   - Presenting the results in the form of recommendations for energy market participants.
