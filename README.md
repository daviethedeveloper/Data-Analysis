# Data-Analysis

# Overview

As a software engineer, my purpose in analyzing this data set is to understand and uncover patterns and insights related to flight delays at different airports and months. The data set I am analyzing is a JSON file of flight information, which was obtained from https://raw.githubusercontent.com/byuidatascience/data4missing/master/data-raw/flights_missing/flights_missing.json.


[Software Demo Video](http://youtube.link.goes.here)

# Data Analysis Results

For the first question, I used the metric of proportion of total flights delayed to determine the "worst" airport. This was done by grouping the data by airport and calculating the total number of flights, total number of delayed flights, proportion of delayed flights, and average delay time in hours. The results showed that SFO airport had the highest proportion of delayed flights (26%) and could be considered the "worst" airport in terms of this metric.

For the second question, I used the metric of proportion of delayed flights to determine the best month to fly in terms of avoiding delays. I removed any rows missing the Month variable, filled in missing values with the mean, and grouped the data by month. The results showed that the best month to fly to avoid delays was December, with the lowest proportion of delayed flights.

# Development Environment
{Describe the tools that you used to develop the software}


{Describe the programming language that you used and any libraries.}

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Web Site Name](http://url.link.goes.here)
* [Web Site Name](http://url.link.goes.here)

# Future Work

* For my future work on this project, my plan is to provide more of a visualization charts from my data
