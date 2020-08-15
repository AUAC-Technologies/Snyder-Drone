# Snyder-Drone

### Project Hardware RoadMap:

Across all releases there would be iterative UAV body design to allow for higher load capacity.

![alt text](https://github.com/nyameaama/Autonomous-UAV/blob/master-platformio/CAD%20models/Body%20Prototype/Screen%20Shot%202020-06-28%20at%206.02.01%20PM%2010.28.38%20AM.png)

Initial body design. See docs for design updates

#### Release 1.0
* UAV design with load capacity of ...[(Technicalities)](https://github.com/nyameaama/Autonomous-UAV/blob/master-platformio/docs/technical.md)
* ATMEGA 2560 based microcontroller running on an arduino development board for UAV computer
* ATMEGA 328p based microcontroller running on UAV remote
* HC-SRO5 bluetooth modules x2
* GPS modules x2

#### Release 2.0
* Increased UAV load capacity
* Custom PCBs for controllers 

### Project Firmware RoadMap:

#### Release 1.0
* Autonomous UAV localisation and tracking between remote and vehicle based on GPS and bluetooth
* Active Obstacle Avoidance using ultrasonics

#### Release 2.0 
* Implementation of liDAR or camera for object detection and tracking

#### Future releases
* Mobile app to use as remote
* System for recognizing No-Fly-Zones
* Gesture Recognition
