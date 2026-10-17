<h1><img height="40" alt="The Pathfinders logo" src="https://github.com/user-attachments/assets/f4916f8a-56fc-4722-a710-fae2e12b1f27" align="top" /> Pathfinder</h1>

> *To make every classroom at UBC Vancouver easy to find, one step at a time. *

## Team Members

| Name | Student Number | Role |
|---|---|---|
| Bianca Li | 66827403 | Project Manager |
| Harrison Tidy | 55532510 | Designer |
| Wilfred Chow | 42698951 | Developer |
| Shreya Srinath | 35430461 | Developer |
| Hasna | 90442450 | Developer |

## Theme

To make every classroom at UBC Vancouver easy to find, one step at a time.

## Mission Statement

Simplifying everyday campus experiences with navigation

---

## Problem

UBC Vancouver is one of Canada's largest university campuses, spanning over 400 hectares with hundreds of buildings. Finding classrooms and navigating campus can be particularly challenging for students unfamiliar with the area.

Class schedules often list locations using building abbreviations and room numbers, such as “ICCS 008.” A student new to campus might open a navigation app to find the building, but what happens once they enter the main lobby? What if the app leads them to the back entrance? What about buildings that are interconnected?

Navigation apps, such as google maps or UBC Wayfinding, only offers directions between buildings, not between individual classrooms inside of the buildings. While floor maps are publicly available, they still leave students to figure out the route to their classrooms themselves. 

New students shouldn't have to spend unnecessary time searching for their classrooms when they could instead spend that time meeting new people, exploring campus, and experiencing university life.

---

## Solution

To address this issue, our team plans to develop an **outdoor and indoor** navigation website that provides directions not only to buildings but also to **individual classrooms within those buildings**. Using Leaflet, an open-source mapping library, we will create an interactive map of UBC Vancouver and integrate existing UBC building floor plans to enable indoor navigation. Users will be able to search for buildings and classrooms using their names or abbreviations, then receive walking directions from their current location to their destination, all the way to the classroom door.

### Core Features

- **Interactive Campus Map** - Display an interactive map of UBC Vancouver using Leaflet
- **Building and Classroom Search** - Sidebar to enter classroom and building names with a dropdown showing relevant options
- **Walking Directions** - Provide a walking route from the user’s location to their destination all the way until their classroom door.

### Dependencies

- **Leaflet** - Open source Javascript library used to render and interact the campus map
- **UBCGeodata repository** - Provides geospatial data for buildings around the campus
- **Flask / Django (TBD)** - Framework used to handle frontend and backend operations

### Mockup User Interface

| Search Sidebar | Map View |
|:---:|:---:|
| <img height="360" alt="Search sidebar" src="https://github.com/user-attachments/assets/7a4834aa-3ae4-4bd4-a24b-455b4d9d597f" /> | <img height="360" alt="Leaflet map view" src="https://github.com/user-attachments/assets/2659cdb8-46f8-4fc8-8ff6-3a1ad883660b" /> |
