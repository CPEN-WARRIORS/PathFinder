# The Pathfinders

> *Simplifying everyday campus experiences with accessible technology*

## Team Members

| Name | Student Number | Role |
|---|---|---|
| Bianca Li | 66827403 | Project Manager |
| Harrison Tidy | 55532510 | Designer |
| Wilfred Chow | 42698951 | Developer |
| Shreya Srinath | 35430461 | Developer |
| Hasna | 90442450 | Developer |

## Theme

Campus Life

## Mission Statement

Simplifying everyday campus experiences with accessible technology

---

## Problem

UBC Vancouver is one of the largest campuses in Canada, spanning over 400 hectares with hundreds of buildings. For new students that arrive every September, this transition can feel overwhelming at times especially for those who have traveled far from home.

Finding classrooms and navigating the campus can be particularly hard for these unfamiliar students. Class schedules often list locations using building abbreviations and room numbers such as “ICCS 008”. For someone new to campus, this means nothing to them and it just makes it more difficult for them to find their way around especially with some of the layouts UBC buildings have. Although UBC provides their own navigation website, buildings are cluttered and paths are unclear, adding little to no help to these new students.

This challenge becomes even more frustrating when buildings have the same name or multiple entrances that lead you to completely different areas. New students shouldn’t be spending unnecessary time searching for their classrooms when they can spend that time instead meeting new people and experiencing campus life.

---

## Solution

To address this longstanding issue, our team plans to develop a website to help guide students to their classrooms more easily. Our team will leverage Leaflet, an open source library, to render an interactive map of UBC’s Vancouver campus. Users will be able to search for buildings and classrooms using their abbreviations and then a path will be displayed to them based on their current location.

### Core Features

- **Interactive Campus Map** - Display an interactive map of UBC Vancouver using Leaflet
- **Building and Classroom Search** - Sidebar to enter classroom and building names with a dropdown showing relevant options
- **Walking Directions** - Provide a walking route based on the user’s location and their destination
- **Building Information** - Display relevant information about the building such as number of floors

### Dependencies

- **Leaflet** - Open source Javascript library used to render and interact the campus map
- **UBCGeodata repository** - Provides geospatial data for buildings around the campus
- **Flask / Django (TBD)** - Framework used to handle frontend and backend operations

### Mockup User Interface

| Search Sidebar | Map View |
|:---:|:---:|
| <img height="360" alt="Search sidebar" src="https://github.com/user-attachments/assets/7a4834aa-3ae4-4bd4-a24b-455b4d9d597f" /> | <img height="360" alt="Leaflet map view" src="https://github.com/user-attachments/assets/2659cdb8-46f8-4fc8-8ff6-3a1ad883660b" /> |
