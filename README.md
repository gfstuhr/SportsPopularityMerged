# Sports Popularity

# **Project Contributors** 

This is a collaborative project, shared between [Jennie Brozena](https://github.com/JenBroz), [Nathaniel Diamond](https://github.com/DiamondN97), [Faith Lierheimer](https://github.com/faithlierheimer), [Thambi Mathews](https://github.com/), and [Gabe Stuhr](https://github.com/gstuhr). 

# **Summary of Interests and Intent**

Major league sports are an integral part of many American lives. However, not all sports are equally popular in all cities. For example, the Green Bay Packers are a wildly successful football team in Wisconsin, but Wisconsin has no NHL team and no corresponding popularity of major league hockey. We are interested in analyzing the relative popularity of each of the “Big 4” sports, (hockey, baseball, football, and basketball) in major American cities and unearthing patterns in where some sports are more or less popular than others. On this large scale, we will use seasonwide attendance to games as a metric to score relative popularity; and we will also compare average ticket prices for teams' games across the four sports. We will be analysing the data from the 2019 professional sports' seasons. It's important to note that some sports have seaons that span across two calendar years, such as the basketball and football seasons; our data sources for those two sports will range from 2019-2020 caleldar years, but will be the data for the season starting in 2019.

# **Data Sources**

Sports season-wide attendance data is relatively easily to find across the internet. To access this data, we will be using a series of web-scraping techniques, including but not limted to python's Pandas library and Beautiful Soup. 
For our baseball attendance data, we will be scraping the Wikipedia article [2019 Major League Baseball Season](https://en.wikipedia.org/wiki/2019_Major_League_Baseball_season) to access data on the Major League Baseball Teams' [attendance figures](mlb_attendance.PNG) for the 2019 season, as well as a [JSON of Ballparks' Locations](https://tinyurl.com/y3sby4ur) to accurately place the ballparks on our leaflet map. 
For the hockey attendance data we will be referencing 
For the football attendance we
For the basketball attendance data we 
For the ticket price data we 
## Baseball Attendance
## Hockey Attendance
## Football Attendance
## Basketball Attendance
## Ticket Prices
## Data Visualization
Once we extracted the data from our chosen sources, we loaded it onto a flask app to create a restful API so the data can be easily recalled for further analysis. Using the javascript library leaflet, we requested the data from our flask API
ETL - take scraped data
Flask - make API to store data we grabbed
leaflet.js - requests data from flask and visualizes


