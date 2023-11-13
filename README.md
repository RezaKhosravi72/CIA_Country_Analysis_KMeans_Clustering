# CIA Country Analysis KMeans Clustering project:

# Project Description

## Overview

This project performs an exploratory analysis on countries using data from the CIA World Factbook. It aims to cluster countries into meaningful groups using k-means clustering based on socioeconomic indicators.

## Data

The datasets used are:

- CIA_Country_Facts.csv: Contains demographic and economic metrics for 266 countries/regions from the CIA Factbook. 

- country_iso_codes.csv: Maps ISO country codes to country names.

- Online Link: https://www.kaggle.com/datasets/lucafrance/the-world-factbook-by-cia 

## Objective

The objective is to gain insights into natural clusters or groupings of countries based on factors like GDP, population, health, education etc. This can help understand relationships between development indicators across nations.

## Methodology

The steps are:

1. Data Loading and Preprocessing 

2. Feature Selection: Choose relevant quantitative metrics like GDP, population etc. 

3. Data Standardization 

4. Elbow Method to find optimal k value for k-means clustering

5. Perform k-means clustering with k=5 

6. Analyze and visualize clusters 

7. Identify major patterns and relationships between countries within each cluster

## Key Insights

- 5 distinct country clusters are identified 

- Cluster 1 contains developed countries with high GDP, education etc

- Cluster 2 shows developing Asian/Latin American countries 

- Cluster 3 consists of impoverished African nations

- Cluster 4 are eastern European countries transitioning to market economies

- Cluster 5 has very poor, unstable and often war-torn regions

The analysis yields meaningful grouping of countries based on core development metrics to better understand global socioeconomic landscapes.
