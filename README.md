# Bumperbot – ROS2 Jazzy Differential Drive Robot

## Overview
Bumperbot is a differential-drive mobile robot simulation built using **ROS 2 Jazzy**, **Gazebo**, and **RViz**.  
The project focuses on understanding and implementing low-level robot control, odometry, and simulation-based testing in a ROS 2 environment.  

At the current stage, the robot can be controlled via **ros2_control** by directly publishing velocity commands to the left and right wheels. The system also provides odometry feedback for visualization and analysis in RViz.  

Future extensions will include:
- Localization and Mapping (SLAM)
- Motion Planning and Navigation
- Computer Vision for perception and obstacle avoidance

## Features Implemented
- Custom robot model integrated with Gazebo simulation  
- Differential drive kinematics using **ros2_control**  
- Wheel velocity control through terminal input  
- Odometry feedback visualization in RViz  

## Tech Stack
- **ROS 2 Jazzy**  
- **Gazebo** (simulation)  
- **RViz** (visualization)  
- **ros2_control** (actuation and control)  

## Next Steps
This project is under active development. Planned features include SLAM, path planning, and integration of vision-based perception.  

---
