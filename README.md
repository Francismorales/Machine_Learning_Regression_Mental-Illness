# Machine_Learning_Regression_MentalIllness
This repository has the Jupyter Notebook, data and presentation material of a Machine Learning Regression project. The objective of the model is to estimate the rate of population in communities that have experienced any mental illness in the past year.


## ABOUT THE DATASET
A total of **820 samples** of data with **30 variables** containing US counties features like: eeconomic, demographics, family structure, education and weather. The dependent variable is the percentage of the total population of the county that has experienced some mental illness in the past year. 

Data was extracted by using web scraping, by connecting to an API and by downloading datasets directly from a webpage. 
List of data sources with links:
1. US Census Bureau: API - https://api.census.gov/data/2018/acs/acs1.json?get=[VARIABLESHERE]&for=county:*
2. National Centers for Environmental Information - https://www.ncdc.noaa.gov/
3. Substance Abuse and Mental Health Services Administration (SAMHSA) - https://www.samhsa.gov/data/report/2016-2018-nsduh-substate-region-estimates-age-group



# FILES & FOLDERS

## ML_Regression_MentalIllness.ipynb

This is the main jupyter notebook with the exploratory analysis and data modeling to solve the problem.

## data_sourcing.ipynb

This notebook has the data sourcing and general data engineering process. You do not have to run this notebook as all the source files are saved to the "DATA" folder in this repository.

## Folder: DATA
Folder with files dowloaded from data sources.
 This folder is called from the **ML_Regression_MentalIllness.ipynb**, therefore you need to make sure to have this folder and all its files saved to the directory were you run your jupyter notebook. 
 
 ## Folder: Shapefile_USA
This folder has the shapefiles  to plot data in the US map. 
