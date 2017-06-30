Sawyer_Gazebo
=============

This package contains a gazebo model and controller configuration for the Rethink Robotics arm Sawyer.

 - sawyer_gazebo : Simulation robot description and demo
 - sawyer_control : Control configuration for Sawyer in simulation

To use these packages, install the following into your catkin workspace and catkin make

 - cd ~/catkin_ws/src/
 - git clone https://github.com/johodges/sawyer_gazebo
 - git clone https://github.com/RethinkRobotics/sawyer_robot
 - git clone https://github.com/RethinkRobotics/intera_sdk
 - git clone https://github.com/RethinkRobotics/intera_common
 - git clone https://github.com/RethinkRobotics/sawyer_moveit
 - git clone https://github.com/johodges/husky_sawyer_moveit_config
 - cd ~/catkin_ws && catkin_make

Optionally, to use the Sawyer arm with the Virginia Tech unmanned ground vehicle, TREX and/or the Clearpath Robotics Husky, install the following into your catkin workspace and catkin make

 - cd ~/catkin_ws/src/
 - git clone https://github.com/johodges/trex
 - git clone https://github.com/johodges/husky_sawyer_moveit_config
 - cd ~/catkin_ws && catkin_make

To run sawyer by itself

 - roslaunch sawyer_gazebo playpen_sawyer.launch

To run the Sawyer with the TREX base

 - roslaunch sawyer_gazebo playpen_trex.launch

To run the Sawyer with the Husky base

 - roslaunch sawyer_gazebo playpen_husky.launch
