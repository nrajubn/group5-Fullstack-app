# Group5-Fullstack-App

Welcome to 'The Hunt', a full-stack location-based game app.


- Heroku Link : https://grp5-full-stack-app.herokuapp.com/
- Link to homepage showing two color components : https://grp5-full-stack-app.herokuapp.com/
- Link to /location : https://grp5-full-stack-app.herokuapp.com/location

## Overview 
- A location-based gaming application that assists the user in finding the treasure. 
- It first compares the device's coordinates to the target position and informs the user whether he or she is inside or outside of it. 
- When the user clicks/touches the first color, it displays a correct treasure location and also a confirmation message stating that a specific location has been chosen will appear.
- Even after confirmation, the user is given the option to choose a different spot, and if so, the game can be restarted from the beginning.
- Whether the user is inside the treasure location and selects or touches the second color, the user will hear information that a treasure has been won; if the user is outside the target location, the user will hear information about help in finding a treasure like direction to walk, how far away from it, or any other clue.

## User stories 

- [X] As a player, I want to touch/click the first color to request a valid (treasure) location.
- [X] As a player, I want to hear confirmation that a location has been selected (so I can I can begin searching). 
- [X] As a player, I want to touch/click the second color:  If I am outside the treasure location, I want to hear information to help me find the treasure location (clue? how far away? what direction to walk?)
- [X] As a player, I want to touch/click the second color: If I am inside the treasure location, I want to hear and see confirmation that I have earned this treasure.
- [X] As a player, after confirmation that I have earned a location: I want the game to ask me if I would like to select another location. If I select yes, we reset and begin again. 

## Stack
- Platform: Node(Version - v15.1.0)
- Web Framework : Express
- View engine : EJS
- ORM(Object Relational Mapping) : Sequelize
- Data store: PostgreSQL
- API : Google Maps
- Coding standards : Enforce AirBnB/Prettier/ESlint

## Team Members:

<table>
  <tr>
   <td align="center"><a href="https://github.com/nrajubn"><img src="https://avatars.githubusercontent.com/u/60019513?s=460&u=6601ccba9a28d0a3095067e657e7305603bd6dda&v=4" width="100px;" alt=""/><br /><sub><b>Raju Nooka</b></sub></a><br /></td>
  
  <td align="center"><a href="https://github.com/Avisakula123"><img src="https://avatars.githubusercontent.com/u/60164504?s=460&u=9401e8b6d44679177550d9b4b5c574cb9100c975&v=4" width="100px;" alt=""/><br /><sub><b>Rohith Reddy Avisakula</b></sub></a><br /></td>
</tr>
</table>

## Reference

- [Web App fall 2020](https://github.com/denisecase/web-app-2020-fall)
- [Group11-FullStack](https://github.com/KHARIKA17/Group-11-Full-stack-app)
