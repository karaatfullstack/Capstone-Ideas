## Pandemic

#### Overview
Pandemic is a collaborative strategy board game in which 2-4 players must work together to eliminate 4 diseases across the world before humanity is eliminated. Create an application to replicate [this board game][https://www.zmangames.com/en/products/pandemic/]. Reference project [here][https://www.fullstackacademy.com/final-projects/planetamic] 

#### MVP
A player should be able to use the web application to play with multiple people over a network and follow the same move set as the board game. There should be a rendering of the map that shows every city in the game with its relevant statistics. There should be a turn counter that restricts player actions to the current player and enacts the between-turn infection logic. 

#### Stretch Goals
* Simultaneous games can run at the same time. 
* Players can select from the range of specialized characters (research scientist, dispatcher, etc.)
* Pandemic Legacy. An extension to the standard game in which characters are maintained over multiple games.

#### Technical Challenges
* Complex logic - can be dealt with by extracting logic into the models, or building a microservices architecture. 
* State management on the front and back-end. 
* Multiple character roles.
* Real time updating of multiple clients.

#### Suggested Stack
* Firebase (or other noSQL DB) for persistent data storage and logic on the backend.
* Socket.io or Firebase for realtime updating.
* React 
* Redux for frontend state management (optional, as many developers prefer to interface directly with Firebase)
