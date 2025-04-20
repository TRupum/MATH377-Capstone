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
Highest: Highest recorded sea level that month (float) <br>
MHHW: Average hight of the higher level tide that month (float) <br>
MHW: Average hight of high water that month (float) <br>
MSL: Average hight of sea that month (float) <br>
MTL: Average hight of tide that month (float) <br>
MLW: Average hight of low water that month (float) <br>
MLLW: Average hight of low level tide that month (float) <br>
Lowest: Lowest recorded sea level that month (float) <br>
Temperature: Average temperature of the city that month (float) 

This dataset allows for a comprehensive analysis of the sea level within the city, enabling the developement and comparison of various forecasting models. 

## Methodology
1. Data prepressing and feature engineering
2. Implementation of Linear Regression, Random Forest, and SARIMA models
3. Model evaluation using other water level observations in NYC
4. Visualization of model preformance and forecast

