# WW2 Weather Conditions Analysis

## Overview
This project explores the weather conditions during World War II and investigates the impact of weather on aerial bombing operations. The analysis aims to understand temperature changes, precipitation, wind speed, and other weather-related factors during the war period.

## Dataset
The weather data used in this analysis is sourced from the United States National Oceanic and Atmospheric Administration (NOAA) National Centers for Environmental Information website. The dataset contains daily weather records from various weather stations around the world, including information on precipitation, snowfall, temperatures, wind speed, and other weather conditions.

Dataset Link: [World War II Era Data - NOAA](https://www.ncdc.noaa.gov/data-access/land-based-station-data/land-based-datasets/world-war-ii-era-data)

## Contributors
- [Abhishek](https://github.com/Night0Fury)
- [Bharathwaj](https://github.com/BharathwajManoharan)

## Analysis Steps
1. Data Loading: The weather data is loaded from the provided dataset, and missing or irrelevant columns are removed.
2. Data Cleaning: Non-numeric values in relevant columns, such as 'Precip', 'MaxTemp', and 'MinTemp', are handled to prepare the dataset for analysis.
3. Exploratory Data Analysis (EDA): Various data visualization techniques are used to gain insights into temperature changes, precipitation patterns, and other weather-related trends during World War II.
4. Linear Regression: A linear regression model is built to predict MaxTemp based on other weather factors. The accuracy of the model is evaluated using R-squared (R2) score.
5. Polynomial Regression: A polynomial regression model is applied to explore non-linear relationships between variables and predict MaxTemp. The model's accuracy is evaluated using R-squared (R2) score.
6. Random Forest Regression: A random forest regression model is built to predict MaxTemp and assess its performance using R-squared (R2) score.

## Conclusion
The analysis of World War II weather conditions helps us understand the impact of weather on aerial bombing operations. Through exploratory data analysis and regression models, we gain insights into temperature changes, precipitation patterns, and other weather-related factors that may have influenced historical events during the war.

## How to Use
1. Clone the repository to your local machine.
2. Ensure you have the necessary Python libraries installed (Pandas, NumPy, Seaborn, Matplotlib, scikit-learn).
3. Run the Jupyter Notebook to perform the analysis and view the visualizations.
4. Explore the findings and insights from the project to gain a better understanding of World War II weather conditions.

Feel free to contribute, provide feedback, or use the code and analysis for further research.
