# Weather & Economic Activity Analysis 
## Overview: 
This project leverages real-time weather and economic activity data using APIs to investigate the relationship between weather conditions and consumer/economic activity. The project demonstrates how to pull live data via APIs, clean and preprocess it, merge it with external datasets, and analyze correlations and trends over time. By integrating weather data (e.g., temperature, precipitation) with economic indicators (e.g., retail sales, energy consumption, or mobility data), this project provides insight into how weather impacts economic behavior.

## Problem Statement: 
Weather conditions influence human behavior and economic activity; however, extreme weather can reduce retail activity, increase energy usage, or impact transportation and employment. Measuring and analyzing these effects requires combining data from APIs with economic indicators. The goal of this project is to demonstrate the ability to pull, clean, and merge API-based datasets with static datasets and perform exploratory data analysis and analytical modeling.  

## Learning Objectives: 
1. __API Usage:__ Gain hands-on experience pulling structured JSON/CSV data from REST APIs.
2. __Data Integration:__ Merge API data with traditional economic datasets to create unified analysis-ready data.
3. __Time Series Analysis:__ Explore lag effects between weather events and economic outcomes. 

## Technologies Used:
1. __Python:__ Primary language for data processing, model training, and evaluation.
2. __Pandas:__ For data manipulation and preprocessing of large datasets.
3. __Request/HTTPx:__ For API requests and JSON data handling. 
4. __Matplotlib / Seaborn:__ For visualizing the dataset and results.
5. __Jupyter Notebooks:__ For interactive development, data exploration, and visualization.

## Data Description
1. __Weather API (OpenWeatherMap, NOAA, or Meteostat):__ Pull daily temperature, precipitation, and severe weather alerts. Covers multiple locations over time. 
2. __Economic Activity API/Dataset:__ US Census Bureau Retail Sales or FRED API
   
## Learner Growth: 
This project provided valuable hands-on experience in working with economic datasets and developing API literacy. 

## Potential Questions: 
1. Do extreme weather days correlate with lower retail sales or mobility?
2. How does average monthly temperature correlate with energy usage or retail activity?
3. Are there seasonal lag effects?
4. Can a simple predictive model be built to estimate retail sales from weather variables?

## Timeline: 
This project took about nine hours. 

## License: 
This project is licensed under the MIT License. See the LICENSE file for details.

