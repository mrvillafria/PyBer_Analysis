# PyBer with Matplotlib

## Overview of Project
For this week's project, we will continue to use Jupyter Notebook and Pandas to pull and merge data, perform calculations, and create dataframes to uncover trends. To visualize our findings, we will be using Python's two-dimensional plotting library, Matplotlib. Matplotlib will allow us to graph our complex data findings and present them in a meaningful and engaging way. With Matplotlib, we can show data as a line chart, bar chart, scatter plot, bubble chart, pie chart, and box-and-whisker-plot. Using graphs is important in telling our story because the audience will be able to quickly observe patterns and trends to make decisions.

### Purpose
The purpose of this week's analysis was to perform an exploratory analysis for PyBer, a Python based ride-sharing app company. There were two data sets that we sorted through, city data and ride data. We merged these data sets to show relations between city types, number of drivers, number of riders, and fares between January 2019 through April 2019. There are three different types of cities that we based on analysis on: Rural, Suburban, and Urban. After we grouped the data by city types and perform calculations, we created visualizations. We first created a ride-sharing summary dataFrame and then designed a multiple-line graph to show the total weekly fares for each city type. This analysis will help PyBer improve their ride-sharing services and allow decision makers at PyBer to evaluate their business across all types of cities.

## Results

#### Ride-Sharing Summary by City Type
The Ride-Sharing Summary by City Type visualization below quickly presents the total number of rides, total number of drivers, total number of fares, average fare per ride, and average fare per driver by city type from our PyBer data. The three different city types for this analysis are Rural, Suburban, and Urban.

![ride_sharing_summary](/analysis/ride_sharing_summary.PNG)

By looking at this chart, we can see that there are more Rural and Suburban rides in relation to how many drivers there are. For Rural and Suburban cities, although there are less rides than the number of rides for Urban cities, there is a demand for drivers. Because there is a demand for more drivers, this may be the cause for the higher average fares for the driver. For Urban cities, their supply of drivers exceeds the number of rides. Drivers have lower average fares in Urban cities because they may not be giving as many rides because of the excess of other drivers. It is also possible that their rides may be shorter in distance due to the proximity of places for city living.

#### Total Fare by City Type
The Total Fare by City Type multiple-line graph shows the total weekly fares for Rural, Suburban, and Urban cities between January 2019 through April 2019. As you can see, Rural cities have the lowest total fares throughout this timeframe but slightly spike up around mid-end February and beginning of April. Suburban total fares throughout January and April are consistent but also go up around mid-end of February. Urban cities generate the highest total fares and have increases around mid-end February, throughout March, and beginning of April. Based on this observation, we would need to obtain more information if there was a holiday or big event across all the city types that may have caused the fares to increase mid-end of February.

![PyBer_fare_summary](/analysis/PyBer_fare_summary.png)

The graph information was based on this chart that calculated and displayed the sum of the fares for each week.

![PyBer_pivot](/analysis/PyBer_pivot.PNG)

## Summary