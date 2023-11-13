# CIA Country Analysis KMeans Clustering project:

# Project Description

## Overview

This project performs an exploratory analysis on countries using data from the CIA World Factbook. It aims to cluster countries into meaningful groups using k-means clustering based on socioeconomic indicators.

## Data

The key highlights about the dataset used in this project:

- The project utilizes data from the CIA World Factbook, which is an open publication produced by the US Central Intelligence Agency with profiles of 266 world entities. 

- The Factbook contains demographic, geographic, economic and societal statistics along with background information about countries and dependencies. 

- Two primary CSV files are used - CIA_Country_Facts.csv containing metrics for 266 countries, and country_iso_codes.csv mapping ISO codes to names.

- CIA_Country_Facts.csv includes over 80 quantitative and qualitative variables on topics like government, economy, people & society, energy, communications, transportation and military for each country.

- Some key variables include GDP, population, income/poverty levels, healthcare access, education rates, disease prevalence, natural resources, infrastructure and military strength. 

- The large, multi-dimensional nature of the dataset with variables spanning diverse socioeconomic indicators makes it suitable for exploratory analysis and modeling of relationships between development factors across nations.

- The Factbook is an open, authoritative source maintained by CIA for transparency, making the data reliable and routinely updated for current statistical baselines on all UN member countries and observers.

So in summary, the CIA World Factbook provides a comprehensive repository of structured, multifaceted data on countries globally to power informative analyses like the one presented in this project.

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
