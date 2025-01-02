## Analyzing Bike Rental Demand in Seoul
### Team: Akshitha Shankar, Vahin Vuppalanchi, Ray Chang, Will Dannacher

### Overview:
This project explores the factors influencing hourly bike rental demand in Seoul's bike-sharing system, Ddareungi (Seoul Bike). By analyzing weather conditions, temporal variables, and rental trends, the study aims to predict rental demand and provide actionable insights to ensure a stable bike supply across the city. The insights help optimize operations, reduce waiting times, and enhance user satisfaction.

### Dataset Summary:
The dataset includes 8,760 hourly records of bike rentals, weather conditions, and temporal features. It consists of 14 variables such as:
- Rented Bike Count: The target variable indicating the number of bikes rented per hour.
- Date and Hour: Temporal features to capture daily and hourly patterns.
- Weather Conditions: Variables such as temperature (°C), humidity (%), wind speed (m/s), visibility (m), and solar radiation (MJ/m²).
- Precipitation: Snowfall (cm) and rainfall (mm).
- Holiday Indicator: Whether the day is a holiday.

### Objectives:
Identify key factors influencing bike rental demand.
Build predictive models to estimate hourly rental counts.
Visualize temporal and weather-based rental patterns to derive actionable insights.

----------------------- Data Preprocessing ----------------------- 
- Created dummy variables to convert categorical data into binary format
- Converted climate-based columns into percentage for easier interpretation
- Split the data ranges into bins to efficiently categorize them
- Filtered data to include only relevant days
- DateTime formatting
- Calculated derived features based on categorical columns

----------------------- Data Visualization ----------------------- 
- Histograms, scatter plots, and box plots are used extensively to understand the distribution and relationships among variables
- PairGrid is applied to examine pairwise relationships
- Scatter plots with regression lines visualize the correlation between "Rented Bike Count" and factors like temperature, rainfall, and snowfall

----------------------- Statistical Analysis ----------------------- 
- Correlation coefficients and p-values for: 
  - Temperature and rented bike count.
  - Rainfall and rented bike count.
  - Snowfall and rented bike count.

(ANOVA and Two-Sample t-Test)
