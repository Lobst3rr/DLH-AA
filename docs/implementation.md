# Implementation

## Introduction
TODO: Describe the system implemented (Describe the dataset. Are there any known issues? Describe any configuration data).




## Project Structure 


The image below it showcases how there are 4 pages of code home.html, search.html, layout.css and RouteSuggestions. home.html is the main menu meaning that this page is where users will be first introduced to and navigate through, search.html is also integrated with home.html search.html inclused the map of facilities as well as all the table displaying all the information of the facilieties, layout.css contains the CSS for the website bringing the final look togteher.
![Image 07-05-2024 at 20 39](https://github.com/Lobst3rr/DLH-AA/assets/148768725/a8ac1848-1e9c-4b4b-a728-2e183a464b05)

When it comes to the doc folder it contains all of the relevant/ important documentation for the website/app.
![Image 07-05-2024 at 20 40](https://github.com/Lobst3rr/DLH-AA/assets/148768725/efc05a49-cbe6-496b-a4af-8df1209e3b8c)

## Software Architecture 

The architecture diagram provided below showcases how there are four major components. Which are the following BMX-Finder, open data Bristol, Maxp-Box and query. 
THE BMX-Finder component is positioned centrally. This is due to the reason that it acts as the primary application. The BMX-Finder component processes and manages queries making it serving the interface between the user and the data sources. 

The Open Data Bristol component is a data source component specifically providing data of the Bristol area. This can include many types of data for example, transportation or geographical data. Due to the component being connected to BMX-Finder it indicates  that our open data will be for BMX facilities. It will be receiving queries from and sends data back to the BMX-Finder.

As mentioned as "mapbox-gl"  this component is responsible for providing mapping services of the Bristol area specifically. Mapbox is known for being a popular tool option for integrating maps and location services into websites as well mobile applications. This means that the "mapbox-gl" component will be handling the geographical visualisation and spatial data that will be processing for the system.

Query is the circle that is between BMX-Finder, Open Data Bristol, and Mapbox suggesting that the query is the management or routing system that directs queries between BMX-Finder and both data sources which are Open Data Bristol and Mapbox. This component makes sure that data requests are handled efficiently and directed to the appropriate data source based on the nature of the query.

![Image 06-05-2024 at 21 22](https://github.com/Lobst3rr/DLH-AA/assets/148768725/834b0a27-6ead-47f8-9bb0-184e7ccfa42e)


## Bristol Open Data API


![Image 07-05-2024 at 18 15](https://github.com/Lobst3rr/DLH-AA/assets/148768725/5dbd4f40-954e-49ac-86e2-16964f58b52a)

The UML diagram that we made depicts how there is a hierarchical structure where the JSON object contains one or more feature objects. When it comes to features each feature has a set of attributes that describe specific characteristics as well as locations that are represented by coordinates.

