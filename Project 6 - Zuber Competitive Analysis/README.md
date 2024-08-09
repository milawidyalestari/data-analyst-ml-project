# Exploring Passenger Preferences and the Influence of External Factors on Zuber Ride-Sharing Company
## by _Mila Widya Lestari_

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

Stay connected by following my instagram: [@milaalestari_](https://www.instagram.com/milaalestari_/)

## Features
> #### project_sql_result_01.csv. This file contains the following data:
> * company_name: name of the taxi company
> * trips_amount: number of trips for each taxi company on November 15-16, 2017.
>   
> #### project_sql_result_04.csv. This file contains the following data:
> * dropoff_location_name: name of the area in Chicago where the trip ended
> * average_trips: average number of trips ending in each area in November 2017.
> 
> #### project_sql_result_07.csv — result of the last query. This file contains trip data from Loop to O'Hare International Airport. Here are the column values in > this table:
> * start_ts -- date and time of pickup
> * weather_conditions -- weather conditions at the start of the trip
> * duration_seconds -- trip duration in seconds

## Introduction
Zuber is a new ride-sharing company that has launched in Chicago. Our goal is to analyze the available information in order to identify patterns. We aim to understand passenger preferences and the influence of external factors on trips. For this project, we will be using the dataset that we previously queried from the database using SQL.

## Goal
In this project, I will be utilizing a database to analyze the data from competitors and test hypotheses related to the impact of weather on trip frequency. The project is divided into two stages: using SQL and Python on Jupiterhub. In this section, I will focus on working with Python on Jupiterhub.

The hypothesis that needs to be tested is as follows: "The average trip duration from the Loop to O'Hare International Airport changes on rainy Saturdays."

I will be using the last query result data file 'project_sql_result_07.csv', which contains trip data from the Loop to O'Hare International Airport. The columns in this table are as follows:
- 'start_ts': pick-up date and time
- 'weather_conditions': weather conditions when the trip begins
- 'duration_seconds': trip duration in seconds

To test this hypothesis, I will be following these steps:
a. Formulating the null hypothesis and alternative hypothesis.
b. Using a default alpha value of 5%.
c. Conducting a statistical test (student t-test independent 2 samples).
d. Comparing the p-value of the statistical test results with the alpha value.
