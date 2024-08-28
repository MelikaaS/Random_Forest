# Predict Maximum Temperature for Tomorrow in Seattle, WA Using Random Forest Algorithm
In this repository, I'm following the steps mentioned in this [article](https://towardsdatascience.com/random-forest-in-python-24d0893d51c0) to implement **Random Forest** algorithm on real dataset.

## DataSet Overview
The DataSet contains weather data for Seattle, WA from 2016  and retrieved using the NOAA Climate Data Online tool by [Will Koehrsen](https://github.com/WillKoehrsen)


### DataSet Description
The below table shows the description of each column

#### Features

| Column   | Description                                           |
|----------|-------------------------------------------------------|
| year     | 2016 for all data points                              |
| month    | Month of the year as a number (1-12)                  |
| day      | Day of the year as a number (1-31)                    |
| week     | Day of the week as a character string (e.g., "Monday")|
| temp_2   | Max temperature 2 days prior                          |
| temp_1   | Max temperature 1 day prior                           |
| average  | Historical average max temperature                    |
| friend   | Friend’s prediction, a random number between 20 below and 20 above the average |

#### Target

| Column   | Description                                           |
|----------|-------------------------------------------------------|
| actual   | Max temperature measurement                           |


dropped columns from original dataset contain :
- "forecast_noaa"
- "forecast_acc"
- "forecast_under"



