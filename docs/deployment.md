# Deployment

## Release Notes Ayub part 


The deployment diagram only shows 2 key nodes, the architecture which are the GitHub.io node which serves as he primary web hosting environment and the Open Data Bristol node which functions  the external data provider. the deployment UML diagram that is displayed its illustrating the architecture of the BMX-finder application. The component GitHub.io (BMX-Finder) is a component that is hosted on GitHub meaning the BMX-Finder system will be in an environment in which it is acting as the central application that handles and serves the BMX facility data to the end users. The Open Data Bristol (Public BMX Facilities) is another component but not like the previous component. This component is identified as the data provider for the BMX facilities information meaning it will be providing up to date information, how does it work ? It works by using public BMX facilities data which is in an open data format that is retrieved from Bristol’s Open data repository.  When it comes down to connections of things the BMX-Finder system retrieves data from the Open Data Bristol, this leads to the data hen being processed and later formatted before being showcased through via GitHub pages. With dependencies the existence of GitHub.io indicates how the system will be using web technologies such as the following HTML,JavaScript and finally CSS. The data integration is also going to be requiring additional JavaScript libraries or tools for the purpose of fetching and the visualisation.  Looking at the diagram we decided that there could be some known issues even though it’s not detailed enough. We collectively thought and came to an agreement that an issue can be he Open Bristol Data. This is due to the reason that we need to ensure that the Open Data Bristol remains  both accessible and reliable data source.
Describe the deployment of software components to hardware nodes using a UML Deployment diagram.

![Image 07-05-2024 at 03 41](https://github.com/Lobst3rr/DLH-AA/assets/148768725/36efb2d3-3e4f-4488-984d-1b57a24a3572)

# User guide Defyn
## Home Page 

![Screenshot 2024-05-07 195337](https://github.com/Lobst3rr/DLH-AA/assets/148768832/c8016a62-215e-4256-b011-35dcef7bd404)
This is the Home page where the introduction to the website begins from first glance there is a Search Facilities button that if clicked on will bring you to the search page. 
![Screenshot 2024-05-07 195350](https://github.com/Lobst3rr/DLH-AA/assets/148768832/b13d0fe8-6c00-4c0d-8394-6f176356baa7)
In this half of the page you can see that there is a button called route suggestions which upon clicking on it changes the page to the Route Suggestions Page. At the very bottom of this page is a Quick Links Title and underneath it is where all the links to the pages will be for quick access on every page.

## Search Page
![Screenshot 2024-05-07 200519](https://github.com/Lobst3rr/DLH-AA/assets/148768832/47fcddc8-3d6a-4c7e-8b9d-df9837a30e84)
This is the search page in which is the map that shows the data of every BMX facility in Bristol using OpenDataBristols API.
![image](https://github.com/Lobst3rr/DLH-AA/assets/148768832/9582200e-0355-4bcc-bfe8-cb005a7c86c8)
clicking on the marker reveals what the facility is called as well as what part of bristol it is in 
![Screenshot 2024-05-07 200535](https://github.com/Lobst3rr/DLH-AA/assets/148768832/d93f61eb-f2ff-4e75-83f0-af37944d8526)
On the bottom half of the website is the list of all facilities in case you can't see it on the map. it shows the longitude and latitude of the lcoation so you can find it upon search.

