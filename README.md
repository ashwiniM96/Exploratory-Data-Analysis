# Exploratory-Data-Analysis
Yelp_academic_dataset_business file:

• The number of star ratings individually have been counted and this star rating distribution was been plotted on a bar graph, which used matplotlib and seaborn libraries. • Then to find out how many businesses are there in each city we counted the number of business in each city and then graphically represented this on bar graph to visualize it. • A graph for some random categories of businesses from the given set of data is also being shown.

We also tried representing the data on maps using their latitudes and longitudes which was provided in the data. Such data is also known as geospatial data. The Geospatial data is a kind of data which contains location information. Such numeric data is used to identify the geographical location of an object. • Initially I started locating the top 1000 businesses on an open street map along with names of each of the businesses all over USA. This is done using the folium function in Python. • Secondly, I filtered out all types of salons from the dataset and mapped their location on an open street view map. • Heatmap was also shown with the various businesses mapped using the heatmap plugin.


Bubble chart is also been used, which is usually implemented using Plotly’s Python library. Initially, the restaurants were filtered out from the category’s column. Then from these results obtained, the unique values were filtered out. So, the result obtained after such query is the various categories of the different types of restaurants • These categories are then plotted on a bubble chart graph with the average price range of each type against the popularity which would be based on the average review, each category of the restaurant would get. Here the size of the bubble is the number of restaurants. • By looking at the graph we particularly come to know which category of restaurants people usually prefer more and spend money


Secondly, we use the Yelp_academic_dataset_checkin file:

This file contains the check-in timings of the users for all the businesses. For further analysis the check-in data is being merged with the business file so that we get the timings of businesses along with the other data present in the business file. From the data, which is split up, we obtain the latitude and longitudes • Here I have divided the frame into 24 time slots, so that each time slot would show at which time, which of the businesses are active. • The timings from the check-in file will automatically map in its time frames. • This visualization shows us the hourly time activities of the businesses mapped

