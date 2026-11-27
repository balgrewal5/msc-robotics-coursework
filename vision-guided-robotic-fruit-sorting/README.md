
# Vision-Guided Robotic Fruit Sorting

**Module:** Applied Robotics  
**University:** University of Birmingham  
**Project Type:** Collaborative MSc Project

## Project Overview

Development and experimental validation of an autonomous fruit sorting system using a physical Quanser QArm robotic manipulator.

The system integrates deep-learning-based object detection, image-space visual servoing and automated pick-and-place operations for agricultural robotics applications.

## Technologies

- Python
- OpenCV
- YOLOv8
- NumPy
- Quanser QArm
- Quanser Hardware-in-the-Loop (HIL) API

## System Features

- Real-time fruit detection and classification
- Wrist-mounted RGB camera
- Closed-loop visual servoing
- Autonomous and manual control modes
- Joint-space waypoint calibration
- State-machine-based motion sequencing
- Fruit-specific grasping parameters
- Joint-limit protection
- Real-time heads-up display and LED feedback

## System Architecture

Camera Acquisition → YOLOv8 Detection → Visual Servoing → Motion Sequencing → HIL Interface → Robotic Manipulation

## Experimental Results

The system was validated on physical Quanser QArm hardware under controlled laboratory conditions.

| Fruit | Attempts | Sorting Success |
|---|---:|---:|
| Banana | 10 | 90% |
| Strawberry | 10 | 100% |
| Tomato | 10 | 80% |
| Overall | 30 | 90% |

Typical pick-and-place cycle time: approximately 35 seconds.

## Engineering Limitations

- Manually calibrated pick heights
- Sensitivity to lighting and training dataset quality
- Hardware jitter near workspace limits
- Slower alignment due to fixed-step visual servoing

## Technical Documentation

The project report and final presentation document the system architecture, implementation, hardware validation and experimental results.

## Skills Demonstrated

Computer vision, deep learning, robotic manipulation, feedback control, Python programming, hardware integration and experimental validation.
