AgriBot: Autonomous Agricultural Robot Simulation

An autonomous field robot simulation developed using ROS 1 (Noetic) and Gazebo. This project focuses on row-following navigation and crop health monitoring within a simulated agricultural environment.

📌 Project Overview

This project simulates an agricultural robot designed to navigate crop rows autonomously. It uses computer vision to detect plant health and provides visual indicators (Green/Red) to assist in precision farming and automated field inspection.

Key Features

 Autonomous Row Navigation: Uses sensor feedback to maintain a centered path between crop lines.
 Crop Health Monitoring: Real-time visualization of health indicators based on simulated data.
 Custom Gazebo World: A detailed agricultural environment modeled for testing navigation logic.
 Sensor Integration: Utilizes Camera and LiDAR plugins for environmental awareness and obstacle detection.

🛠️ Tech Stack

 Middleware: ROS 1 Noetic
 Simulator: Gazebo 11
 Language: Python 3
 OS: Ubuntu 20.04

🚀 Quick Start

1. Clone the repository:
```bash
cd ~/catkin_ws/src
git clone https://github.com/your-username/agribot-ros1.git

```


2. Build the workspace:
```bash
cd ~/catkin_ws
catkin_make
source devel/setup.bash

```


3. Launch the simulation:
```bash
roslaunch agribot_pkg simulation.launch

```



---

Developed for research and simulation in autonomous agricultural robotics.
