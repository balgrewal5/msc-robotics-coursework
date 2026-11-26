
# Intelligent Book Retrieval Robot

**Module:** Intelligent Robotics  
**University:** University of Birmingham  
**Project Type:** Collaborative MSc Project

## Project Overview

Development of an autonomous book retrieval robot using a KUKA youBot mobile manipulator within the Webots simulation environment.

The project integrates odometry, localisation, LiDAR-based occupancy mapping and robotic manipulation to support automated book retrieval in a library environment.

## Technologies

- Python
- Webots
- KUKA youBot
- LiDAR
- Wheel encoders
- Mecanum wheel kinematics

## System Features

- Encoder-based robot pose estimation
- LiDAR-based occupancy grid mapping
- Omnidirectional locomotion
- Coordinate transformations
- Robotic arm manipulation
- State-machine-based retrieval sequence

## My Contributions

- Research and evaluation of robotic localisation methods.
- Mathematical formulation of differential-drive odometry.
- Implementation of encoder-based position and orientation estimation.
- Odometry validation using GPS and IMU ground-truth measurements.
- Analysis of accumulated drift and modelling limitations.

A simplified differential-drive odometry model was adopted for the experimental evaluation, despite the robot's omnidirectional Mecanum wheel configuration.

## Experimental Results

A 3-metre straight-line test and a 1 × 1 metre square-path experiment were used to evaluate odometry accuracy.

| Performance Metric | Result |
|---|---|
| Square-path position error | 1.3 cm |
| Orientation drift | 1.2 degrees |

## Original Project Repository

[View source code and Webots simulation](https://github.com/Yamadalv1/Book-robot)

## Technical Report

The accompanying academic report documents the research, mathematical formulation, implementation methodology and experimental evaluation.

## Skills Demonstrated

Mobile robotics, odometry, localisation, mathematical modelling, Python programming, robotic simulation and experimental validation.
