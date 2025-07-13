---
title: "Local Mapping System"
excerpt: "Development of real-time local environment mapping and obstacle detection systems."
collection: work-experience
permalink: /work-experience/local-mapping
date: 2021-06-01
location: "India"
project_type: "Navigation Stack Component"
header:
  teaser: /images/local mapping.png
---

<img src="/images/local mapping.png" alt="Local Mapping System" width="500" height="400">

## Overview
The Local Mapping system provided critical real-time environment perception capabilities for the Navigation Stack at Miko.AI, enabling immediate awareness of the robot's surroundings.

## Technical Details

### Cyclic Buffer 3D Voxel System
- Implemented cyclic buffer of 3D voxels for efficient real-time mapping
- Maintained three specialized buffer types for comprehensive spatial representation
- Designed system to avoid recalculation at each timestep through cyclic updates
- Created modified octomaps optimized for dynamic local mapping

### Voxel Buffer Types
- **Free Voxels**: Tracked confirmed free space around the robot
- **Occupied Voxels**: Mapped occupied space and obstacles in the environment
- **Distance Transform Voxels**: Maintained closest obstacle distances for each 3D space point
- Integrated distance transform data with DWA planning for collision avoidance

### Sensor Fusion
- Implemented sensor fusion algorithms for combining pointcloud data with robot pose estimate
- Developed multi-sensor calibration systems
- Designed real-time sensor data processing pipeline

### System Integration
- Designed interfaces with local planning system
- Implemented real-time data sharing with global mapping
- Created performance monitoring tools

