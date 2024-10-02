# Localization-and-Mapping-using-Drones-and-Robotics
![Swarm-SLAM Overview](media/system-overview.svg)

<p align="center">
  <img src="media/graco_pg.gif" alt="Swarm-SLAM on GRACO dataset" width="48%" />
  <img src="media/graco_pc.gif" alt="Swarm-SLAM on GRACO dataset" width="48%" />
</p>

SLAM is an open-source C-SLAM system designed to be scalable, flexible, decentralized, and sparse, which are all key properties in swarm robotics. Our system supports lidar, stereo, and RGB-D sensing, and it includes a novel inter-robot loop closure prioritization technique that reduces inter-robot communication and accelerates the convergence.

Packages summary:
- [cslam](https://github.com/lajoiepy/cslam): contains the Swarm-SLAM nodes;
- [cslam_interfaces](https://github.com/lajoiepy/cslam_interfaces): contains the custom ROS 2 messages;
- [cslam_experiments](https://github.com/lajoiepy/cslam_experiments): contains examples of launch files and configurations for different setups;
- [cslam_visualization](https://github.com/lajoiepy/cslam_visualization): contains an online (optional) visualization tool to run on your base station to monitor the mapping progress.

Follow the [start-up instructions](https://lajoiepy.github.io/cslam_documentation/html/md_startup-instructions.html) to install, build and run Swarm-SLAM

A smart autonomous drone with Object Tracking and Object Detection capabilities

[**Demo of Person Tracking:**](https://github.com/Prabhdeep1999/smart-AI-autonomous-drone/tree/main/tello)

<p align="center"><img src="tello/images/README/official_attempt.gif" alt="official_attempt" width="480" height="270"/></p>

[**Demo of Custom Drone with real-time intruder detection:**](https://github.com/Prabhdeep1999/smart-AI-autonomous-drone/tree/main/custom_drone/)

<p align="center"><img src="custom_drone/images/README/first_test_flight.gif" alt="first_test_flight" width="480" height="270"/></p>


