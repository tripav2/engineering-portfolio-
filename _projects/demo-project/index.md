---
layout: post
title: 3D Spatial Mapping Scanner 
description: Built a 360° spatial scanning system using the VL53L1X Time-of-Flight sensor mounted on a stepper motor, integrated with a TM4C1294 microcontroller. The system collects distance data at 11.25° intervals via I2C, then transmits angle-distance pairs over UART to a Python application for real-time 2D and 3D point cloud rendering using Open3D. Designed custom firmware in C to coordinate motor control, sensor resets, and LED indicators, while the PC-side Python script handles serial parsing, coordinate transformation, and visualization. This low-cost, portable scanner enables accurate indoor environment mapping and accessibility analysis.
skills: 
  - Microcontroller Programming (TM4C1294 / ARM Cortex-M4F)
  - Embedded Systems Design
  - C/C++ Programming
  - Python Programming
  - UART Serial Communication
  - I2C Protocol
  - Stepper Motor Control
  - Sensor Integration (VL53L1X ToF Sensor)
  - Open3D Point Cloud Visualization
  - Real-Time Data Processing
  - Hardware-Software Integration
  - PCB/Circuit Schematic Understanding
  - System Optimization (Bus Speed, Timing)


main-image: /project2.jpg
---

---




