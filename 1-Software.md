# Software

This open-source software was developed in support of the SubT Challenge by DARPA or performers.

### [SubT Virtual Testbed](https://github.com/osrf/subt)

The simulation infrastructure developed by DARPA and Open Robotics for testing robot autonomy and navigation software in complex virtual underground environments.

Tags: `simulation 🖥️`

### [Cloudsim](https://gitlab.com/ignitionrobotics/web/cloudsim)

The cloud-based simulation coordination infrastructure developed by Open Robotics to launch, run, and process simulations in the cloud.

Tags: `simulation 🖥️`

### [SubT Hello World](https://github.com/osrf/subt_hello_world)

A set of software and tutorials developed by DARPA and Open Robotics to quick start an autonomous virtual robot capable of exploring and finding artifacts.
Multiple open-source software repositories for mapping, object detection, and navigation are built into a dockerized solution.

Tags: `mobility 🦵`, `autonomy 🧠`, `perception 📷`, `networking 📶`, `simulation 🖥️`

### [Test Scoring Server](https://bitbucket.org/subtchallenge/test_scoring_server)

Dockerized software interface developed by DARPA to register and report score-related information in the SubT Challenge. 
The Test Scoring Server accepts artifact report submissions as JSON-encoded objects for each of the ten SubT Challenge artifact types in accordance with the SubT Challenge Interface Control Document (ICD). 

Tags: ``perception 📷`

### [Test Mapping Server](https://bitbucket.org/subtchallenge/test_mapping_server)

Dockerized software interface developed by DARPA to register and report mapping-related information in the SubT Challenge. 
The Test Mapping Server accepts mapping data submissions as JSON-encoded objects representing 3D point clouds, 2D occupancy grids, telemetry, and markers in accordance with the SubT Challenge Interface Control Document (ICD). 

Tags: ``perception 📷`

### [Occupancy Homogeneous Map (ohm)](https://github.com/csiro-robotics/ohm)

GPU accelerated occupancy and voxel mapping with heightmap generation for high rate lidar by Team CSIRO Data61. Supports both OpenCL and/or CUDA for generating probabilistic occupancy maps with extended models such as normal distribution transforms. Additional modules support generation of single or multi-layer heightmaps with virtual surface generation for negative obstacle avoidance.

Tags: `perception 📷`

### [Robot Body Filter](https://github.com/peci1/robot_body_filter) and its [Tutorial Using SubT Virtual Robots](https://github.com/ctu-vras/rosdevday_cloud_filtering)

Package with an advanced and highly configurable filter for pointclouds and laser scans which removes measurements on the body of the robot. It can be used both in simulation and on real robots. The tutorial ([software](https://github.com/ctu-vras/rosdevday_cloud_filtering), [video](https://www.youtube.com/watch?v=j0ljV0uZy3Q)) has been made for ROSDevDay 2021 using the CTU-CRAS-NORLAB virtual SubT robots.

Created by: CTU-CRAS-NORLAB

ROS packages:
 - `ros-melodic-robot-body-filter` / `ros-noetic-robot-body-filter`
 - `ros-melodic-sensor-filters` / `ros-noetic-sensor-filters`

Tags: `perception 📷`, `simulation 🖥️`

