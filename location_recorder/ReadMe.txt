ENPM809E
Project 3

---

- Install yaml module with: pip install PyYAML==5.1.2
- Add location_recorder package to the src directory of your catkin workspace
- Ensure the aws-robomaker-small-house-worls and mapping packages are also in the catkin workspace
- Start ros master with: roslaunch mapping start_navigation.launch
- Start yaml recorder node with: rosrun location_recorder room_recorder
- Teleoperate turtlebot into desired room
- Record location to yaml with: rosservice call room_service "room_name"

