# Data-Analysis

As a software engineer, my purpose in analyzing this data set is to understand and uncover patterns and insights related to flight delays at different airports and months. The data set I am analyzing is a JSON file of flight information, which was obtained from https://raw.githubusercontent.com/byuidatascience/data4missing/master/data-raw/flights_missing/flights_missing.json.


[Software Demo Video](http://youtube.link.goes.here)

# Data Analysis Results

For the first question, I used the metric of proportion of total flights delayed to determine the "worst" airport. This was done by grouping the data by airport and calculating the total number of flights, total number of delayed flights, proportion of delayed flights, and average delay time in hours. The results showed that SFO airport had the highest proportion of delayed flights (26%) and could be considered the "worst" airport in terms of this metric.

For the second question, I used the metric of proportion of delayed flights to determine the best month to fly in terms of avoiding delays. I removed any rows missing the Month variable, filled in missing values with the mean, and grouped the data by month. The results showed that the best month to fly to avoid delays was December, with the lowest proportion of delayed flights.

# Development Environment

The software application I developed used several tools and programming languages to create a robust and efficient system. The primary programming language used was Python. To handle data manipulation and analysis, I used the Pandas library. For data visualization, I utilized the Altair library, which is a declarative statistical visualization library for Python. It enabled me to quickly create a variety of visualizations, including scatter plots, line charts, and bar charts, with just a few lines of code.

In addition to these libraries, I also used the NumPy library, which is a fundamental package for scientific computing in Python. It provided an efficient way to perform mathematical operations on large datasets, which is essential when working with data.

Finally, I used the Visual Studio development environment to write and debug the code. Visual Studio is a powerful integrated development environment (IDE) that provides a range of tools for developing, testing, and debugging code.


# Future Work

* For my future work on this project, my plan is to provide more of a visualization charts from my data
