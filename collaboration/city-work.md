## City Work Crew Job Tracker

#### Overview

The city managers of your city have a problem:

Potholes.

- They're in the roads.
- They're in the streets.
- They're uptown, downtown, everywhere you look: potholes.

The citizens of your city aren't pleased with the way the roads are getting fixed.
Trouble is, nobody knows what's going on, where the potholes are, and which holes should be prioritized.

We've identified three key groups who are involved:

1: Citizens: They drive on the roads and pay taxes for their upkeep. They're often the first to notice that a new pothole has formed when they drive over them.
2: City managers: They're responsible for assessing citizen's needs and allocating resources efficiently and fairly.
3: City road-crew workers: They're out there, on the street, doing the actual work of filling in potholes.

It's been identifed that a custom mobile and web application could help bring all these groups into balance and help get those pot-holes filled!

#### MVP

- Mobile application that Citizens and City Surveyors can use to report the locations of potholes they'd like to be repaired.
  - Citizens can photograph a pothole and mark it's location on a map.
  - Citizens can "upvote" other potholes to emphasize the importance of that pothole.

- Mobile application for work crews
  - Work crews out in the city need to know which pot-hole to fix next, so they should be shown a map with directions to their next highest priority pot-hole.
  - When work-crews fill a pot-hole they should confirm their work by photographing the completed work-site.

- Web browser accessible application for city administrators
  - Citizens are a good source of information, but city resources need to be allocated fairly. City administrators need to be able to re-set priorities.
  - Administrators need to see that work is getting completed, so they should see daily reports of where different work crews filled in potholes.


#### Stretch Goals
Capstone teams will be encouraged here but given a set of stretch goals that are possible extensions to the MVP

- Budgeting
  - Assign costs to filling potholes, estimate the cost of damages incurred daily by potholes and calculate the most efficent routes for work crews to hit the highest priorty pot-holes.

- Reporting
  - Generate nice looking reports showing rate of reporting / completed work so city administrators can share results with citizens.

- Real-time Mapping
  - Show citizens their dollars are hard at work: show where work crews are fixing things up in real time.


#### Technical Challenges
- Role-based access control (Administrators, Citizens, Workers)
- Multiple clients, single API (Mobile Applications, Web Applications)
- File storage/photo upload
- Geographical location data
- Real-time communications
- Mobile Camera Access

#### Suggested Stack
- Role-based access control (Administrators, Citizens, Workers)
  - Role system is relatively simple, so can likely be solved directly in the Fullstack Stack without reaching for extra libraries.

- Multiple clients, single API (Mobile Applications, Web Applications)
  - Can be solved with either
    - Progressive web-app
    - Expo/create-react-native-app

- File storage/photo upload
  - Good fit for an image storage service
    - https://cloudinary.com/ is popular
  - Source of images depends on choice of mobile platform.
    - Expo has decent camera access.
    - Mobile browser:
      - navigator.mediaDevices
      - <input type="file" accept="image/*;capture=camera">

- Geographical location data
  - Postgis
  - mapbox
  - Expo map

- Real-time communications
  - Direct Websocket is a good fit if application data is stored in a SQL database
  - Firebase could also be used to store data for this project.

#### References
*[Pothole Patrol](https://youtu.be/0CN3UoDTUW8)
