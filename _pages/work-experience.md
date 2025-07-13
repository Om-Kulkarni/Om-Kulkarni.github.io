---
layout: archive
title: "Work Experience"
permalink: /work-experience/
author_profile: true
---

## Robotics Developer at Miko.AI
*2021 - 2023*

During my two-year tenure at Miko.AI, I played a key role in developing the company's autonomous navigation capabilities. My primary focus was on designing and implementing a comprehensive Navigation Stack that enhanced the robot's ability to understand and navigate through complex environments.

### Navigation Stack Project
The Navigation Stack was a comprehensive solution that enabled autonomous navigation through integration of mapping and planning systems at both global and local levels. This modular architecture allowed for robust and efficient navigation in diverse environments.

### Project Components

### 1. [Global Planning](/work-experience/global-planning)
<img src="/images/astar_graph.png" alt="Global Planning" width="400" height="300">

Led the development of high-level path planning algorithms, implementing efficient pathfinding solutions using A* and D* algorithms, with dynamic route recalculation capabilities.
[Read more...](/work-experience/global-planning)

### 2. [Local Planning](/work-experience/local-planning)
<img src="/images/dwa_planner.png" alt="Local Planning" width="400" height="300">

Designed and implemented reactive path planning systems for immediate obstacle avoidance, featuring Dynamic Window Approach (DWA) and other collision prediction systems.
[Read more...](/work-experience/local-planning)

### 3. [Global Mapping](/work-experience/global-mapping)
<img src="/images/Occupancy-Grid-Maps.png" alt="Global Mapping" width="400" height="300">

Developed comprehensive global mapping capabilities, with map merging functionalities. Created 2D occupancy maps from 3D local maps with temporally dynamic features, requiring n-frame verification for object persistence and removal, allowing objects to be repositioned without permanently affecting the global map.
[Read more...](/work-experience/global-mapping)

### 4. [Local Mapping](/work-experience/local-mapping)
<img src="/images/local mapping.png" alt="Local Mapping" width="400" height="300">

Created real-time local environment mapping system using cyclic buffer of 3D voxels with three specialized buffers: free voxels, occupied voxels, and distance transform voxels. This modified octomap structure enabled efficient real-time updates and supported DWA planning through closest obstacle tracking.
[Read more...](/work-experience/local-mapping)
