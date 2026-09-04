# Mine-ADAS

Modular ROS 2 + Gazebo-based ADAS platform for open-cast mining vehicles.

## Goal

Develop a modular simulation and perception system for situational awareness,
collision-risk estimation, and driver assistance in adverse mine conditions.

## Technology Stack

- Ubuntu 22.04
- ROS 2 Humble
- Gazebo Harmonic
- RViz2
- Python / C++
- Computer Vision
- LiDAR
- Radar
- Thermal Camera
- GNSS
- IMU
- Sensor Fusion

## Project Structure

```text
simulation/     Gazebo worlds, vehicles, sensors and environments
ros2/           ROS 2 perception, fusion and ADAS modules
interfaces/     ROS topics, messages and TF conventions
docs/           Architecture and engineering documentation
datasets/       Simulation and perception datasets
hardware/       Embedded hardware and ESP32 integration
tests/          Unit and integration tests

