---
title: "Plastic and Paper Segregation Robot - LeRobot Global Hackathon 2025"
excerpt: "Technical Experts Award & 2nd Place Winner at Hugging Face LeRobot Global Hackathon - London 2025<br/><img src='/images/me_with_so101.jpeg' width='500' height='500'>"
collection: projects
date: 2025-06-15
---

### Project Resources
* **Code Repository**: [LeRobot Implementation](https://github.com/snknitheesh/lerobot)
* **Dataset**: [Sort Boxes Conveyor Dataset v1](https://huggingface.co/datasets/OmKulkarni/sort_boxes_conveyor_v1)

This project, developed during the Hugging Face LeRobot Global Hackathon 2025 in London, secured the Technical Experts Award and 2nd place overall. As Team Episode-124 (named after our 124 collected data episodes), we tackled the critical challenge of automated waste segregation, specifically focusing on separating paper from mixed plastic-paper waste on a moving conveyor belt.

### Key Achievements
* Won Technical Experts Award at LeRobot Global Hackathon 2025
* Secured 2nd Place in London competition
* Successfully implemented real-time waste segregation on moving conveyor
* Developed during an intensive 2-day deep-tech sprint

### Technical Implementation

* **Vision System**: Implemented dual-camera setup (top and front views) for comprehensive object detection
* **Robot Control**: Utilized SO101 robot arm with fine-tuned GROOTN1.5 VLA model
* **Dynamic Prediction**: Developed algorithms to predict object positions during conveyor movement for precise grasping
* **Data Collection**: Created comprehensive dataset using leader-follower setup
  * 124 training episodes
  * Integrated camera feeds with robot joint angles
  * Real-time position tracking and prediction

### Technical Evolution
* Initial Approach: Tested ACT model from scratch
* Intermediate Step: Experimented with fine-tuning smolVLA (faced prediction challenges)
* Final Solution: Successfully implemented fine-tuned GROOTN1.5 VLA model
  * Superior performance in dynamic object tracking
  * Accurate prediction of object positions during conveyor movement
  * Robust grasping strategy implementation

### Technologies Used
* SO101 Robot Arm
* GROOTN1.5 VLA (Vision-Language-Action) model
* Dual Camera Vision System
* Leader-Follower Training Setup
* Advanced Motion Prediction Algorithms
* Real-time Control Systems

### Team Members
* Om Kulkarni
* Nitheesh Kumar Senthilnathan
* Pranav Naik
* Prahalad Vijaykumar
