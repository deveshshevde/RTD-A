## Introduction of RTD-A Controller
- A novel control scheme, the **Robust setpoint Tracking Disturbance rejecting and Aggressiveness (RTD-A) controller**, is introduced as an alternative to the classical Proportional Integral Derivative (PID) controller.

## Controller Tuning Parameters
- The RTD-A controller's performance relies on four tuning parameters: `θR`, `θT`, `θD`, `θA`, each ranging from 0 to 1. Tuning of RTD-A is more transparent compared to PID controllers.

## Real-Time Implementation
- Implementation of the RTD-A controller and a Model Predictive Controller (MPC) in real-time on a **Single Input Single Output (SISO) pressure control process** using MATLAB and Simulink (with jMPC tool).

## Hardware in Loop Implementation
- Practical application includes **Hardware in Loop interfacing** with MATLAB, utilizing an Arduino microcontroller as a data acquisition unit.

## Comparative Analysis
- Performance of the RTD-A controller is compared with MPC and Proportional Integral (PI) controllers.

## Extension to MIMO Systems
- RTD-A controller is adapted for **Multi Input Multi Output (MIMO)** systems, tested in Decentralized and Decoupled Control Modes on processes like ISP reactor and Quadruple tank process.

## Adaptive Control for Non-Linear Processes
- Development of an adaptive version of the RTD-A controller for non-linear processes, such as controlling the liquid level in a conical tank.

## Use of Meta-Heuristic Algorithms
- Meta-heuristic algorithms like grey wolf optimization and genetic algorithm are employed for tuning RTD-A parameters.

## Introduction of NMGSO Algorithm
- Introduction of a new **Modified Galactic Swarm Optimization (NMGSO)** algorithm for optimal tuning of RTD-A parameters, compared with other algorithms and tuning rules.

## Simulation Tool Development
- Development of a new simulation tool with four graphical user interfaces for managing RTD-A control schemes.

## Applications and Analysis
- Demonstration of the tool on various applications like liquid level control, air pressure control, and type I diabetic process. Performance of the RTD-A controller analyzed using different optimization algorithms under deterministic and uncertain conditions.
