# Water-Quality-Hilo-Bay

# Effects on Water Quality from Environmental Conditions on Hilo Bay

This project analyzes the relationship between water quality in Hilo Bay, Hawaii, and various environmental conditions, particularly focusing on how storms impact variables such as turbidity, salinity, chlorophyll, dissolved oxygen, and temperature. The data was collected using a Water Quality Buoy, set up by Dr. Jason Adolf, which recorded water quality metrics in Hilo Bay four times every hour over several years.

## Project Overview

The primary objective of this project is to understand how environmental factors like rainfall and river flow affect the water quality in Hilo Bay. We aim to identify patterns and relationships between these environmental conditions and water quality parameters by using time series analysis and Vector Autoregressive (VAR) models.

### Key Objectives:
- Determine the relationship between water quality variables (turbidity, salinity, chlorophyll, dissolved oxygen, temperature) and river flow.
- Analyze the impact of storms on water quality using time series plots.
- Develop and apply Vector Autoregressive (VAR) models to understand the interaction between variables over time.
- Utilize Impulse Response Models to predict the effects of environmental changes on water quality.

## Data and Methodology

1. **Data Collection**: The data was collected by a Water Quality Buoy in Hilo Bay from October 23, 2010, to December 31, 2016. Due to equipment malfunctions, a subset of data from January 1, 2013, to December 31, 2015, with fewer missing values, was used for analysis.

2. **Time Series Analysis**: Plots were created to understand how variables behaved over time, especially during storm events. We identified 72 storms within the dataset to analyze their impact on water quality.

3. **Vector Autoregressive (VAR) Models**: VAR models were employed to explore the interactions between river flow and other water quality variables. The models examined how shocks to one variable, such as an increase in river flow, affected others.

4. **Assumptions Testing**: We tested for stationarity, serially correlated errors, and homoscedasticity to validate the VAR models. Most models failed to meet the assumptions, indicating the need for further refinement.

## Key Findings

- **Storm Impact**: Time series plots indicated that storms generally led to an increase in turbidity and a decrease in salinity and dissolved oxygen.
- **VAR Model Insights**: Initial VAR models suggested interactions between river flow and water quality variables. However, due to unmet assumptions (stationarity, serial correlations, homoscedasticity), these models were not valid for making definitive conclusions.

## Future Directions

- **Improving Data Collection**: Continuous data collection with minimal interruptions would provide a more robust dataset for analysis.
- **Additional Buoys**: Placing additional buoys in different locations around Hilo Bay could help in understanding the spatial variation in water quality.
- **ARMA Modeling**: Consider using Autoregressive Moving Average (ARMA) models or seasonal ARMA models to better capture the patterns in the data.

