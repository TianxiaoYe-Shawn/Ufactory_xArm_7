# Ufactory_xArm_7
This repository stores the ROS code for the xArm 7 robotic arm in ARClab.


Created by [TianxiaoYe](https://github.com/TianxiaoYe-Shawn). If you have any questions, please contact via email: **tye46@wisc.edu**
***
*This code repository is based on Ubuntu 20.04 and ROS Noetic version.*
## XArm 7 Controller Simulation

First, try controlling the xArm 7 in the simulator. Currently, three different methods have been identified, all based on the [MoveIt open-source library](https://github.com/moveit/moveit).
### 1. Moveit! graphical control interface + Gazebo simulation environment

Follow the tutorial [here](https://github.com/xArm-Developer/xarm_ros/tree/master?tab=readme-ov-file#3-preparations-before-using-this-package) to set up all environment and [here](https://github.com/xArm-Developer/xarm_ros/tree/master?tab=readme-ov-file#55-xarm7_moveit_config) to control the robot arm using Moveit! graphical interface.

https://github.com/user-attachments/assets/c9b7970a-e4c6-45c4-8fe2-577a3467c3ac

### 2. xArm_planner interface + RViz simulation environment

Follow the tutorial [here](https://github.com/xArm-Developer/xarm_ros/tree/master?tab=readme-ov-file#56-xarm_planner) to learn how to use the xarm_planner ros package and control the robot arm by calling ros service.

https://github.com/user-attachments/assets/21aa5541-43a9-40fc-b8a7-f8d74a967008

### 3. Move Group C++ Interface + RViz simulation environment

After you are familiar with the basic configuration of xarm and moveit, you can try to use this ros package which rewrites the code of the moveit official tutorial to equip the xArm7 robotic arm. Related moveit official tutorial is [here](https://moveit.github.io/moveit_tutorials/doc/move_group_interface/move_group_interface_tutorial.html).

https://github.com/user-attachments/assets/6b35ff59-e285-4f49-a322-541d78fc9d75







