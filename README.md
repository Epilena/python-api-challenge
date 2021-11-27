# python-api-challenge
weather api project

Introduction

In this project the OpenWeatherMap API was utilized to pull the weather of 500+ cities across the world with varying distance from the equator.  A Python script was used to pull the weather data and create a CV file.  On the second portion of the project the city data obtained in the first section is analyzed using jupyter-gmaps and the Google Places API to create a heat map displaying humidity and hotels near cities with ideal vacation temperature.

Methods

Completion of this project required the use of the .gitignore file to store API keys.  Python via Jupyter notebook was utiilzed to create the script for the API call. Citipy is the Python library used.  Scatter plots were creating utilizing matplotlib.  Linear Regression was processed using scipy.  To complete the project jupyter-gmaps and Google Place APi was used.  

Analysis/Results

The world city data revealed max tempatures dropped as latitude increased and cities locations moved north from the equator.  There is a negative relationship between maximum temperature and going north in the northern hemisphere.  

![LatTemp](https://user-images.githubusercontent.com/88807979/143720218-5ea785a1-3621-4558-a1b7-140665917846.png)

The interpretation of the graph is as latitude increases (travel north) maximum temperature decrease.  The high R-squared value of 0.79,represents the regression model is representative of the data.

![N Hemisphere Temp vs Latitude Regression](https://user-images.githubusercontent.com/88807979/143720229-a040ca63-b538-4514-9170-d1f25231bf6f.png)

The southern hemisphere max temperature regression model reflects a positive relationship.  In the southern hemisphere as latitude increases and moves closer to the equator, the maximum temperature of the cities increase. 

![S Hemisphere Temp vs Latitude Regression](https://user-images.githubusercontent.com/88807979/143720301-bc942671-f845-42d4-965f-842aee17cca1.png)

A dataframe was created down to six cities and a hotel map created with a marker layer. 

![Hotel Marker Map](https://user-images.githubusercontent.com/88807979/143720470-4535a881-d9ca-4d1d-88d8-7679298f13bf.png)
