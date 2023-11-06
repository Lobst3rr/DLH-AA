# Requirements

## User Needs

### User stories
Ayrton Merritt suggests as a BMX rider I want to find BMX Facilities nearest to me so that I do not have to travel far
Shawn Orozco suggests as a driver I want BMX riders to stay off the road so that I do not get stuck in traffic.

As a BMX rider I want to locate and find BMX facilities so that I'll be able to practice my tricks in a safe space
and ride as much as I want and not disrupt the public.

### Actors
- BMX Riders 
- Skaters
- Scooter Riders
- Members of the public 
- People who are looking for socialisation 

### Use Cases
TODO: Describe each use case (at least one per team member).
    Give each use case a unique ID, e.g. UC1, UC2, ...
    Summarise these using the use-case template below.

| USE-CASE | UC1 | 
| -------------------------------------- | ------------------- |
| **Description** | As a BMX Rider I want to find the nearest skate park or BMX facility to me |
| **Actors** | BMX Rider, Skater |
| **Assumptions** | Browser supports geo-location, user knows how to navigate basic applications</td></tr>
| **Steps** | <ol><li> Opt to view table of skate parks or BMX facilities</li> <li> Request permission to access user location</li> <li> Giver permission for geo-location</li> <li>Get nearest facilities for BMX riders and skaters from database</li> <li> View table of nearest facilities for BMX riders and skaters</li> |	
| **Variations** | <ol><li> Browser does not support geo-location </li> <li> BMX only facilities </li> |
| **Non-functional** | The application should run on most browsers |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |


| USE-CASE | UC2 | 
| -------------------------------------- | ------------------- |
| **Description** | As a social person I want to find a place to socialise |
| **Actors** | citizen |
| **Assumptions** | Browser supports geo-location, user knows how to navigate basic applications</td></tr>
| **Steps** | <ol><li> Opt to view table of skate parks or BMX facilities</li> <li> Request permission to access user location</li> <li> Giver permission for geo-location</li> <li> locate nearest facility that is a hotspot </li> <li> view the facilities that has the best rating for a social spot</li> |	
| **Variations** | <ol><li> Browser does not support geo-location </li> <li> less hot social spot BMX facility </li> |
| **Non-functional** | The application should run on most browsers |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |


TODO: Your Use-Case diagram should include all use-cases.
![IMG_5906](https://github.com/Lobst3rr/DLH-AA/assets/148768725/788091c0-290d-4e15-ba81-332324f7faef)


## Software Requirements Specification
### Functional requirements
FR1: The system shall get user geo-location from navigator.geolocation
FR2: The system shall get nearest BMX facilities from database 
FR3: The system shall get ratings from google ratings
FR4: The system shall get traffic news from news
FR5: The system shall get bike routes from googlemaps
FR6: The system shall get input from keyboard/user

### Non-Functional Requirements

Give each non-functional requirement a unique ID. e.g. NFR1, NFR2, ...

Indicate which UC the requirement comes from.
