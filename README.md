# NOAA-Temperature-Data-Analysis
## Overview
This project analyzes daily climate records from the National Centers for Environmental Information (NCEI) using data from the Daily Global Historical Climatology Network (GHCN-Daily). The goal is to visualize record high and low temperatures from 2005 to 2014, overlaying 2015 data to identify broken records.

## Dataset
The dataset consists of two CSV files:
- **temperature.csv**: Contains daily temperature records with columns such as `id`, `date`, `element`, `Data_Value`, etc.
- **BinSize.csv**: Provides station location data, including latitude and longitude.

## Features
- Visualizes record high and low temperatures by day of the year.
- Shading between the record highs and lows.
- Scatter plot of 2015 data to highlight broken records.
- Excludes leap days from the analysis.
- Map visualization of  locations near Ann Arbor, Michigan.
- Summary statistics of temperatures for the year 2015.

## Installation
To run this project, I used Python with the following packages installed:
- pandas
- matplotlib
- plotly
- numpy
