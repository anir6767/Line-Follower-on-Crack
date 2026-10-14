# Line Follower on Crack

A high-performance line-following robot developed through embedded programming, sensor integration, motor control, and PID tuning.

## Overview

Line Follower on Crack is a line-following robot project designed to achieve fast, accurate, and reliable line tracking. The project combines an ESP32-based control system, reflectance sensors, and a dual-motor driver to detect a line and adjust the robot's movement in real time.

The complete working prototype serves as the foundation for the next stage of development: designing a custom PCB to integrate the electronics into a more compact and reliable system.

## Current Features

- **ESP32-based control:** Processes sensor readings and controls the robot's movement.
- **Reflectance sensing:** Detects the line using a QTR-8RC sensor array.
- **Dual-motor drive:** Controls two DC gear motors through an L298N motor driver.
- **PID control:** Adjusts motor behaviour based on the robot's position relative to the line.
- **Modular hardware:** Uses separate electronic modules for easier testing, maintenance, and debugging.

## Hardware

| Component | Purpose |
|---|---|
| ESP32 development board | Main controller |
| QTR-8RC sensor array | Line detection |
| L298N motor driver | Motor direction and speed control |
| 2 × DC gear motors | Robot propulsion |
| Chassis and wheels | Mechanical structure |
| Battery pack | Power supply |

## Software

The firmware is written in Arduino-style C/C++ for the ESP32 platform.

Its main responsibilities include:
- Reading the reflectance sensors.
- Calculating the robot's position relative to the line.
- Applying PID-based corrections.
- Adjusting motor speed and direction.
- Keeping the robot on the line during operation.

## Development Process

The prototype development phase includes:

1. Assembling the robot chassis and electronics.
2. Establishing the sensor and motor-driver connections.
3. Developing and debugging the firmware.
4. Tuning the PID controller for line-following behaviour.
5. Testing the integrated prototype.

## Custom PCB — Next Stage

The working prototype currently uses separate modules and wiring. The next stage is to design a custom PCB that brings the electronic connections together into a cleaner, more compact layout.


## Repository Structure

```text
Line-Follower-on-Crack/
├── README.md
└── prototype/
└── pcb main/
```

Firmware, wiring documentation, test records, and PCB design files will be organised into the repository as the project documentation is expanded.

## Project Status

- [x] Prototype hardware assembly
- [x] Firmware development and debugging
- [x] PID tuning
- [x] Prototype integration
- [ ] Custom PCB schematic and layout
- [ ] PCB manufacturing and validation
- [ ] Integration and testing of the custom PCB

## Design Goals

The project focuses on modular development, reliable control, clean hardware integration, and measurable improvements in line-following performance.

The prototype establishes the working system; the custom PCB is the next step toward a more integrated robot.
