# Model-Based-Controller-Design-for-a-Nuclear-Plant-Inspection-Robot
Mathematical Modelling and Model-Based Controller Design for a Nuclear Plant Inspection Robot. It's a simulation of mobile inspection robot and compare two control techniques: PID and SMC. The simulation is developed using Web VPython 3.2, includes a three-dimensional plant environment, robot navigation, monitoring displays, and real-time graphs.

# Nuclear Plant Inspection Robot Using PID and Sliding Mode Control

## Overview

This project presents a 3D simulation of an autonomous inspection robot operating in a nuclear-plant-inspired environment. It combines mathematical robot modelling, waypoint-based navigation, and two control techniques—Proportional–Integral–Derivative (PID) and Sliding Mode Control (SMC)—to study robot movement and dynamic response.

Developed using **Web VPython 3.2**, the simulation visualizes the plant environment, robot navigation, environmental monitoring displays, and real-time graphs for comparing controller behaviour.

## Objectives

- Simulate an autonomous robot navigating through a nuclear plant environment.
- Implement and compare PID and Sliding Mode Control for robot motion.
- Model differential-drive robot kinematics and dynamics.
- Analyse trajectory tracking, linear and angular velocity, wheel speeds, motor torque, and acceleration.
- Visualize environmental risk information and simulated emergency scenarios.

## Features

- **3D Plant Environment:** Includes a reactor, turbine hall, pump station, cooling tower, control room, waste storage area, and restricted zones.
- **Waypoint-Based Navigation:** Guides the inspection robot through predefined patrol locations.
- **PID and SMC Controllers:** Enables controller selection for studying robot motion.
- **Robot Dynamics:** Models linear and angular motion, wheel velocities, and motor torque.
- **Real-Time Graphs:** Displays trajectory tracking, linear velocity, angular velocity, wheel angular speeds, motor torques, and dynamic response.
- **Environmental Monitoring:** Displays dataset-based radiation, temperature, pressure, water contamination, and risk information.
- **Interactive Controls:** Supports controller selection, disturbance adjustment, plant-power adjustment, pool-level setpoint changes, and simulation-speed control.
- **Emergency Scenarios:** Includes simulated anomaly conditions and response-robot behaviour.

## Technologies Used

- **Language:** Python
- **Simulation Environment:** Web VPython 3.2
- **Control Techniques:** PID Control and Sliding Mode Control
- **Modelling:** Differential-drive robot kinematics and dynamics
- **Visualisation:** 3D scene rendering and real-time graphs

## Simulation Parameters

| Parameter | Value |
|---|---:|
| Robot mass | 50 kg |
| Rotational inertia | 12 kg·m² |
| Wheel radius | 0.5 m |
| Track width | 2.4 m |
| Maximum linear velocity | 0.75 m/s |
| Maximum angular velocity | 1.25 rad/s |
| Motor torque limit | ±45 N·m |

## Graphs and Analysis

The simulation generates graphs to analyse the behaviour of both controllers:

1. **Trajectory Tracking:** Compares the desired patrol path with the actual robot trajectory.
2. **Linear Velocity Tracking:** Compares reference and actual forward velocity.
3. **Angular Velocity Tracking:** Examines the robot's turning response.
4. **Wheel Angular Speeds:** Displays the left and right wheel-group speeds.
5. **Motor Torques:** Shows the torque applied to the left and right wheel groups.
6. **Dynamic Response:** Displays linear and angular acceleration.
7. **Spent-Fuel-Pool Dynamics:** Shows pool level, scaled temperature, and the target level.

These plots support a qualitative comparison of tracking performance and control effort. Numerical performance claims should be based on verified simulation data.

## How to Run

1. Clone or download this repository.
2. Open the Python simulation file.
3. Copy the code into a compatible Web VPython environment, such as [GlowScript](https://glowscript.org/).
4. Run the simulation in the browser.
5. Use the available controls to select PID or SMC, adjust disturbances, and explore the simulation scenarios.
6. Observe the robot's movement and the generated graphs.

**Note:** The code uses Web VPython-specific features, so it may require adaptation before it can run directly in a standard local Python environment.

## Project Scope and Limitations

This is a simulation-based project intended for educational and research purposes. The environmental readings are obtained from an embedded dataset and do not represent live measurements from a physical nuclear facility. The simulated anomaly and emergency-response scenarios do not control real equipment.

A complete numerical comparison of PID and SMC requires recorded simulation runs and verified calculations of the relevant performance metrics.

## Future Enhancements

- Automated calculation of controller performance metrics.
- Repeated trials under matched operating conditions.
- Improved obstacle avoidance and route planning.
- More comprehensive disturbance and anomaly testing.
- Integration with physical robot hardware or hardware-in-the-loop simulation.

## Authors

- B. Vaasita
- K. Nikshitha
- S. Khyathisree
  

## Disclaimer

This project is an academic simulation and is not intended for deployment in an actual nuclear facility or use in safety-critical operations.
