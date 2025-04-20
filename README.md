# MATH377-Capstone
## Project Overview
### Problem Area
This project aims to address the issue of predicting changing water levels and its corrolations with temperature and other factors specifically in NYC. The key issues include:
  - Predicting water level based on time of year
  - Predicting water level based on overall temperature of the city
  - Optimizing city infurstructure
  - Predicting increases in possible flood events

### Affected Stakeholders
- Homeowners
- Construction and maintinance companies
- NYC government
- Home insurance companies
- Environmental protection agencies
- NYC Residents

### Proposed Data Science Solution
Develop various forcasting models to acurately predict the the average sea level in NYC in any given given month and/or temperature. In order to do this the following models will be used: 
  - Linear Regression
  - Random Forest
  - SARIMA (Seasonal Autoregressive Integrated Moving Average)
These models will:
  - Predict predict average, high, and low sea levels based on historical data and weather conditions
  - Compare the preformance of different modeling techniques
  - Provide insight on the factors influencing sea level

### Impact
The potential impacts of this project includes: 
- Increased flood preparation by government agencies, companies, and individiuals
- More optimized maintinance schedules for buildings, subway stations, bridges, etc.
- Better prepare residents for possible high-risk flood months

## Dataset Description
My analysis utilizes datasets containing measures of sea level and temperature information from New York City from 1950 to 2025. The datasets includes: 
  - Monthly mean termperature readings
  - Monthly sea level reading from the Battery Observatory

### Data Dictionary
Date: Date of observation (date) <br>
Highest: Highest recorded sea level that month in ft (float) <br>
MHHW: Average hight of the higher level tide that month in ft (float) <br>
MHW: Average hight of high water that month in ft (float) <br>
MSL: Average hight of sea that month in ft (float) <br>
MTL: Average hight of tide that month in ft (float) <br>
MLW: Average hight of low water that month in ft (float) <br>
MLLW: Average hight of low level tide that month in ft (float) <br>
Lowest: Lowest recorded sea level that month in ft (float) <br>
Temperature: Average temperature of the city that month in ºF (float) 

This dataset allows for a comprehensive analysis of the sea level within the city, enabling the developement and comparison of various forecasting models. 

## Methodology
1. Data prepressing and feature engineering
2. Implementation of Linear Regression, Random Forest, and SARIMA models
3. Model evaluation using other water level observations in NYC
4. Visualization of model preformance and forecast

### Restults
This project will compare the preformance and accuracy of the differnt models in predicting different sea level measurements. This will be visualized as: 
- Bar graphs showing MAE for each model and different sea level measurements
- Heatmap visualizing MAE across models and different sea level measurements

### Limitations 
- Geographic Scope: The analysis focuses on a specific location along the hudson river in manhattan, which may not be very indicative of other parts of the city or world
- Limited scope of input variables: This analysis only takes into account time and temperature as input variables and does not account for weather events, pressure, human activity, etc.
- Temporal resolution: Monthly data may not capture short-term fluctuations in wave hight and tidal forces

### Future Works
- Include data from other sea level stations and labratories across NYC and the United States
- Include data from weather stations and other climate measurements
- Include water quality indicators
- Include data that breaks down sea level and tidal hight at a daily or hourly scale
- Expand the model to estimate amount of damage done to structures and property due to flooding
- Explore the use of multiple differnt models 
