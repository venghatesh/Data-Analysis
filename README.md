# Data-Analysis
Analysis of Berkshire Data
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. 
Bicycle-sharing systems allow users to rent bicycles for short trips, typically 30 minutes or less.
Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or
return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.
In this project, exploratory analysis on data provided by Motivate, a bike-share system provider for many major cities
in the United States is carried out. we will compare the system usage between three large cities: New York City, Chicago, and Washington, DC.
we will also see if there are any differences within each system for those users that are registered, regular users and those users
that are short-term, casual users.

The scope of the work involves
1. Trip data across cities are not consistent. Column names, format are different. To do actual exploration, trim and cleaning of data is 
carried out .
2. We need to generate new data files with five values of interest for each trip: trip duration, starting month, starting hour, 
day of the week, and user type. Each of these may require additional wrangling depending on the city. 
3. Initial Exploratory data analysis  (Using Python 3 - No usage of pandas or dataframe) 
  a) city with highest number of trips
  b) city with highest proportion of trips made by subscribers
  c) city with highest proprotion of trips made by short term customers
  d) Average trip length of each city
  e) Proportion of rides made in each city are longer than 30 minutes
4. Further Exploratory Analysis
   a) How does ridership differ by month or season? Which month / season has the highest ridership? Does the ratio of Subscriber trips to Customer trips change depending on the month or season?
   b) Is the pattern of ridership different on the weekends versus weekdays? On what days are Subscribers most likely to use the system? What about Customers? Does the average duration of rides change depending on the day of the week?
   c) During what time of day is the system used the most? Is there a difference in usage patterns for Subscribers and Customers?
5. Visualisation (using matplotlib)
  a) Trip duration vs no of trips for 3 cities - histogram based on rider types
  b) Distribution of trips on each day of the week across different cities - Line plot
