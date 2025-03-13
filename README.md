# Fitness Data Analysis: Centralized Visualization Tool

This repository contains the code and data for a project focused on creating a centralized visualization tool for fitness lifestyle and achievements among friends and coworkers. The goal is to provide a platform to share and analyze fitness data, fostering motivation and community.

## Project Overview

This project aims to aggregate and visualize fitness data from various sources (specifically Garmin activities) to create a comprehensive overview of fitness activities. Key aspects include:

* **Data Aggregation:** Collecting fitness data from multiple individuals and sources.
* **Data Processing:** Cleaning, transforming, and preparing the data for analysis.
* **Visualization:** Creating interactive dashboards in Power BI to showcase fitness achievements, trends, and geolocation data.
* **Community Building:** Providing a platform for friends and coworkers to share and compare their fitness activities.

## Contents

* `Data/`: Contains the raw and processed fitness data.
    * `Actividades AARL 1 año.csv`: Fitness activity data for user AARL (1 year).
    * `Actividades JJ 1 año.csv`: Fitness activity data for user JJ (1 year).
    * `Activities AMG.csv`: Fitness activity data for user AMG.
    * `Activities CCO.csv`: Fitness activity data for user CCO.
    * `Activities KMP 1 año.csv`: Fitness activity data for user KMP (1 year).
    * `Codigos Codazzi.csv`: Codazzi codes (potentially for geolocation data).
    * `DimUser.xlsx`: User dimension table (potentially for user information).
    * `Fitness track.xlsx`: Consolidated fitness tracking data.
    * `Garmin activities AR.xlsx`: Garmin activity data for user AR.
* `Importing Garmin activities with Python.ipynb`: Jupyter Notebook for importing and processing Garmin activity data using Python.
* `Flujo Garmin.bak`: Backup file for Alteryx workflow.
* `Flujo Garmin.yxmd`: Alteryx workflow for data processing.
* `README.md`: This file.

## Methodology

1.  **Data Collection:** Gathering fitness activity data from Garmin devices and other sources.
2.  **Data Processing:**
    * Using Python (`Importing Garmin activities with Python.ipynb`) to import and process Garmin activities.
    * Utilizing Alteryx (`Flujo Garmin.yxmd`) for data cleaning, transformation, and integration.
    * Merging and consolidating data from multiple sources into `Fitness track.xlsx`.
3.  **Data Analysis:** Analyzing fitness data to identify trends, patterns, and key metrics. This project analyzes fitness data to gain insights into activity patterns and user behavior. The analysis includes descriptive statistics, data visualization, and K-Means clustering. Descriptive analysis provides an overview of the dataset, including distributions of key variables such as 'Activity Type' and 'Distance'. Visualizations, such as histograms, bar charts, and correlation heatmaps, illustrate relationships between variables and distributions of data[cite: 1, 2, 3]. K-Means clustering is used to identify groups of activities based on features like 'Activity Type', 'Distance', and 'userID'. The clustering results are further analyzed by examining the distribution of users and activity types within each cluster, providing insights into the characteristics of the identified groups.
4.  **Dashboard Development:** Creating interactive dashboards in Power BI to visualize fitness achievements, average sports practices, geolocation data, and other relevant metrics. (Dashboard in progress)
5.  **Visualization:** Creating visualizations to represent the analysis results.

## Technologies Used

* **Python:** For data importing and processing.
* **Pandas:** For data manipulation and analysis in Python.
* **Alteryx:** For data workflow and transformation.
* **Power BI:** For interactive dashboard development and visualization.
* **Excel:** For data storage and manipulation.
* **CSV:** For data storage.

## Future Enhancements

* Complete the Power BI dashboard with interactive visualizations for all key metrics.
* Integrate data from additional fitness tracking platforms.
* Add features for social interaction and community engagement.
* Implement automated data updates to keep the dashboard current.
* Add geolocation visualizations to show activity locations.

## Usage

1.  Clone the repository: `git clone [repository URL]`
2.  Navigate to the `Data/` directory to explore the fitness data.
3.  Open `Importing Garmin activities with Python.ipynb` in Jupyter Notebook to understand the data import process.
4.  Review the `Flujo Garmin.yxmd` Alteryx workflow (if you have Alteryx) to understand the data transformation steps.
5.  (Once completed) Open the Power BI dashboard to explore the interactive visualizations.

## Contact

[Alejandro Rodriguez Lozano]

[alejo1109@gmail.com]

[https://www.linkedin.com/in/andalejo/]
