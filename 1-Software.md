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

MRS UAV system is developed and actively maintained by the [Multi-robot Systems Group](http://mrs.felk.cvut.cz/) at the [Czech Technical University in Prague](https://www.cvut.cz/en).
The system contains both [core](https://github.com/ctu-mrs/uav_core) and [optional](https://github.com/ctu-mrs/uav_modules) ROS packages for research and verification of algorithms for UAVs both in simulation and real hardware:
 - [UAV controllers](https://github.com/ctu-mrs/mrs_uav_controllers) (SE(3) geometric state feedback, model predictive control, failsafe controller)
 - [Trajectory trackers](https://github.com/ctu-mrs/mrs_uav_trackers) for generating feasible all-state reference from a sequence of position setpoints
 - [Trajectory generation](https://github.com/ctu-mrs/mrs_uav_trajectory_generation) for generating time-parametrized trajectory out of a sequence of waypoints
 - [State estimation](https://github.com/ctu-mrs/mrs_uav_odometry) for estimating the state of the UAV by fusion of onboard sensors measurements
 - [Library](https://github.com/ctu-mrs/mrs_lib) of useful wrapper classes adding additional functionality to standard ROS interface
 - and much more

Our UAV [simulation package](https://github.com/ctu-mrs/simulation) based on the Gazebo simulator contains configurable models of most of the real [UAV platforms](http://mrs.felk.cvut.cz/research/micro-aerial-vehicles) used by our group including the X500 deployed in both system and virtual track finals of DARPA SubT by our team CTU-CRAS-NORLAB. The sensor payload can be easily customized by arguments and includes most often used sensors such as Ouster and Velodyne LiDARs, Realsense RGBD cameras, 2D LiDARs, RGB cameras, etc.

Most of the software is well documented at https://ctu-mrs.github.io/.

The system follows a description presented in the article: [doi](https://doi.org/10.1007/s10846-021-01383-5), [pdf](https://link.springer.com/content/pdf/10.1007/s10846-021-01383-5.pdf).

Created by: CTU-CRAS-NORLAB

Tags: `mobility 🦵`, `autonomy 🧠`, `perception 📷`, `networking 📶`, `simulation 🖥️`
