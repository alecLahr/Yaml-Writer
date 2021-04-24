ENPM809E
Project 3

---

1) Add location_recorder package to the src directory of your catkin workspace
2) Ensure the aws-robomaker-small-house-worls and mapping packages are also in the catkin workspace
3) Start ros master with: roslaunch mapping start_navigation.launch
4) Start yaml recorder node with: rosrun location_recorder room_recorder
5) Teleoperate turtlebot into desired room
6) Record location to yaml with: rosservice call room_service "room_name"

