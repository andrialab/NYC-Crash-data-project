# Motor Vehicle Collision Analysis - NYC

## Overview
This project focuses on analyzing **motor vehicle collisions** in New York City. It includes data preparation, cleaning, and visualization to identify trends and insights into crash incidents. The analysis covers key metrics such as injuries, fatalities, and vehicle involvement, leveraging **Python** and popular data science libraries.

## Features
- **Data Cleaning & Preprocessing**: Handling missing values, filtering incorrect data, and standardizing formats.
- **Exploratory Data Analysis (EDA)**: Statistical summaries and visualizations of key crash metrics.
- **Time Series Analysis **: Examining accident trends over time to identify seasonal patterns and long-term changes.
- **Geospatial Analysis**: Mapping crash locations using **Folium**.
- **Ethical Considerations**: Assessing bias and fairness in the dataset.

## Data Sources
The dataset is sourced from [NYC Open Data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data), specifically **Motor Vehicle Collisions - Crashes**.

## Example Insights and Outcomes
- The average number of injuries per crash is **0.305**.
- Fatalities are rare, with an average of **0.00146** deaths per crash.
- A significant proportion of crashes occur at high-traffic intersections, suggesting the need for better traffic regulation.
- Analysis of vehicle types indicates that larger vehicles, such as trucks, are involved in more severe accidents compared to smaller vehicles.
- Time-of-day analysis reveals that peak traffic hours correspond with a higher frequency of accidents, emphasizing the importance of rush-hour traffic management strategies.
- **Pre-COVID vs. Post-COVID Trends**: Pre-COVID, the highest accident rates occurred during **morning (7-9 AM) and evening (5-7 PM) rush hours**, while post-COVID saw a shift toward more **afternoon (12-3 PM) incidents**, likely due to changes in commuting patterns and remote work.
- **High-Risk Locations**: The **most accident-prone areas** include **Midtown Manhattan, the Bronx's Grand Concourse, and intersections along Flatbush Avenue in Brooklyn**.
- **Leading Causes of Accidents**: The most frequent causes include **distracted driving, speeding, and failure to yield**. Additionally, **weather-related factors** (such as rain and snow) significantly increase accident occurrences.

## Technologies Used
- **Python**
  - **Pandas**: Data manipulation and cleaning
  - **Matplotlib & Seaborn**: Data visualization and statistical analysis
  - **Folium**: Interactive geospatial mapping
  - **NumPy**: Numerical computations and array operations
  - **Scikit-learn**: Basic machine learning applications for pattern detection
  - **GeoPandas**: Geospatial data analysis

