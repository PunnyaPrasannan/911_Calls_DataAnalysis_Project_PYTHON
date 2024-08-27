# 911 Calls Data Analysis Project

This project analyzes 911 call data from Montgomery County, Pennsylvania, sourced from Kaggle.com. The goal of this analysis is to explore the dataset, create new features, and visualize trends and patterns in emergency calls using Python's data analysis and visualization libraries.

## Project Overview

The dataset consists of 911 emergency call records with the following fields:
- **Latitude** and **Longitude**: Geographic coordinates of the call location.
- **Description**: Type of emergency.
- **Zip Code**: Postal code of the area where the call was made.
- **Title**: Specific title of the emergency call.
- **Timestamp**: Date and time of the call.
- **Township**: Area or region of the call.
- **Address**: Address string where the emergency occurred.
- **E**: It's just a dummy variable it's always one.

The objectives of this project are:
1. **Data Import and Setup**: Load the data into a pandas DataFrame and perform initial setup.
2. **Exploratory Data Analysis (EDA)**: 
   - Answer specific questions related to the dataset.
   - Generate summary statistics and uncover hidden trends.
3. **Feature Engineering**:
   - Create new features from existing data, such as extracting date and time components from timestamps.
4. **Visualization**:
   - Create bar plots to visualize categorical data.
   - Generate line plots to observe trends over time.
   - Produce heatmaps and cluster maps to identify geographical or temporal clusters in the data.

## Libraries Used

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib**: For basic plotting and visualizations.
- **seaborn**: For advanced visualizations, such as heatmaps and cluster maps.

## Key Visualizations

- **Bar Plots**: To visualize the frequency of different types of emergency calls.
- **Line Plots**: To analyze trends over time, such as the number of calls per month or day.
- **Heatmaps**: To show the intensity of calls over time and across geographical areas.
- **Cluster Maps**: To identify clusters or patterns in the data, helping to uncover hidden insights about call locations and times.
