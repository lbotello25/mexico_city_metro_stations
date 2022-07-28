# K-Means Clustering Analysis of Mexico City

## Introduction
Mexico City is one of the most populous cities in the world, home to one of the largest metro systems in the world. The system served 1.655 billion passengers in 2019. However, Mexico City is also ranked as one of the most congested cities in the world. This project aims to better understand neighborhoods surrounding Mexico City's metro stations.

## Data Acquisition
Two data sources were utilized for this project. Data regarding metro stations (name, location, year-built) were scraped from Wikipedia. The Foursquare Place API was utilized to obtain data of the venues 
surrounding each metro station. Any venue within a 300 m. radius of the station was considered a 
venue of such station. The data points obtained for each venue are the following: Venue Name, Venue 
Category, Latitude, Longitude, Distance (m.) from Station. 

## Predictive Modeling
K-Means clustering analysis with 3 and 4 clusters were employed. The clustering was performed based on the venues surroanding each of the 195 metro stations. The dataset contained a total of 176 different venue categories. Note, that stations with less than five venues were not included in the analysis.


Jupyter notebook contains all code used to perform analysis. PDF document briefly discusses the findings and identifies areas of improvement.


