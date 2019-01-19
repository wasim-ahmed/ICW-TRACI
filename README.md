# ICW-TRACI
SUMO-TRACI Integration for ICW

This project is about creating an Intersection Collision scenario and retreiving real time values in a program.

1. Creating a ICW scenario
  The intersection collision is created at junction on real map by adjusting the speed of vehicles. One vehicle starts from X axis 
  and another from Y axis and they collide at junction. Currently nothing is being done on an event of collision. Maps are taken 
  from Open Street Maps

2. Retreiving the real time values
 The real time values of Location [latitude,longitude] & Speed are received in c++ program via TRACI Client.

SUMO version utilised is 	
TRACI includes the Xerces version  
Projectis build on windows MinGW 4.8.1
