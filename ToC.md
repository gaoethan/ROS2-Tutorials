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
    - Message filters
    - Bridge non-inherent messages between ROS1 and ROS2
  * Transform coordinate with ROS2 tf2
  * Create and publish robot model in ROS2
  * ROS2 threading models
    - Single threaded executor
    - Multi-threaded executor
  * Customize message and service with rosidl
  * ROS2 with different DDS and QoS
  * Secure ROS2 node with DDS security plugins
  * Run ROS2 with RTOS(Linux)
  * Release ROS2 packages with bloom
