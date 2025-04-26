# tank-level-control-pi-simulation
MATLAB/Simulink project for controlling tank water level using a PI controller.
# Tank Level Control Using PI Controller in Simulink

## Project Overview
This project simulates a simple tank water level control system using a Proportional-Integral (PI) controller. 

## System Description
- Step input applied as desired tank level
- Feedback loop adjusts the inflow based on error
- Transfer function of tank: G(s) = 1 / (s + 1)
- PI controller parameters: Kp = 2, Ki = 1

## Simulation Results
The tank level smoothly reaches the setpoint with minimal overshoot, indicating effective control action.

## Files
- tank_level_control_PI.slx : Simulink model
- tank_level_scope_output.jpg : Scope output showing level response

## Created by
Safa Bazrafshan
