# Crime Data Application

## Team Members

* Israel Gonzalez
* Ravendra Nand
* Alexander Chui
* Rishi Sudhakar
* Sydney Anabaraonye
* Brian Nganjo

## App Link

<https://inst377-finalproj.herokuapp.com>

## Information Problem

A good population of the University of Maryland (UMD) student body would love to live off campus, or away from UMD’s campus, but relatively close to campus for easier commute. When people move they sometimes would consider many factors about the home and the area that they will be living. One of the factors that some may consider is, if the area is safe and would want to look at the crime levels in certain areas. We will solve the user’s need to determine how safe it would be to live in a certain area.

## Stakeholders/ Target Browsers

A stakeholder for this app is  UMD students who want to live off campus, since UMD is located in PGC and many of the students may stay within the county. Potential stakeholders of the application also include city officials and police officers, they can use this to help enable better policies for the monitoring of certain areas around the county. Since the data is focused on PGC, the app will also be helpful for those who would want to live in PGC. They will be able to see how safe, or what potential safety precautions they will need of their potential home. Along with crime people are able to look for the emergency service systems around their area, which is important to know along with the other data.

## Data

The data we chose to use for our Crime Data Application website primarily focused around the PGC crime data set which spanned back until 2017 to the present date. The crime data contains information such as incident case id, date, reporting area, sector, etc. For the purpose of our project we did not need all of the information the api provided so we filtered the unnecessary information and only kept information regarding the date, latitude, longitude,the type of crime committed, and street address. Our team only chose to work with the latitude, longitude, and type of crime for our final submission which would enable us to plot markers of a crime incident depending on the type of crime the user would like to see. The street address is for future use which could be used to enable the user to search a location of interest by street name.

Furthermore, we also chose to use PGC’s police and hospital dataset which would allow the user to view the nearest emergency service in case students would take the risk of living in a high crime area and would like to know where they can go or call for the fastest assistance. We specifically wanted to focus on the facility name, latitude, longitude, and telephone number. Through the use of these api’s information that we filtered for we can post the location of each emergency service, as well as their name and phone number.

## Strategies and Solutions

The strategy we utilized when looking to solve our problem was, where do most students who are off campus decide to live. We took that into consideration and we knew that the safety of these students is crucial, the next step we would have to take was analyzing the area. By doing so we were able to analyze the general college park area and we started to analyze the map. By looking fully at the map we were able to pinpoint to where directly there was a significant focus in the criminal activities. Along with this we had to decide what the best use for the API application was and utilizing it for crime data was important because it provided real life information in a clean system.

## Technical system decision rationale

The application underwent numerous iterations to become what it is now. Many small changes and bug fixes were made to increase the efficiency of progression. However there were some larger changes that were made for a variety of reasons. The first major change we made was to remove the search bar that would’ve accepted zip codes as input. This was removed because much of the data we were pulling from databases did not include zip codes. The second change we made was to cease usage of Google maps and switch to the leaflet api. This change was made due to Google maps being restrictive and having a paywall. The last major change was to change the search bars for our filters to checkboxes. This change was made to improve ease of use and make functionality more evident.

## How the App Addressed the Problem

The application addressed the problem because it was a mapping application that was created to focus specifically on crime within the area and the emergency services. People are now able to look at a map with real batch data of their area, and from that map they can select the various kinds of crime or all crime and see the numbers of their affected area. Along with this, people are able to also view the emergency service systems within the general vicinity, this is important because people are now able to report to something when in dire need. Having this information at the disposal of individuals and policy makers is important because with this they can enable various policies to help protect the general vicinity.

## Challenges Faced and Impact on Final Design

One of the biggest problems we faced was implementing the police data information and along with the other informational markers. When trying to implement the police markers along with the other information, there was difficulty in both of these various aspects coming together within the application so it needed to be fixed within the code. Along with the marker troubles, one of the most worrisome issues was the issue of the markers freezing when the data was selected on what to focus on. There was trouble in some bits of the website which made it difficult because the marker would freeze in certain instances.

## Possible Future Work Directions

Based on what we accomplished so far on this app, there are many more rooms for improvements. One of the types of improvement involves the filtering portion, where the users can filter the data that appears on the map. There are other filters that can be added to the map, such as being able to filter the data by dates, and zip codes. Also the filter can remove the markers on the map, when the user no longer wants a certain crime data, which can be done by unchecking the box. There can also be a search filter where the users can search by street name, and it will show all the crime on that street. In the data there are data that can be combined into one category, and it can be displayed as one crime type. For example, there are different types of breaking and enterings (B&E), which some have labels: “B&E: Residentials”, or “B&E: Commercial”, which could be set to a crime type of “B&E”.

The final portion of improvements involves the map, where it can show a heatmap of the crime occurrence of different areas on the map. The users should be allowed to toggle between markers and heatmap, since the heat map is a summary of the crime data and the markers are individual crime occurrences. Lastly the map can also provide data outside of PGC, such as Montgomery County, and  Anne Arundel County to list nearby counties. Eventually this map application can expand to view crime occurrences throughout the state of Maryland.