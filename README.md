# 3-DOF Bomb-Defusal Robotic Arm

## Overview
This project presents a remotely operated robotic arm designed for hazardous environments such as bomb defusal. The system minimizes human interaction with dangerous objects by enabling remote manipulation and wire-cutting operations.

## Objective
To design and develop a remotely controlled low-cost robotic arm capable of performing precise manipulation tasks in hazardous environments.

Designing a robotic arm requires coordination between mechanical structure, actuator control, and embedded system programming. The goal was to create a functional robotic prototype capable of smooth and controlled motion.

## Working Principle
- Live camera feed provides visual feedback to the user  
- User sends control commands remotely  
- Robotic arm aligns to the required position  
- End-effector performs manipulation (e.g., wire cutting)

## System Overview
- Remote operator (safe zone)
- Robotic arm (hazardous zone)
- Camera module for live video feedback
- Control interface for actuation

## System Architecture
- Mechanical arm designed using SolidWorks
- Servo motor-based joint actuation
- Arduino-based embedded control
- Raspberry Pi for video feedback and monitoring

## Tech Stack
- SolidWorks
- Arduino
- Raspberry Pi

## Implementation
- Designed the arm structure and joint mechanisms
- Developed embedded control logic for servo actuation
- Integrated motor control for coordinated movement
- Added camera-based visual feedback using Raspberry Pi

## Results
- Smooth multi-axis motion control
- Successful hardware-software integration
- Functional robotic arm prototype for basic manipulation tasks

## Future Work
- Inverse kinematics implementation
- Improved precision and payload handling
- Autonomous object pick-and-place capability

