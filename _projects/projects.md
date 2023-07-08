---
layout: archive
title: "Projects"
collection: projects
permalink: /projects/
author_profile: true
---

{% include base_path %}

## Robotics and Autonomous Systems Projects

This repository showcases a collection of robotics and autonomous systems projects that I have worked on. Each project demonstrates my expertise in various areas of robotics, including SLAM, autonomous navigation, trajectory tracking, and motion planning.

### [Particle Filter SLAM](https://github.com/suryapilla/Particle-Filter-SLAM)  
- Developed a Particle Filter algorithm for indoor localization and mapping of a differential-drive robot.  
Utilized LiDAR data to generate a probabilistic occupancy grid of an unknown environment.

<div style="display: flex; justify-content: center;">
  <img src="../gifs/OccupancyGrid_data21.gif" width="400" alt="Rubik's Cube 1" style="margin-right: 20px;">
  <img src="../gifs/TextureMap_data21.gif" width="400" alt="Rubik's Cube 2">
</div>

### [Visual Inertial SLAM](https://github.com/suryapilla/VISLAM)
- Implemented Visual Inertial SLAM (VI SLAM) using an Extended Kalman Filter approach.
- Fused sensor measurements from gyroscope, accelerometer, and camera to track the 3D pose of the robot and create a landmark map.
<div style="display: flex; justify-content: center;">
  <img src="../images/Traj_10.png" width="400" alt="Traj" style="margin-right: 20px;">
  <img src="../images/Traj_feat_10.png" width="400" alt="Traj and features">
</div>

### [Autonomous Navigation](https://github.com/suryapilla/Autonomous-Navigation)
- Designed and implemented a dynamic programming algorithm for deterministic shortest path planning.
- Optimized control actions to find the shortest path from a starting point to a key location while avoiding obstacles.

<div style="display: flex; justify-content: center;">
  <img src="../gifs/doorkey_rand_8-10.gif" width="400" alt="NAvig 1" style="margin-right: 20px;">
  <img src="../gifs/doorkey_rand_8-36.gif" width="400" alt="Navig 2">
</div>

### [Trajectory Tracking](https://github.com/suryapilla/Trajectory-Tracking.git)
- Solved a non-linear optimization problem using Python CasADi solver.
- Developed an optimal control policy for accurate trajectory tracking.
- Compared the performance of Receding-Horizon Certainty Equivalent Control and Generalized Policy Iteration techniques.

<div style="display: flex; justify-content: center;">
  <img src="../gifs/2_5_10.gif" width="400" alt="Tracking 1" style="margin-right: 20px;">
  <img src="../gifs/20_5_10_50T.gif" width="400" alt="Tracking 2">
</div>

### [Motion Planning](https://github.com/suryapilla/motion-planning.git)
- Compared search-based (A*) and sampling-based (RRT) algorithms in a continuous 3D environment.
- Evaluated their efficiency and effectiveness for generating collision-free paths.
<div style="display: flex; justify-content: center;">
  <img src="../images/maze_astar.png" width="400" alt="A *" style="margin-right: 20px;">
  <img src="../images/maze_rrt.png" width="400" alt="RRT">
</div>
<br>
<div style="display: flex; justify-content: center;">
  <img src="../images/window_astar.png" width="400" alt="A *" style="margin-right: 20px;">
  <img src="../images/window_rrt.png" width="400" alt="RRT">
</div>

### [Image segmentation for Carla Dataset](../files/segmentation.pdf)
- Trained a PyTorch-based UNet architecture with attention and the Deeplabv3 with Resnet 101
backbone architecture to perform semantic segmentation for road object detection on a pixel level achiving accuracy of 91 and 82 respectively.

These projects demonstrate my proficiency in robotics algorithms, sensor fusion, path planning, and control optimization. Each project represents my ability to apply theoretical concepts to practical robotics challenges.
