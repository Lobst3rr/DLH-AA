# Implementation

## Introduction
TODO: Describe the system implemented (Describe the dataset. Are there any known issues? Describe any configuration data).

## Project Structure
TODO: Provide an outline of the project folder structure and the role of each file within it.
provide a table listing the number of jslint warnings/reports for each module.

## Software Architecture

The architecture diagram provided below showcases how there are four major components. Which are the following BMX-Finder, open data Bristol, Maxp-Box and query. 
THE BMX-Finder component is positioned centrally. This is due to the reason that it acts as the primary application. The BMX-Finder component processes and manages queries making it serving the interface between the user and the data sources. 

The Open Data Bristol component is a data source component specifically providing data of the Bristol area. This can include many types of data for example, transportation or geographical data. Due to the component being connected to BMX-Finder it indicates  that our open data will be for BMX facilities. It will be receiving queries from and sends data back to the BMX-Finder.

As mentioned as "mapbox-gl"  this component is responsible for providing mapping services of the Bristol area specifically. Mapbox is known for being a popular tool option for integrating maps and location services into websites as well mobile applications. This means that the "mapbox-gl" component will be handling the geographical visualisation and spatial data that will be processing for the system.

Query is the circle that is between BMX-Finder, Open Data Bristol, and Mapbox suggesting that the query is the management or routing system that directs queries between BMX-Finder and both data sources which are Open Data Bristol and Mapbox. This component makes sure that data requests are handled efficiently and directed to the appropriate data source based on the nature of the query.

![Image 06-05-2024 at 21 22](https://github.com/Lobst3rr/DLH-AA/assets/148768725/834b0a27-6ead-47f8-9bb0-184e7ccfa42e)


## Bristol Open Data API


![Image 07-05-2024 at 18 15](https://github.com/Lobst3rr/DLH-AA/assets/148768725/5dbd4f40-954e-49ac-86e2-16964f58b52a)

The UML diagram outlines a refined framework that bridges the gap between raw geographic data and practical, usable applications that can be manipulated and render the data forcefully for different end users. The BMX-Finder UML is also designed to interact with a set of feature that will be containing a specific amount of data that are organised into attributes and geometrical coordinates. 

