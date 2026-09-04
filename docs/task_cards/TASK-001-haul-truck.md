# TASK-001 — Mining Haul Truck Simulation

## Objective

Create a realistic open-cast mining haul-truck model that can be simulated
in Gazebo Harmonic and controlled/observed through ROS 2.

## Required Vehicle Features

- Mining/off-highway haul truck
- 4 or more wheels
- Separate wheel geometry if possible
- Wheel rotation joints
- Steering mechanism
- Vehicle chassis
- Visual meshes
- Collision meshes
- Approximate real-world dimensions
- Approximate mass/inertia
- ROS 2 compatible simulation

## Preferred File Formats

Priority:

1. STEP / STP
2. STL
3. OBJ
4. DAE
5. Existing URDF/Xacro
6. Existing SDF

## Search Keywords

- open pit mining haul truck CAD model
- mining dump truck 3D CAD
- autonomous haul truck CAD
- mining truck STEP model
- mining truck URDF
- mining truck Gazebo model

## Gazebo Requirements

Target:

- Gazebo Harmonic
- SDF or URDF/Xacro
- Physics enabled
- Collision geometry
- Visual geometry
- Wheel joints
- Steering/control interface

## ROS 2 Requirements

Vehicle should eventually expose:

### Inputs

- Steering command
- Vehicle velocity command
- Brake command

### Outputs

- Vehicle odometry
- Wheel states
- TF transforms
- IMU data
- Sensor data

## Expected TF Frames

```text
base_link
├── base_footprint
├── front_left_wheel
├── front_right_wheel
├── rear_left_wheel
├── rear_right_wheel
└── sensor frames
