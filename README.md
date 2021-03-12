# Visualization of Eruptions, Earthquakes, and Emissions

<img src="img/Map_Jan_2017.png">

<b>FIGURE 1.</b> Static image of the interactive eruptions, earthquakes, and emissions map.

### THE FEATURED PROJECT

<b>Map:</b> [Eruptions, Earthquakes, and Emissions](https://volcano.si.axismaps.io/)

<b>Explanation of Project:</b> [Project Overview](https://www.axismaps.com/projects/smithsonian)

### INTRODUCTION

The Eruptions, Earthquakes, and Emissions project, built by Axis Maps for the Smithsonian Institute’s National Museum of Natural History, highlights volcanic activity and earthquakes occurring around the world since 1960. Utilizing eruption and emission data from the [Smithsonian’s Global Volcanism Program](https://volcano.si.edu/), and earthquake data from the [United States Geological Survey (USGS) Earthquake Catalog](https://earthquake.usgs.gov/fdsnws/event/1/), the featured web-based map explores the changes in and locations of volcanic eruptions, sulfur dioxide emissions, and earthquakes. To determine the benefits and importance of analyzing this project, it is necessary to delve further into not only the purpose of the visualization, systematic architecture, and user experience and interface, but also the deeper-rooted context and implications of the data.

When first viewing the map, the time lapse of data automatically begins. From January 1960 to January 2017, eruptions, emissions, and earthquakes are visibly cycled through, taking form of three different symbols that fluctuate in size and prevalence based off quantitative and time-oriented measurements. The first indicated variable, earthquakes, visualizes the locations of known earthquakes. It is symbolized by a blue circle that grows or shrinks respective to magnitude. Only earthquakes with a magnitude of five to ten are populated on the map. Volcanoes, the second variable, encompasses the volcanic eruptions data. Each data point is measured on a one to ten scale by volcanic explosivity index and is represented by an orange triangle that increases or decreases based on the corresponding index number. Finally, the sulfur dioxide emissions, symbolized by a yellow-green circle, are the gas emissions that occur from volcanic eruptions. This data only appears during and after 1978 and is measured by emissions in kilotons. All these features ultimately are encompassed in the main functions of the map. With controllable sliders and clickable points that change display of information, the 

The purpose, therefore, of this visualization is to showcase in a clear format the pervasiveness of natural disasters, like volcanic eruptions and earthquakes, and their effects, like sulfur dioxide emissions. Due to the map being specifically built for the Smithsonian Institute, it can be assumed that it is widely used, well developed, and a credible resource for information. Though the project can be found on a few designated sites, its expansive, global view of different environmental phenomenon can apply to a diverse range of organizations, communities, and individuals. Three target audiences that could benefit from this information are residents near or on impacted areas, government officials and workers providing emergency relief in crises, and environmental activists studying the impacts of the represented variables. If there are any areas in particular that are hit harder by eruptions or earthquakes than others, more resources could then be allocated to those locations for protection and evacuation.

#### General Overview

- <b>Author:</b> Axis Maps
- <b>Built for and with:</b> The Smithsonian Institute’s National Museum of Natural History
- <b>Data:</b> Eruptions, Earthquakes, and Emissions
- <b>Data Resources:</b> [Smithsonian’s Global Volcanism Program](https://volcano.si.edu/) and [United States Geological Survey (USGS) Earthquake Catalog](https://earthquake.usgs.gov/fdsnws/event/1/)

#### Functions

- Time lapse from January 1960 to January 2017
- Symbology representing the eruptions, earthquakes, and emissions
- Slider that allows control of what month and year is being observed
- Clickable points to show the information of each recorded piece of data, including date, magnitude, or location


### SYSTEMATIC ARCHITECTURE

The process of loading, updating, and displaying the data involves the implementation of a secure database and strong website and mapping framework. In the case of this project, rather than the map pulling information directly from the listed programs and resources, it is stored within a postgres database hosted by Axis Maps. The postgres database serves to optimize the data through generalizing locations and removing certain attributes before sending it to the client. When the data is fully stored and condensed, it is then loaded into the map and displayed in a timely manner. Clients can overall view the populated data and interact with the desired functions without having to be aware of backend procedures. When the clients request the site, the destination server responds by providing the map with all its features and data.

As for the website and mapping framework, the structure is primarily built with JavaScript, and in particular, the Cesium JavaScript Library. To provide a foundation for high functioning and interactive visualizations, the map utilizes JavaScript, which passes in the data and grants the ability for users to click on symbols for information and a slider to switch to and from different periods of time. From the code, it seems that all the data filters into a function which then populates the points on the map. It saves each piece of data’s relevant information and assigns it to a clickable symbol for display. The Cesium library, more specifically, is used to host the WebGL technology. Instead of only having the default view of the map, WebGL produces a 3D globe view. This provides more options to observe the data in its geographic context.

<img src="img/code.png">

<b>FIGURE 2.</b> View of the code that runs the map on the browser. It contains a function the passes in the data and .

<img src="img/globe_map_1980.png"  width="700" height="600">


### USER EXPERIENCE AND INTERFACE

Designing exemplary user interface and experience is necessary to the successful and efficient display of featured information. User experience notably defines the look and overall function of the project, while user interface handles the interactive and more technical elements that users can toggle and select. Observing the visual design of the displayed map, as well as the interactable features, the project is determined to be a highly controllable and explorable hub of data. The real-time responsiveness to user engagement allows for . Taking this into account, it seems that the map grants the perfect ability to formulate analysis and find patterns in the data due to the customizability of 

The main portion of the visualization, which is the map, uses an OpenStreetMap basemap generated by Map Box. It sets a baseline for drawn out boundaries and locations and ensures that the data is given a geographic meaning. With a darker theme, it makes the neon-colored symbols stand out and easier to read. This already creates a better experience for users because of its visually-. The thematic layer, on the other hand, contains all the data that is being populated. The eruption, earthquake, 
While the m

### PROS

The positives of this project overall involve the effective implementation of a responsive map, as well as al.

### CONS

A more negative result of this project is the blurriness and cluster effect of the data points. While the design of the hosted map is responsive and able to populate the symbols at a quick rate, some of the symbols look graphically lower quality. It is logical that with several of the phenomenon occurring within similar locations, some of the points would overlap. However, without any of the symbols having a distinct outline, the data visually runs together. There are also some issues where the data points are so small and transparent that they are hard to see. 

In this way, the map could benefit from improving the symbology and making the data more distinguishable. Even though hovering over the data points shows their information and changes them to white to stand out, it would make it easier to read if the symbols were higher quality and more well-defined. Adding outlines to and increasing opacity of the points provide an overall better user experience and design.  

### REFLECTION

After analyzing the totality of the project in terms of its purpose, systematic architecture, and methods of visualization, it is now important to delve further into the grander context and socioeconomic implications of creating and using this kind of map. Some relevant key take form in finding the context of the data, realizing the 
	 
In not only treating
