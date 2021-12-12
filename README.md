# Project Title: U.S Adult Literacy Rate Map by County

# Project Description 
This github project is about visualizing the Adult Literacy Rate for U.S adults. This project visually shows the U.S Adult Literacy Rate per county as an interactive web application. There is a search bar that can be used to find locations in the U.S and the Adult Literacy Rate for that county will be displayed in the upper lefthand corner. If you do not see the data on the map, try refreshing the page. The user can enter any number of locations into the search bar to look up the Adult Literacy Rate for their county. 

This application uses a combination of HTML, CSS and Javascript for all the front-end/back-end functionalities it supports.That being said all of the code is located in a single html file called index.html. This application also uses mapbox in order to display a map of the United States. All of the data is taken from data.gov, for more information click the hyperlink in the application to learn more about how the data was collected and which organizations use this data. The dataset I used had addtional columns that could have been indicators of why certain counties had lower/higher than expected values, but for clarity sake I wanted to focus solely on the Literacy Rate as not to confuse what the original topic was.


# Project Goal
In this application I wanted to look at the Literacy Rates for all counties in the United States. The goal of the project was to analyze/look for patterns in places of high and low literacy rates. I mapped the literacy rates by county instead of by state in order to get more information about the various counties in each state. The message I wanted to give to the users was for them to acknowledge which areas in the country have the highest literacy rates regardless of any bias that they may have on which counties they personally think should be higher.

I also wanted to make this project open source so that anyone would be able to use this application or get any ideas for future improvement. The color scheme chosen for the legend was handpicked to contrast the basemap color scheme. With my legend colors being very light contrasting the dark shading of the basemap, all of the counties are able to stand out. This project also uses a variety of tools and technologies we used through the quarter but mainly the past several weeks(geocoder, mapbox,etc).  

# Access the application here: 
https://aembar.github.io/GEOG495AdultLiteracyRateMap/

![](https://github.com/aembar/GEOG495AdultLiteracyRateMap/blob/main/imgs/Screen%20Shot%202021-12-09%20at%205.59.48%20PM.png)


# Main Functions 

## Search Feature 

In the search bar enter a location to see the Adult Literacy Rate for your county. Click the ‘X’ button in the top right hand corner to clear the search so that you may enter a new location. When you enter a location in the search bar, the application will ping and zoom in on that area. 

![](https://github.com/aembar/GEOG495AdultLiteracyRateMap/blob/main/imgs/Screen%20Shot%202021-12-09%20at%207.11.37%20PM.png)

## Literacy Rate

The main functionality is the literacy rate per county which is displayed in the top left hand corner. Go to the data sources section to see how the data was collected. This data was from data.gov. 

# Data Sources 

You can find the data source here at data.gov: https://catalog.data.gov/dataset/piaac-county-indicators-of-adult-literacy-and-numeracy  

The data was from The National Center for Education Statistics who surveyed 12,330 U.S. adults ages 16 to 74 living in households from 2012 to 2017. These organizations used small area estimation models (SAE) to produce indirect estimates of literacy and numeracy proficiency for all U.S. counties. SAE is a model-dependent approach that produces indirect estimates for areas where survey data is inadequate for direct estimation. SAE models assume that counties with similar demographics would have similar estimates of skills. By using PIAAC survey data in conjunction with data from the American Community Survey, the Skills Map data provides reliable estimates of adult literacy in all counties in the U.S. 


# Applied Libraries 

I used mapbox gl js to display a map of the Globe and then centered on the United States. I also used their version 10 dark basemap for my application to make all of the counties stand out from the rest of the world. I used a geocoder to add the functionality of the search bar(the search bar is made to work all over the world). I am also using github in order to store all of my files and using their github pages resource to host my application. This entire project is open sourced so people can use my application and see the repository. 

# Acknowledgement 

I used mapbox tutorials to help with the search functionality implemented in this application from here: https://docs.mapbox.com/help/tutorials/local-search-geocoding-api/ . 

I also used maobox’s api in order to change the type of basemap I would use for my GIS application: https://docs.mapbox.com/api/maps/styles/ . 

Lastly my data source is from data.gov and the website is from: https://catalog.data.gov/dataset/piaac-county-indicators-of-adult-literacy-and-numeracy 

This project was developed for my GEOG 495 Web & Mobile GIS class at UW taught by Professor Bo Zhao who taught concepts related to Web programming for GIS applications which were used in development of this application. 

