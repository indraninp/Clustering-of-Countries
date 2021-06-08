# Clustering-of-Countries
Categorise the countries using Clustering Models (both K-means and Hierarchical Clustering) based on some socio-economic and health factors that determine the overall development of the country. This is to help an NGO to choose the countries that it needs to focus on for disbursement of economic aid.

## Introduction
HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It runs a lot of operational projects from time to time.

They have been able to raise around $ 10 million from funding sources. They now need to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid.

Therefore it is required to categorise the countries using some socio-economic and health factors that determine the overall development of the country, so that the countries on which the HELP International NGO needs to focus on the most can be suggested.

## Project Description
The data is cleaned, wrangled and then Exploratory Data Analysis & Outlier treatment is performed using python and its libraries. The data is prepared for modelling by scaling and standardization techniques. Hopkins statistic is calculated to check if the data is suitable for clustering. The optimal number of clusters is found by elbow-curve and silhouette score methods, the number chosen would also be appropriate from our business perspective. Clustering is performed using both K-Means and Hierarchical clustering. We have analyzed gdpp, child_mort and income using boxplots and scatterplots. These are the factors used to categorise the countries. Presented findings with relevant statistics and visualizations using the matplotlib and seaborn libraries.

## Technologies Used
Python

Libraries: pandas, numpy, matplotlib, seaborn, sklearn, scipy

Jupyter Notebook

## Results
Used both K-Means and Hierarchical clustering to categorise the countries using some socio-economic and health factors, and identified the countries which are in dire need of aid. We have obtained the same set of countries using both the K-Means and Hierarchical clustering methods, which rank lowest in terms of gdpp and income, and highest in child mortality. The list of countries are then suggested to the organization for providing funding.
