---
title: "Global Mapping System"
excerpt: "Development of large-scale environment mapping capabilities and SLAM implementation."
collection: work-experience
permalink: /work-experience/global-mapping
date: 2021-06-01
location: "India"
project_type: "Navigation Stack Component"
header:
  teaser: /images/Occupancy-Grid-Maps.png
---

<img src="/images/Occupancy-Grid-Maps.png" alt="Global Mapping System" width="500" height="400">

## Overview
The Global Mapping system was a fundamental component of the Navigation Stack at Miko.AI, providing comprehensive environment mapping and localization capabilities.

## Technical Details

### 2D Occupancy Map Development
- Developed 2D occupancy maps from 3D local maps and robot pose estimates
- Implemented temporally dynamic mapping system with frame-based persistence
- Created n-frame verification system for object addition to global map
- Designed n-frame removal system for dynamic object handling
- Enabled adaptive map updates for movable objects like chairs and furniture
- Prevented map corruption from temporary obstacles or moved objects
