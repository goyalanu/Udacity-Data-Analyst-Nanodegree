
## P0: Explore Weather Trends

### Prerequisites

Additional installations: 

* [Missingno](https://github.com/ResidentMario/missingno)
* [sklearn](https://scikit-learn.org/)

## Project Overview

This first project required the following steps:
* Extract data from a database using a SQL query
* Calculate a moving average
* Create a line chart 

I analyzed local and global temperature data and compared the temperature trends in Delhi,India city to overall global temperature trends. After some data cleaning I created a function to assist the data processing and visualization with some options to play around with. This included also the calculation of a simple linear regression to visualize trends.

![Global Weather Trend](https://github.com/goyalanu/Udacity-Data-Analyst-Nanodegree/tree/master/1-Introduction_to_Data_Analysis/1-Explore_Weather_Trends)

### Data Sources

**Name:** city_data.csv
* Definition: Overall city temperature data
* Source: Udacity
* Version: 1
* Method of gathering: SQL

**Name:** global_data.csv
* Definition: Global temperature data
* Source: Udacity
* Version: 1
* Method of gathering: SQL

**Name:** city_list.csv
* Definition: List of cities in this dataset
* Source: Udacity
* Version: 1
* Method of gathering: SQL

### Wrangling
* Cut data to years 1750 - 2013

### Summary

> To conclude, there is a clear overall uptrend visible, what means, that the average global temperature is increasing, with an also increasing tempo.

The Indian cities Delhi got compared to the global data (1750 - 2013):

- 1) The following data shows us about the global temperature and city temperature
-2) The gap between the city_temp line tells you about the missing data
-3) Temperature of city iis higher than global temperature 
-4) Since 1800 the temperature remain vary between 20 to 30 only
### Authors

* Christoph Lindstädt
* Udacity


