# Weather Real-Time Pakistan Cities Data Analysis

## Description
Welcome to the **Weather Real-Time Pakistan Cities Data Analysis** project! This Python-based application leverages the OpenWeather API to fetch real-time weather data for various cities across Pakistan. The primary goal of this project is to collect, analyze, and visualize key weather parameters such as temperature, humidity, wind speed, and cloudiness.

## Project Structure

### Part 1: Data Scraping (Data Collection)
- Utilizes the OpenWeather API to gather real-time weather data.
- Collects detailed information, including:
  - Temperature
  - Humidity
  - Wind Speed
  - Cloudiness
  - Weather Description
- Stores the collected data in a structured format (CSV or DataFrame) for easy access and analysis.

### Part 2: Data Exploration
- Loads the dataset and inspects its structure to understand the features.
- Conducts initial exploration to analyze summary statistics for numerical and categorical variables.

### Part 3: Data Cleaning
- Handles missing values by filling them or dropping duplicates.
- Converts date/time columns (e.g., Sunrise, Sunset) to appropriate data types.
- Normalizes column names for consistency and removes unnecessary data.

### Part 4: Exploratory Data Analysis (EDA)
- Analyzes the distribution of numerical variables like temperature and humidity.
- Explores correlations between different weather features.
- Investigates outliers and patterns within the dataset.
- Groups and compares weather conditions across various cities.

### Part 5: Data Visualization
- Employs Seaborn and Matplotlib to create compelling visualizations:
  - Histograms, scatter plots, box plots, and heatmaps.
- Plots trends in weather conditions across different cities.
- Visualizes relationships between variables such as temperature vs. humidity and cloudiness vs. wind speed.

## Dataset
The dataaset used for this project is sourced from Kaggle, specifically from the "Population of Pakistan" dataset. You can access it [here](https://www.kaggle.com/datasets/mabdullahsajid/population-of-pakistan-dataset). This dataset provides valuable demographic information that can enhance the analysis of weather data across various cities in Pakistan.

## Technologies Used
- Python
- OpenWeather API
- Pandas
- NumPy
- Seaborn
- Matplotlib
