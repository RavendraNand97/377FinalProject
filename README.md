# Crime Data Application

## Description

The purpose of our application is to enable prospective Prince George's residents to view the density of crime that would occur near by to a street they would potentially be moving to. More importantly this application can be used to help inform University of Maryland students on where they should consider living. As a college student the related crime of an area can easily be overlooked when considering the cost of living and how close you would be to campus. Our application makes use of the Prince Georges county crime dataset by creating a map visualization that would allow users to select what types of crimes they would be most concerned about in the area and placing markers of those crimes onto our map provided by leaflet. Markers are placed on the map by clicking the desired checkbox next to the crime name. The map allows users to zoom in and out of and drag the map to find the street or route they would be interested in viewing to get a closer look of the crimes. By clicking on the map markers, you will also be able to view the type of crime if you have selected more than one. With creating crime markers for our application users will have the knowledge to make an informed decision if they would want to avoid an area.If users chose to live in a crime filled area our application also makes use of Prince George’s county police and hospital dataset, which would enable users to identify which police station or hospital is closest in case any safety or health concerns need to be addressed.

## Link to Heroku

<https://inst377-finalproj.herokuapp.com/>

## Target Browser

Web browsers:

* Google Chrome
* Mozilla Firefox
* Internet Explore
* Safari
* Microsoft Edge

## Developer Manual

Our application is intended for the purpose of helping inform college park students about recent past crime history so they can make an educated decision on where they should consider living when looking for housing off campus. The crime data application website is meant to inform students by using a series of checkboxes and placing markers on to a map to create an easy map visualization. Our Crime Data Application page was built using HTML, CSS, and Javascript. The libraries used to provide website information to the user where leaflet, which was used to create our map. The other three libraries came for the Prince George's county data website, which were “Crime Incidents February 2017 to Present”, “County Police Stations”, and “County Hospitals”.

For future development purposes developers can copy would need to clone the repository link <https://github.com/RavendraNand97/377FinalProject.git> . Once cloning the repository developers can fork their repository in order to work on continuing developing the website. One last step in preparations to continue developing would be by opening the terminal and entering “npm install”. In order to open the website the developer would also have to type “npm start” in the terminal and open a page in Chrome followed by typing localhost:3000 in the url search bar.

For our GET endpoints we created 3 functions for each api source that would fetch the original data into our server. In each function we also filtered what specific data we wanted to read in, which would make our data easier to read. To view this end point you would need to enter npm start into the console and in Chrome you would type localhost:3000/api to view the data. For our POST, we await the requested data and then are able to use that data to update our application via the functions in our script file.

One of the bugs that we are experiencing with our website is getting the check boxes to clear specific data markers off of our map when a user unchecks a box. This could be fixed in our script.js folder inside of our dumb function, but we could not get it to work. In the future we believe it would be beneficial to add a search bar to the website that would allow users to search by street, which when submitted would zoom into that specific part of the map making it easier to get a closer view of crimes in the area of interest. In the future it would also be helpful to expand our to other university campus counties in Maryland to help more students make informed decisions when finding a safe place to live when at school.
