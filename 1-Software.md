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

Tags: `perception 📷`

### [Test Mapping Server](https://bitbucket.org/subtchallenge/test_mapping_server)

Dockerized software interface developed by DARPA to register and report mapping-related information in the SubT Challenge. 
The Test Mapping Server accepts mapping data submissions as JSON-encoded objects representing 3D point clouds, 2D occupancy grids, telemetry, and markers in accordance with the SubT Challenge Interface Control Document (ICD). 

Tags: `perception 📷`

### [Map Analysis](https://github.com/subtchallenge/map_analysis)

Tools developed by DARPA and the CCDC Army Research Laboratory to analyze and quantify mapping performance. 
The Map Analysis package produces intrinsic and extrinsic metrics such as map coverage, deviation, and RMSE by comparing 3D point clouds and artifact reports to known ground-truth data. 

Tags: `perception 📷`

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

### [MRS UAV System](https://github.com/ctu-mrs/mrs_uav_system.git)

The MRS UAV system is developed and actively maintained by the [Multi-robot Systems Group](http://mrs.felk.cvut.cz/) at the [Czech Technical University in Prague](https://www.cvut.cz/en). The system contains both [core](https://github.com/ctu-mrs/uav_core) and [optional](https://github.com/ctu-mrs/uav_modules) ROS packages for research and verification of algorithms for UAVs both in simulation and real hardware. Our UAV [simulation package](https://github.com/ctu-mrs/simulation) based on the Gazebo simulator contains configurable models of most of the real [UAV platforms](http://mrs.felk.cvut.cz/research/micro-aerial-vehicles) used by our group including the X500 deployed in DARPA SubT.

The system follows a description presented in the article: [doi](https://doi.org/10.1007/s10846-021-01383-5), [pdf](https://link.springer.com/content/pdf/10.1007/s10846-021-01383-5.pdf).

Created by: CTU-CRAS-NORLAB

Tags: `mobility 🦵`, `autonomy 🧠`, `perception 📷`, `networking 📶`, `simulation 🖥️`

## Team CERBERUS

### [Graph-based Exploration Planner 2.0](https://github.com/ntnu-arl/gbplanner_ros)

Exploration path planning by Team CERBERUS.

Tags: `mobility 🦵`, `autonomy 🧠` 

### [Motion Primitives-based Exploration Planner](https://github.com/ntnu-arl/mbplanner_ros)

Exploration path planning by Team CERBERUS.

Tags: `mobility 🦵`, `autonomy 🧠`

### [ANYmal Rough Terrain Planner](https://github.com/leggedrobotics/art_planner)

Sampling based path planning for ANYmal based on 2.5D height maps, by Team CERBERUS.

Tags: `mobility 🦵`, `autonomy 🧠`

### [Maplab](https://github.com/ethz-asl/maplab)

Research-oriented visual-inertial mapping framework, written in C++, for creating, processing and manipulating multi-session maps by Team CERBERUS.

Tags: `perception 📷`

### [Elevation Mapping](https://github.com/leggedrobotics/elevation_mapping_cupy)

Robot-centric elevation mapping on GPU for rough terrain navigation and locomotion by Team CERBERUS.

Tags: `perception 📷`, `mobility 🦵`

### [Voxblox](https://github.com/ethz-asl/voxblox)

Voxblox is a volumetric mapping library based mainly on Truncated Signed Distance Fields (TSDFs) by Team CERBERUS.

Tags: `perception 📷`

### [ROVIO](https://github.com/ethz-asl/rovio)

Robust visual-inertial odometry framework by Team CERBERUS.

Tags: `perception 📷`

### [MAV Control](https://github.com/ethz-asl/mav_control_rw)

Model Predictive Control for flying robots by Team CERBERUS.

Tags: `mobility 🦵`
