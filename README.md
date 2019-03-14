# Final Map Critque :walking: :car: :bike:
This is a report descriping The [***Portland Traffic Deaths and Injuries since 2007***](https://pdx.maps.arcgis.com/apps/MapSeries/index.html?appid=5385b143768c445db915a9c7fad32ebe) made on ArcGIS online and was created by the city of Portland. The goal of this report is to wirte up a map critique including a decription, data sources, style, and map elements.

### Description
The [***Portland Traffic Deaths and Injuries since 2007***](https://pdx.maps.arcgis.com/apps/MapSeries/index.html?appid=5385b143768c445db915a9c7fad32ebe) was created by The City of Portland Bureau of Transportation (PBOT) September, 2017. Within PBOT the Vision Zero is dedicated preventing future accidents. The map represents traffic accidents that occur on major corridors that lead to an injury or death. This map help visualize where accidents occur on arterial streets and categorizes accidents by category: car, bike or pedestrian. The map has a dark greyscale basmap while arterial streets are highlighted in yellow. Crashed are represented by orange and bright light grey circles. City officials and people interested in Vision Zero would find this map useful when identifying streets and intersections where accidents occur this leading to safer street design, lowering speed limts and promoting . 

### Map features
**Fetures & Elements**
* Dark netural basemap. This implies that the thematic layers are the focus of the map.
* Map title with author and sharable links (Facebook, Twitter and Share button).
* Side panel with map description and legands.

![alt text](https://github.com/garciahan/Final_MapCritque/blob/master/legand.PNG)

* Symbols representing diffrent features.
* City of Portland Boundary is darker than the basemap to area of focues is easily known.
* Graph in the side panel adds another way to visualize the data on the map.
* In the side panel the auhtors credit their data, has "last updated" information, and includes links to their Vision Zero team and how they process their crash data. 

**Thamatic and interactive layers**
* Thamatic layers on the map are the crash points and the street layers.
* Interactive features include clickinng on points and a info box pops up with data attributed to it. Data attributed to crash points are the date of crash, time, day, number of injuries or deaths, speed, incluence of drugs or alchohol during the crash and if a bike, car por pedestrian were involved. 

![alt text](https://github.com/garciahan/Final_MapCritque/blob/master/popup.PNG)

* Zoom in out, and recenter button on the map. Also a enter address box to find crashed near an address. 
* Another interactive feature is the tabs on the side panel. The tabs are "All deaths & injuries", "People in vehicals", "People walking" and " People biking" Clicking on those tabs will select crashed specific to the type of crash it is then the webmap on the side will also change to refelect the chosen tab.

![alt text](https://github.com/garciahan/Final_MapCritque/blob/master/tab.PNG)

### List of Data Source
Data for this map was collected by Oregon Department of Transportation (ODOT) and the Portland Police Bueau. See the image below to see how PBOT collects their crash data. All data in the map are vector format, with crashes as points and streets are polylines.

![alt text](https://github.com/garciahan/Final_MapCritque/blob/master/Crashdiagram.png)
Image from PBOT website [*How crash data works*](https://www.portlandoregon.gov/transportation/article/595691)

### System Architecure
PBOT has a GIS database that stores all GIS data for the city to use. The city works maily with ESI products and offers open source data [here](https://gis-pdx.opendata.arcgis.com/). The map was created on ArcGIS online, which is a easy webserver to work with to let users create and publish webmaps online. 

### Map Design Critique

This map is consistant with colors, the basemap is a dark greayscale and the features of interest are yellow, light grey and orange. These colors provide great contrast with the dark basemap. All the information is easily avalible in the side panel. THe side panel 
provides symbology description and a bar graph, which is a great way to display the data in another way. Side panel also inclued what data is being showed and where the data came from. Anytime a URL is mentioned it is hyperlinked for users to click on. The pside panel is a little text heavy but there is hierarchy so users know what to read first. 
There are many oppurtunities to interact with the map, in map portion of the map users are able to scroll across the map, and zoomi n/out to look at specific areas. There is also an address bar so if users were intersted in looking at crashes on their street they can type is in and the map will zoom to the location.
The title is informative and tells users that the ,ap is about traffic deaths and injuries from 2007 - present. The map has no formal introduction but all the other features in the side panel implys what the map is about.
The balance of the web map is great, features are seperated and the entire page is being used so ther is no uneasy empty space. Also the font is consistant only two diffrent fonts are used in the map and tehre are less than 5 colors used (orange, yelloe, black, white and gray). Its easy to tell that features in yelloe, orange and gray are the most important elements since they pop off the page. 
The cymbology is lgetable, the author chose circles to represent crashed that lead to deaths and injuries. The diffrent sizes of the circles represent maginiture of number of crashes. The figure ground organization is good, the city of portland boundary is darker than the rest of the basemap so users can tell what the city boundaries are. 

From your own perspective, what is the merits of this web map, and how this web map could be further improved?

### Final Dissucssions
Overall this map has a great design and creates a geospatial visialization of crashes in Portland. The only sugguestion is to fix the zoom level when entering in address the map. When entering in a address the zoom goes in super close, so users have to zoom back out to see roads and data. 


**Map screenshots in this read me file were from the [***Portland Traffic Deaths and Injuries since 2007***](https://pdx.maps.arcgis.com/apps/MapSeries/index.html?appid=5385b143768c445db915a9c7fad32ebe) web map created by PBOT.*
