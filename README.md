# robot_localization

Fork of [cra-ros-pkg/robot_localization](https://github.com/cra-ros-pkg/robot_localization) used by the Autonomous Robotics LLC UAV stack. It provides nonlinear state estimation (EKF / UKF) that fuses an arbitrary set of sensors.

In the swarm workspace this package is the filter that can combine IMU, GPS, and the optical velocity / pose from [ros2_vision](https://github.com/AutonomousRoboticsLLC/ros2_vision).

Upstream documentation: http://wiki.ros.org/robot_localization

## Upstream description

robot_localization is a package of nonlinear state estimation nodes. The package was developed by Charles River Analytics, Inc.

## Related repositories

- [ros2_vision](https://github.com/AutonomousRoboticsLLC/ros2_vision) — optical velocity and visual position inputs
- [ros2_driver](https://github.com/AutonomousRoboticsLLC/ros2_driver) — IMU, GPS, and other vehicle topics
- [ros2_interfaces](https://github.com/AutonomousRoboticsLLC/ros2_interfaces) — swarm message types
