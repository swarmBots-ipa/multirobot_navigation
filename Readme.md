# Multi Robot Navigation for SwarmBot 
This ROS 2 package is responsible for the navigation while maintinaing the formation of the robots.
## 1. Bringup the multirobot simulation, Localization and Pathplanning
````
ros2 launch multirobot_bringup multirobot_bringup.launch.xml
````
## 2. Send pallet pose from rviz2
````
ros2 run multirobot_formation agent_formation 4
````
number of agents can be anywere from 1 to infinity

