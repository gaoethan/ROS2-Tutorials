# ROS2 Overview

# Installation of ROS2
  * Install ROS2 in Linux
    - Binary Installation
    - Source Installation
  * Install ROS2 in Windows
    - Bianry Installation
    - Source Installation
  * Install ROS2 in Mac OS X
    - Binary Installation
    - Source Installation
  * Install ROS2 with Virtual Machine
  * Install ROS2 with Docker
  * Install ROS2 with Raspberry Pi
  * Maintain the source for source installation

# ROS2 Archetecure and concepts
  * Build System
    - ament_package
    - ament_cmake
    - ament_tools
    - ament_lint
  * Filesystem level
    - workspace
    - package manifest
    - cmake compiling file
    - messages
    - services
    - resource management
  * Graph level
    - nodes
      - IPC(Intra Process Communication) nodes
      - managed nodes 
    - topics
    - services
    - messages
    - parameters
  * Client library
    - rcl
    - rclpy
    - rclcpp
  * Middleware Interface(rmw)
    - Common Part
    - Middleware specific 
  * DDS

# Basic ROS2 development
  * Create a ROS2 package with Python
  * Create a ROS2 package with C++
  * Create messages and topics(Python/C++)
    - message file(.msgs)
    - topics
    - interact message and topic with command lines
  * Create nodes(Python/C++)
    - publiser node
    - subscriber node
    - create nodes with timer
    - play node with ros2 command lines
  * Create services(Python/C++)
    - service file (.srv)
    - client node
    - service node
  * Create and enable ROS2 tests
    - gtest for ROS2 C++
    - unittest for ROS2 Python
  * ROS2 remapping
    - namespace and node name remapping
    - topic and service remapping
  * Operate ROS2 parameters
    - set parameters
    - get parameters
  * Ros2 launch
  * Virtulization and Debugging
    - debug with logger
    - debug with gdb
    - rviz2
  * Bridge ROS1 and ROS2 with ros1_bridge

# Advanced ROS2 development
  * Nodes
    - Multi-nodes composition
    - Manage Lifecycle node
    - IPC nodes
    - Native C++ node 
  * Messages
    - Blend multi-messages with message filters
    - Bridge non-inherent messages between ROS1 and ROS2
  * Transform coordinate with ROS2 tf2
    - static tf
    - tf broadcast
    - tf listening
    - tf debugging
  * Create and publish robot model in ROS2
    - Create URDF
    - robot_state_publiser
  * ROS2 threading models
    - Single threaded executor
    - Multi-threaded executor
  * Customize message and service with rosidl
  * ROS2 with different DDS and QoS
    - Reliable policy
    - Best effort policy
  * Secure ROS2 node with DDS security plugins
  * Run ROS2 with RTOS(Linux)
  * Release ROS2 packages with bloom

# Using sensors and actutors in ROS2
  * teleoperation 
    - control using keyboard
    - control using joystick
  * Arduino to add sensors and actutors
    - controlling in Arduino
    - rosserial 

# ROS2 Perception
  * Interact with camera 
    - obtain and publish RGB image
    - obtain and publish depth image
    - obtain and publish point cloud data
  * Raw images processing
    - conversion with image pipeline
    - proceed images using opencv with cv_bridge in ROS2
  * Point Clouds
    - ROS2 pcl interface
      - create point clouds
      - filter and downsample
      - registration and matching
      - partition
      - segamentation
    - depth to pointcloud2
  * depth to laser scan
  * visual odometry
  * object detection and classification (`TBD`)
  * camera calibration

# ROS2 Controlling and Manipulation
  * ROS2 control
    - control manager
    - effort_controller
    - joint_state_controller
    - position_controller
    - velocity controller
    - gazebo_ros_control plugin
  * Moveit
  * Simulatation with Gazebo

# ROS2 SLAM and navigation
  * Locate and map with catographer in ROS2
    - Lidar
    - Vision
  * Create a map
    - save the map using map_server
    - load the map using map_server
  * Publish IMU and LaserScan
  * AMCL
  * Configure move_base
    - common paramters
    - global planner and global costmap
    - local planner and local costmap
  * Run and control in rviz
    - Initial 2D pose estimation
    - Set 2D nav goal 
  * Run with turtlebot2 via ros1_bridge


