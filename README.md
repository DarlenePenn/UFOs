# UFOs
https://darlenepenn.github.io/UFOs/

## Overview
### *Purpose of Project*
This project was designed to create a webpage using javascript and html that will display a table of UFO sighting data. The table is filterable on 5 different inputs: date, city, state, country, and shape. When the user inputs a change in any of these filterable fields, the table updates and presents only the data that matches their search criteria.

## Results
The initial table loads with all data visible. Once a specific date is entered, the table will update to show results that only match that specific date. As shown in this example, the date was entered as "1/10/2010" and so the table is only showing results from that date.

![Filtered by Date](/images/date-filtered-jan-10.PNG)


In this example, the city has been input as "cleveland", and the results have updated to filter only those sightings matching that specific criteria. 

![Filtered by City](/images/city-filtered-cleveland.PNG)

The webpage has the capability to filter on multiple fields at once, as shown here with a date of "1/1/2010", a city of "el cajon" and a shape of "triangle" selected. 

![Multiple Filters](/images/multiple-filters.PNG)


## Summary
###This web appliation is useful for sorting through large volumes of data in an interactive way. It has limits, for example the fields are case sensitive and must be input exactly as listed in the dataset. Entering the name "Cleveland" would not bring up any results because it is listed as "cleveland" in the dataset. 
Future developments should incorporate a dropdown menu for the cities and/or shapes because users may not be aware of what options they can choose from. Another future development would be a message that informs the user "No results found" or a similar error message for instances when no results are available based on the search criteria. 
