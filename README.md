# Visualization of Eruptions, Earthquakes, and Emissions

<img src="img/Map_Jan_2017.png">

<b>FIGURE 1.</b> Static image of the interactive eruptions, earthquakes, and emissions map.

### THE PROJECT

[Eruptions, Earthquakes, and Emissions](https://volcano.si.axismaps.io/)

### INTRODUCTION

The Eruptions, Earthquakes, and Emissions project, built by Axis Maps for the Smithsonian Institute’s National Museum of Natural History, highlights volcanic activity and earthquakes occurring around the world since 1960. Utilizing eruption and emission data from the Smithsonian’s Global Volcanism Program, and earthquake data from the United States Geological Survey (USGS) Earthquake Catalog, all occurring within the time range of January 1960 to January 2017, the featured web-based interactive map explores the changes in and locations of volcanic eruptions, sulfur dioxide emissions, and earthquakes. In looking at not only the purpose, systematic architecture, and user experience and interface of this visualization, but also the deeper rooted , 

When viewing the map, the time lapse of data automatically begins. From 1960 to 2017, eruptions, emissions, and earthquakes are visibly cycled through, taking form of three different symbols that fluctuate in size and prevalence based off quantitative and time-oriented measurements. The first indicated variable, earthquakes, visualizes the locations of known earthquakes. It is symbolized by a blue circle that grows or shrinks respective to magnitude. Only earthquakes with a magnitude of five to ten are populated on the map. The second variable, volcanoes, encompasses the volcanic eruptions data. Each data point is measured on a one to ten scale by volcanic explosivity index and is represented by an orange triangle that increases or decreases based on the corresponding index number. Finally, the sulfur dioxide emissions, symbolized by a , All of these features present the main functions of the map and 

The purpose, therefore, of this visualization is to showcase in a clear format the pervasiveness of natural disasters, like volcanic eruptions and earthquakes, and their effects, like sulfur dioxide emissions. Due to the map being specifically built for the Smithsonian Institute, it can be assumed that it is widely used, well developed, and a credible resource for information. Though the project can be found on a few designated sites, its expansive, global view of different environmental phenomenon can apply to a diverse range of organizations, communities, and individuals. Three target audiences of this information that could benefit from this information are residents near or on impacted areas, government official that 

#### General Overview:

- <b>Author:</b> Axis Maps
- <b>Built for and with:</b> The Smithsonian Institute’s National Museum of Natural History
- <b>Data:</b> Eruptions, Earthquakes, and Emissions
- <b>Data Resources:</b> Smithsonian’s Global Volcanism Program and United States Geological Survey (USGS) Earthquake Catalog

#### Functions

- 


### SYSTEMATIC ARCHITECTURE

The process of loading, updating, and displaying the data involves the implementation of a secure database and strong website and mapping framework. In the case of this project, rather than the map pulling information directly from the listed programs and resources, it is stored within a postgres database hosted by Axis Maps. The postgres database serves to optimize the data through generalizing locations and removing certain attributes before sending it to the client. When the data is fully stored and condensed, it is then loaded into the map and displayed in a timely manner. Clients can overall view the populated data and interact with the desired functions without having to be aware of backend procedures.

As for the website and mapping framework, the structure is primarily built with JavaScript, and in particular, the Cesium JavaScript Library. To provide a foundation for high functioning and interactive visualizations, the map utilizes JavaScript, which passes in the data and grants the ability for users to click on symbols for information and a slider to switch to and from different periods of time. From the code, it seems that all the data filters into a function which then populates the points on the map. The Cesium library in this circumstance is specifically used to host the WebGL


### USER EXPERIENCE AND INTERFACE

Designing exemplary user interface and experience is necessary to the successful and efficient display of featured information. User experience notably defines the look and overall function of the project, while user interface handles the interactive and more technical elements that users can toggle and select. Observing the visual design of the displayed map, as well as the interactable features, the project is determined to be a highly controllable and explorable hub of data. The real-time responsiveness to user engagement allows for . Taking this into account, it seems that the map grants the perfect ability to formulate analysis and find patterns in the data due to the customizability of 

The main portion of the visualization, which is the map, uses an OpenStreetMap basemap generated by Map Box. It sets a baseline for drawn out boundaries and locations and ensures that the data is given a geographic meaning. With a darker theme, it makes the neon-colored symbols stand out and easier to read. This already creates a better experience for users because of its visually-. The thematic layer, on the other hand, contains all the data that is being populated. The eruption, earthquake, 
While the m

### PROS

The positives of this project overall involve the effective implementation of a responsive map, as well as al.

### CONS

A more negative result of this project is the blurriness and cluster effect of the data points. While the design of the hosted map is responsive and able to populate the symbols at a quick rate, some of the symbols look graphically lower quality. It is logical that due to several of the phenomenon occur within similar locations that some of the points would overlap. However, without any of the symbols having an outline and 

In this way, 

### REFLECTION

After analyzing the totality of the project in terms of its purpose, systematic architecture, and methods of visualization, it is now important to delve further into the grander context and socioeconomic implications of creating and using this kind of map. Some relevant key take form in finding the context of the data, realizing the 
	 
In not only treating
