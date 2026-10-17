<h1><img height="40" alt="The Pathfinders logo" src="https://github.com/user-attachments/assets/f4916f8a-56fc-4722-a710-fae2e12b1f27" align="top" /> Pathfinder</h1>

> To make every classroom at UBC Vancouver easy to find, one step at a time. 

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

### Evidence

The following Reddit posts from the UBC subreddit highlight difficulties students have experienced when navigating the campus and finding classrooms.

| Source | Student Issue |
|---|---|
| [Looking for someone to show me around campus](https://www.reddit.com/r/UBC/comments/pg3uy3/looking_for_someone_to_show_me_around_campus/) | A new student voices their concerns about finding their way around campus and asks for help |
| [Need help finding a study hall for exam](https://www.reddit.com/r/UBC/comments/revkjd/need_help_finding_a_study_hall_for_exam/) | A student struggles to locate their exam room despite already being inside the correct building. |
| [Bro where is this room](https://www.reddit.com/r/UBC/comments/1jyl7zd/bro_where_is_this_room/) | A student struggles to locate a specific room inside IKB |

---

## Solution

To address this issue, our team plans to develop an **outdoor and indoor** navigation website that provides directions not only to buildings but also to **individual classrooms within those buildings**. Using Leaflet, an open-source mapping library, we will create an interactive map of UBC Vancouver and integrate existing UBC building floor plans to enable indoor navigation. Users will be able to search for buildings and classrooms using their names or abbreviations, then receive walking directions from their current location to their destination, all the way to the classroom door.

### Core Features

- **Interactive Campus Map and Path Finder** - Display an interactive map of UBC Vancouver using Leaflet
- **Building and Classroom Search** - Sidebar to enter classroom and building names with a dropdown showing relevant options
- **Mapping Classroom Walks** - Provide a walking route from the user’s location to their destination all the way until their classroom door.

## User Interactions

### 1. Searching For a Destination

- Users enter a building name or abbreviation into a search section located in the sidebar.
- A dropdown menu will display relevant buildings and classrooms as the user types.
- If no building is found, the sidebar will show a message indicating to the user that there were no results.

### 2. Selecting a Starting Location

- Users will be prompted, “Use My location”, to automatically determine their current location using browser location services.
- Once a location is selected, a marker will indicate to the user their starting position.
- Written and audible instructions will be available.

### 3. Navigating to a Destination

- After selecting a starting location and destination, users can click a button to generate a walking route.
- A path will be highlighted on the map to the classroom / building the user entered

### 4. Changing Navigation

- Users would also be able to click and interact with the map to pan, zoom, and select locations on the map.
- Users will be able to click on a button that ends their current journey.

### 5. Adaptive Screen Sizes

- Website will resize automatically based on the user’s device size that will be grabbed from the browser’s settings.

### 6. Indoor Classroom Guidance

- After arriving at the building destination, users will be able to view information about their selected classroom.
- The website will display the classroom’s floor number and there will be written directions to help users locate a room in the building.
- Users will be able to click a button to have the instructions read aloud.
- Indoor directions will be provided for supported classrooms using predetermined instructions. Supported classrooms will be common rooms.
- For classrooms without available indoor directions, the website will display the building location and any available classroom information.
  
### Error Handling

| Error | Expected Behaviour |
|---|---|
| Location permission denied | Users will be prompted to manually select their starting location on the map |
| Unable to determine current location | An error message will appear, asking users to try again or manually select a starting location |
| Walking route could not be generated | An error message will inform users that no walking route is available for their selected destination |
| No starting location selected | Users will be prompted to select a starting location before generating a route. |
| No matching search results | The sidebar will display a message indicating that no matching buildings or classrooms were found. |

### Mockup User Interface 

| Search Sidebar | Map View | 
|:---:|:---:|
| <img height="360" alt="Search sidebar" src="https://github.com/user-attachments/assets/7a4834aa-3ae4-4bd4-a24b-455b4d9d597f" /> | <img height="360" alt="Leaflet map view" src="https://github.com/user-attachments/assets/2659cdb8-46f8-4fc8-8ff6-3a1ad883660b" /> 

&nbsp;

| Routing Example | Location Request Example |
|:---:|:---:|
| <img width="376" height="272" alt="Routing Example" src="https://github.com/user-attachments/assets/792984d7-5c8a-468c-8aaf-a26cce66a60b" /> | <img width="460" height="288" alt="Location Request Example" src="https://github.com/user-attachments/assets/151baa08-975a-4446-bba8-34ce4473db87" /> |

