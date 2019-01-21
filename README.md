# ICW-TRACI
SUMO-TRACI Integration for ICW

This project is about creating an Intersection Collision scenario and retreiving real time values in a program.

1. Creating a ICW scenario
  The intersection collision is created at junction on real map by adjusting the speed of vehicles. One vehicle starts from X axis 
  and another from Y axis and they collide at junction. Currently nothing is being done on an event of collision. Maps are taken 
  from Open Street Maps

2. Retreiving the real time values
 The real time values of Location [latitude,longitude] & Speed are received in c++ program via TRACI Client.

SUMO version utilised is 1.0.1
TRACI includes the Xerces version 3.2.0 specially built for SUMO, can be found @ https://sourceforge.net/projects/sumo/files/dependencies/   
Project is build on windows MinGW 4.8.1

Steps to run:
1. Configure the SUMO on your system
2. Navigate to ICW_SUMO directory & run simulation using command :
	sumo-gui -c icw.sumo.cfg --remote-port 8000
3. Navigate to ICW_TraciClient directort & run Traci_Client.exe.
4. Adjust the Delay from Sumo Gui to visualize the simulation properly set delay slider to 300.
5. Click the Start.
6. You should receive the data on to terminal.
