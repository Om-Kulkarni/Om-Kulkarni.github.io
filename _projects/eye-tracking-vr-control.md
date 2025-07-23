---
title: "Eye Tracking Control for Robot Arm Manipulation in VR"
excerpt: "Implementation of an advanced eye tracking-based control system for Franka Emika Panda robot using Unity VR and ROS integration<br/><img src='/images/eye_tracking_vr_control.png' width='500' height='300'>"
collection: projects
permalink: /projects/eye-tracking-vr-control
location: "Bristol Robotics Laboratory, UK"
project_type: "Master's Dissertation"
date: 2025-07-01
---

### Project Resources
* **GitHub Repository**: [Pick and Place Eye Tracking VR](https://github.com/Om-Kulkarni/Pick_And_Place_Eye_Tracking_VR)

## Project Overview
This project implements an innovative eye tracking-based control system for robotic pick-and-place operations, integrating the Franka Emika Panda robot with Unity VR. The system enables users to intuitively select targets for robot manipulation using eye tracking technology in an immersive virtual environment.

### Key Features
* Eye tracking-based target selection in VR
* Precise robotic manipulation using Franka Panda
* Seamless ROS 1 integration with Unity
* Docker-based development environment
* Real-time pick and place execution

## Technical Implementation

### System Architecture
* **Unity VR Integration**: Custom implementation for immersive control
* **ROS Framework**: Complete ROS 1 Noetic integration
* **Robot Control**: Franka Panda arm with MoveIt
* **Communication**: ROS-Unity TCP bridge for reliable data transfer

### Core Components
* **Vision System**: 
  - Real-time eye tracking integration
  - Dual camera setup (top and front views)
  - Advanced object detection and tracking

* **Robot Control**: 
  - MoveIt-based motion planning
  - Real-time trajectory execution
  - Precise gripper control system
  - Collision detection and avoidance

* **VR Interface**:
  - Intuitive target selection mechanism
  - Real-time visual feedback
  - Interactive manipulation controls
  - Safety constraint visualization

### Technical Details
* **Motion Planning**:
  - Custom trajectory planning service
  - Dynamic obstacle avoidance
  - Real-time path optimization
  - Speed-controlled execution

* **Gripper Control**:
  - Precision grasping system
  - Force-feedback integration
  - Adaptive grip strength control
  - Multi-object manipulation capability

### Technologies Used
* Unity for VR Environment
* ROS 1 Noetic
* Franka ROS Packages
* MoveIt Motion Planning
* Docker Containerization
* Python for System Integration
* C# for Unity Development

## Development Infrastructure

### Docker Environment
* Containerized ROS workspace
* GUI support through WSLg
* Integrated development tools
* Cross-platform compatibility

### Communication Architecture
* TCP/IP-based ROS-Unity bridge
* Real-time state synchronization
* Robust error handling
* Low-latency data transfer

## Key Achievements
* Successful integration of eye tracking with robotic control
* Real-time motion planning and execution
* Robust safety implementation
* Intuitive user interface design
* Containerized development environment

## Future Development
* Enhanced eye tracking precision
* Multi-robot coordination
* Advanced gesture recognition
* Expanded task automation
* Improved human-robot interaction
