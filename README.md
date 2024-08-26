# Accident Data Analysis Project

This project involves analyzing road accident data to understand patterns and relationships between various factors such as road conditions, weather conditions, and time of day. The analysis is implemented in Google Colab using Python libraries like Pandas, Seaborn, and Matplotlib for data manipulation and visualization.

## Analysis Process

The analysis process consists of the following steps:

### 1. Data Preprocessing
- **Loading Data**: Importing the accident data from a CSV file.
- **Cleaning Data**: Handling missing values and ensuring data consistency.
- **Feature Engineering**: Creating new features if needed and encoding categorical variables.

### 2. Exploratory Data Analysis (EDA)
- **Descriptive Statistics**: Analyzing basic statistics of the dataset.
- **Visualization**: Creating plots to visualize the distribution of accidents across different factors:
  - **Top Locations**: Identifying the top 10 locations with the highest number of accidents.
  - **Road Conditions vs. Accident Severity**: Analyzing the relationship between road surface conditions and accident severity.
  - **Weather Conditions vs. Accident Severity**: Understanding how weather conditions impact the severity of accidents.
  - **Time of Day vs. Accident Severity**: Examining how the time of day influences accident severity.

### 3. Data Visualization
- **Bar Charts**: Showing the number of accidents by location, road conditions, weather conditions, and time of day.
- **Heatmaps**: Analyzing correlations between different factors.


## Key Findings

- **Top Locations**: The top 10 locations with the highest number of accidents were identified, highlighting areas that may require more attention or intervention.
- **Impact of Road Conditions**: The analysis revealed how different road surface conditions are related to the severity of accidents.
- **Weather Influence**: Insights were gained into how various weather conditions affect accident severity.
- **Time of Day**: Patterns related to the time of day when accidents occur were analyzed to understand peak times.

## The Dataset

The dataset used in this analysis is available at [Kaggle](https://www.kaggle.com/datasets/nezukokamaado/road-accident-casualties-dataset). It includes various columns such as `Accident_Severity`, `Accident Date`, `Latitude`, `Longitude`, `Road_Surface_Conditions`, `Weather_Conditions`, and more.
