## Getting Started
 Source the workspace then:

# export TURTLEBOT3_MODEL=burger
# roslaunch turtlebot3_gazebo turtlebot3_house.launch

then open anew terminal

# export TURTLEBOT3_MODEL=burger
# roslaunch turtlebot3_slam turtlebot3_slam.launch

open anew terminal

# export TURTLEBOT3_MODEL=burger
# roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch

start moving in order to make the map then use this command to save your map

# rosrun map_server map_saver

then in order to navigate autonomously use this command

# roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml
