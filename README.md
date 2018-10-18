# Weather—Flight
In this project, we were given two data sets: flights and weather2. The first data set: flights.csv, provides us with information about airline flights in and out of all of the New York airports between January 1, 2013 and December 31, 2013. In this data set, each row is an observation about a single flight, but there are a number of derived columns that need to be cleaned up in order to transform this data set into tidy form. For the transformation process, we only kept the month, day, carrier, flight number, departure hour (originally called hour), departure minute (originally called minute), origin and destination airports, departure delay time, arrival delay time, distance and air time. The other columns such as the actual departure time and actual arrival time could all be derived from the information kept in the table. For easy exporting purposes, we set the index column to 'month'. The second data set: weather2.csv, is data obtained from Weather Underground for weather metrics in Boston, MA over the time period ranging from January 1, 2013 and December 31, 2013, same time period as in the flights data. This data does not conform to our Tidy data constraints. We first clean these datasets and then find some relationships between variables. 
## Prerequisites
Anaconda
Jupyter Notebook
# Installing
https://www.anaconda.com/download/#macos (for installing Anaconda)
http://jupyter.org/install (for installing Jupyter Notebook)
# Contributing
