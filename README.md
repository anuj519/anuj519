# Anuj Arora

Robotics Engineering student at the University of Michigan focused on embedded robotics software, autonomous systems, and controls.

My experience spans physical mobile-robot autonomy, autonomous-vehicle sensor validation, open-source robotic prostheses, and embedded sensing systems. Recent work includes implementing and validating an end-to-end ROS 2 localization, mapping, and SLAM stack on a physical differential-drive robot.

## Featured work

### [Physical Mobile Robot Localization, Mapping & Navigation](https://github.com/anuj519/mbot-autonomous-navigation)

Implemented a physical ROS 2 autonomy stack spanning embedded wheel control, odometry, waypoint navigation, LiDAR mapping, Monte Carlo Localization, and SLAM.

- Tuned feedforward/PID wheel-speed control to **0.0028 m/s MAE** and implemented a C++ rotate-translate-rotate waypoint controller
- Implemented motion-compensated LiDAR processing, Bresenham/log-odds occupancy mapping, probabilistic action and sensor models, and low-variance particle filtering
- Achieved **0.026 m localization RMSE**, compared with **0.149 m for odometry alone**
- Profiled MCL at **approximately 64 ms/update with 400 particles** on a Raspberry Pi and tuned real-robot uncertainty to eliminate duplicated map geometry

### [Open-Source Leg Research](https://github.com/anuj519/open-source-leg)

Contributed to software and development infrastructure supporting the University of Michigan's Open-Source Leg, an open-source robotic prosthesis platform used to develop and test control algorithms on physical hardware.

- Implemented Python-based software improvements for research workflows
- Supported reproducible Raspberry Pi system configuration and developer onboarding
- Contributed merged [network-debugging](https://github.com/neurobionics/robot-ci/pull/44) and [SMTP setup](https://github.com/neurobionics/robot-ci/pull/42) documentation
- Collaborated through GitHub issues, pull requests, code review, and issue resolution
- Validated BOM and CAD data during a SolidWorks-to-OnShape migration

### [Fabric Game Controller](https://github.com/anuj519/fabric-game-controller)

Contributed to an embedded soft-sensing system that converts a fabric touch matrix into a responsive controller with real-time visual feedback.

- Developed Python and MicroPython components for Raspberry Pi and microcontroller hardware
- Worked with matrix scanning, serial communication, and OLED visualization
- Supported low-latency state updates for a scalable 5x5 touch interface

## Additional project

### [Autonomous Indoor Service Robot](https://github.com/anuj519/autonomous-indoor-service-robot)

Earlier independent ROS 2 simulation project exploring autonomous navigation in a custom multi-room office environment.

- Integrated TurtleBot3, Gazebo Classic, RViz2, SLAM Toolbox, AMCL, and Nav2
- Generated 2D LiDAR occupancy maps and demonstrated point-to-point autonomous navigation

## Technical toolkit

| Area | Tools |
| --- | --- |
| Languages | C, C++, Python, MATLAB |
| Robotics | ROS 2, SLAM, MCL, Nav2, AMCL, LiDAR, Gazebo, RViz2 |
| Embedded and systems | Raspberry Pi, RP2040, Linux, CAN, serial communication, Docker, Git |
| Engineering | Controls, state estimation, sensor integration, hardware-in-the-loop validation |

## Current focus

- Embedded robotics software and controls
- Physical robot localization, mapping, planning, and navigation
- Performance-conscious C++ systems integration
