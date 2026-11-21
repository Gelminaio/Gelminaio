## Pietro Gelmini

Robotics student at the University of Trento · Trento, Italy

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8%2BPC9zdmc%2B&logoColor=white)](https://www.linkedin.com/in/pietro-gelmini) [![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gelmini.pietro@gmail.com)

Control, state estimation and embedded systems on real hardware. Now building a 3D-printed SO-101 arm for robot learning.

#### Projects

<a href="https://github.com/Gelminaio/drift-mpc-ackermann"><img align="right" width="240" src="assets/drift-parking.jpg" alt="Top view: the 1:10 car parked sideways between two boxes 47 cm apart, with its measured path"/></a>

**[Autonomous drift parking](https://github.com/Gelminaio/drift-mpc-ackermann)** · 1:10 car · Apr–Oct 2026\
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)\
The car finds a parking gap with its lidar and slides into it sideways. Nonlinear MPC (acados) at 50 Hz on a Raspberry Pi 4,
a dynamic model with saturating tires identified from video, IMU and encoders, ESP32 + micro-ROS for motors and sensors,
and the same ROS 2 stack in Gazebo.\
47 cm gap for a 26 cm car · ten clean takes of the full routine · 52 unit tests in CI\
[Video](https://github.com/Gelminaio/drift-mpc-ackermann/releases/tag/phase-12) · [Technical report (PDF)](https://github.com/Gelminaio/drift-mpc-ackermann/blob/main/report/report.pdf)<br clear="right"/>

**[OS blockchain simulation](https://github.com/Gelminaio/os-blockchain-project)** · team of 3 · Apr–Sep 2026\
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)\
Nodes, miners and clients run as separate processes that share no memory: FIFOs for data, POSIX signals for control,
simulated proof-of-work, Merkle trees and SHA-256 written from scratch. Operating Systems course, graded 10/10.

#### In progress

- **SO-101 brick builder**: a 3D-printed SO-101 arm that sorts toy bricks seen by a webcam and assembles them from a
  blueprint, with inverse kinematics and imitation learning (LeRobot).
- **Pick-and-place with a UR5**: Fundamentals of Robotics course project. Block detection and pose estimation, inverse
  kinematics and trajectories in simulation, then the same pipeline on the SO-101.
- **Lidar SLAM car**: team project for the Embedded Software for the Internet of Things course, on the drift car's chassis.
  It maps a room with its lidar, localizes itself in the map (SLAM) and drives to a goal or along a path drawn on screen.

#### Open source

Small fixes merged in ros2/rclcpp ([#3145](https://github.com/ros2/rclcpp/pull/3145), [#3146](https://github.com/ros2/rclcpp/pull/3146))
and ros2/rosbag2_bag_v2 ([#52](https://github.com/ros2/rosbag2_bag_v2/pull/52)).

#### Education and experience

- **University of Trento**, BSc in Computer, Communications and Electronic Engineering · 2024–2027
- **Metalsistem S.p.A.**, Rovereto: 3D software developer intern, interactive 3D interface for industrial environments (Babylon.js) · 2023
- **ITT G. Marconi**, Rovereto: diploma in Computer Science, Big Data track, 100/100 · 2019–2024

#### Stack

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white) ![micro-ROS](https://img.shields.io/badge/micro--ROS-22314E?style=flat-square&logo=ros&logoColor=white) ![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=flat-square) ![acados](https://img.shields.io/badge/acados-4B5563?style=flat-square) ![CasADi](https://img.shields.io/badge/CasADi-4B5563?style=flat-square) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
