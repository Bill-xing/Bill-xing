<h1 align="center">Jianming Xing / 邢鉴明</h1>

<h3 align="center">Embodied AI · Robotics Software · ROS2 · VLA/OpenPI</h3>

<p align="center">
  <a href="https://bill-xing.github.io">Personal Website</a> ·
  <a href="https://bill-xing.github.io/assets/pdf/Xingjianming_s_CV.pdf">English CV</a> ·
  <a href="https://bill-xing.github.io/assets/pdf/CV_%E9%82%A2%E9%89%B4%E6%98%8E.pdf">中文简历</a> ·
  <a href="mailto:bill.xjm@gmail.com">Email</a>
</p>

## About

I am pursuing a second bachelor's degree in **Computer Science and Technology** at **Harbin Institute of Technology, Shenzhen**. I received my B.Eng. in **Mechanical Design, Manufacturing and Automation** from **Harbin Institute of Technology, Weihai**.

My work focuses on **embodied AI and robotics software**, especially real-robot VLA/OpenPI adaptation, ROS2 systems, robot data collection, computer vision, and desktop HMIs for robot control and visualization. I am interested in learning-based manipulation systems that move cleanly from data collection to safe real-machine deployment.

我目前关注具身智能与机器人软件工程，希望把学习型机器人操作系统从数据采集、模型适配推进到可验证的真机部署。

## Current Focus

- Real-robot VLA/OpenPI pipelines: teleoperation, synchronized data recording, LeRobot dataset conversion, policy serving, and robot-side inference.
- ROS2 robot systems: camera/robot/gripper integration, time alignment, safety checks, and deployment tooling.
- Robot vision and HMIs: segmentation models, C++/Qt control interfaces, OpenGL digital twins, and robotics visualization.
- Reinforcement-learning environments: Isaac Lab task migration, MuJoCo terrain queries, reward design, and regression checks.

## Featured Work

| Project | What I built | Stack |
| --- | --- | --- |
| [VLA/OpenPI Real-Robot Data Collection and Inference Loop for CR5](https://bill-xing.github.io/projects/cr5-vla-openpi/) | Built a real-robot closed loop for Dobot CR5, Orbbec Astra2 RGB-D, and an electric gripper. The pipeline covers eye-to-hand calibration, teleoperation recording, HDF5 synchronization, LeRobot v2.0 conversion, OpenPI fine-tuning, WebSocket policy serving, and CR5 inference deployment. | ROS2 Humble, Dobot CR5, LeRobot v2.0, OpenPI, HDF5 |
| [Robot Digital-Twin HMI for Weld-Seam Recognition](https://bill-xing.github.io/projects/robot-welding-system/) | Built a robotics software stack for weld-seam segmentation, Qt-based control, and OpenGL digital-twin visualization. Improved weld-seam segmentation accuracy from 64% to 96.8% through transfer learning, data augmentation, and dataset expansion. | C++/Qt, PyTorch, U-Net, OpenGL, MATLAB |
| [MotrixLab ANYmal-C Navigation Migration](https://github.com/Bill-xing/MotrixLab) | Migrated Isaac Lab's ANYmal-C navigation task to a MotrixLab NumPy environment, including reset/step logic, command sampling, observation assembly, reward calculation, termination checks, terrain height/slope queries, and rollout/regression tests. | MuJoCo, Isaac Lab, NumPy, RL |

## Selected Repositories

- [openpicr5](https://github.com/Bill-xing/openpicr5): CR5 VLA/OpenPI adaptation, data collection, dataset conversion, and inference client.
- [HMI](https://github.com/Bill-xing/HMI): C++/Qt robot upper-computer system for weld-seam recognition and digital-twin visualization.
- [DOBOT_6Axis_ROS2_V3](https://github.com/Bill-xing/DOBOT_6Axis_ROS2_V3): ROS2 integration work around Dobot 6-axis robot control.
- [ros2_ws_xing](https://github.com/Bill-xing/ros2_ws_xing): ROS2 workspace for camera/robot recording and synchronization experiments.
- [MotrixLab](https://github.com/Bill-xing/MotrixLab): MotrixLab/Isaac Lab migration work for quadruped navigation and RL environments.

## Experience

- **Xbotics Embodied AI Community Internship** (2025.10 - 2026.01): MotrixLab, Isaac Lab, quadruped robotics, and reinforcement learning.
- **HIT Weihai HERO Robomaster Team, Vision Group** (2023.09 - 2024.02): ROS2 vision-framework migration, host-MCU communication, and time synchronization.

## Toolbox

| Area | Tools |
| --- | --- |
| Programming | C/C++, Python, MATLAB |
| Robotics and Vision | ROS/ROS2, OpenCV, PyTorch, robot kinematics, Gazebo |
| Interfaces and Visualization | Qt, OpenGL, desktop robot HMIs, digital twins |
| Engineering | Git, CMake, data validation, regression tests |
| Language | TOEFL 93, CET-4, CET-6 |
