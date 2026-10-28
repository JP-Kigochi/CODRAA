# CODRAA — Collaborative Dual Robotic Arm for Assembly

## Overview

Two 6-DOF arms that coordinate to assemble a simple gearbox model.

### Actuators

|                 | Arm A            | Arm B            |
| --------------- | ---------------- | ---------------- |
| Joint actuators | Feetech STS3215  | Dynamixel AX-12A |
| Gripper         | SG90 micro-servo | SG90 micro-servo |

### Perception

- **_Xbox-One Kinect Camera_** for perception

### Software Tools

- **_ROS2 Jazzy_**
- **_Moveit_** for motion planning and collision checking
- **_Gazebo_** for simulation during development

## Repository Layout

## Build

## Roadmap

| Phase | Goal                                     | Tag    |
| ----- | ---------------------------------------- | ------ |
| 1     | Description: both arms in RViz           | v0.1.0 |
| 2     | Simulation: both arms in Gazebo          | v0.2.0 |
| 3     | MoveIt: plan and execute in sim          | v0.3.0 |
| 4     | Hardware: real arms follow trajectories  | v0.4.0 |
| 5     | Perception: Kinect in the planning scene | v0.5.0 |
| 6     | Assembly: coordinated gearbox assembly   | v1.0.0 |

## License

[Apache-2.0](LICENSE)
