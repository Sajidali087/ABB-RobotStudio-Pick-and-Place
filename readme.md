# ABB RobotStudio Pick & Place Automation System

## Overview
This project simulates an industrial pick-and-place automation system developed in **ABB RobotStudio** using the **IRB1660ID robot**. The system models a real-world production environment with automated sorting, stacking, and handling of variable-sized objects using structured RAPID programming.

## Features
- Industrial pick-and-place workflow simulation
- Multi-object handling (small and large boxes)
- Defined TCPs and WorkObjects for accurate motion control
- Path generation using `MoveJ`, `MoveL`, and `Offs()` functions
- Conditional logic for object detection and routing
- Modular RAPID code with reusable procedures

## System Design
- Robot: ABB IRB1660ID  
- Programming Language: RAPID  
- Environment: ABB RobotStudio  
- WorkObjects: Defined for station-based operations  
- Tooling: Custom TCPs for gripper alignment and precision handling  

## Key Implementation Details
- Structured program flow for continuous operation
- Safe approach and retreat paths for collision avoidance
- Parametric and reusable procedures for scalability
- Realistic industrial cycle simulation with dynamic object handling

## Learning Outcomes
- Industrial robot programming using ABB RAPID
- Path planning and coordinate transformations
- Automation logic design for manufacturing systems
- Simulation-based validation of robotic workflows

## Status
Completed academic/engineering simulation project