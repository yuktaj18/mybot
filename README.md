# MyBot : Differential Drive Robot Simulation using ROS2 Jazzy

A ROS2 Jazzy project that demonstrates the complete workflow of developing a **2-wheeled differential drive mobile robot** from scratch. The robot is modeled using **URDF**, simulated in **Gazebo Sim (GZ Sim)**, visualized in **RViz2**, mapped using **SLAM Toolbox**, and navigated autonomously using the **Nav2 Stack**.
I have followed the tutorial series by **articulated robotics** on youtube, https://articulatedrobotics.xyz/category/build-a-mobile-robot-with-ros.

---

## 🛠 Technologies Used

- ROS2 Jazzy
- Gazebo Sim (GZ Sim)
- RViz2
- URDF/Xacro
- SLAM Toolbox
- Nav2 Stack
- Robot State Publisher
- ros_gz_bridge
- ros_gz_sim
---

## Workflow

### 1. Robot Modeling

- Designed the robot using URDF/Xacro
- Defined links, joints, inertial, visual, and collision properties

The robot consists of:

- Differential drive base
- Two driven wheels
- Caster wheel
- LiDAR sensor
- Robot links and joints


### 2. Simulation

- Spawned the robot in Gazebo Sim
- Simulated differential drive motion

### 3. Visualization

- Visualized the robot model in RViz2
- Displayed TF frames, LaserScan, Odometry, and Map

### 4. Mapping

- Used SLAM Toolbox to generate a 2D occupancy grid map
- Saved the generated map for future navigation

### 5. Autonomous Navigation

- Loaded the saved map
- Localized the robot using AMCL
- Planned paths with Nav2
- Navigated autonomously to user-defined goals

---

## Key Takeaways
- Learnt how to create a robot model for simulation using urdf.
- Understood implementation of launch files to include different nodes
- Created simple world in gzsim and how robot is visualized in rviz2
- Creating configuration files

---
## Video


