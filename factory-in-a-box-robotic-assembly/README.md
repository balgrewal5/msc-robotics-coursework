
# Factory-in-a-Box – Automated XY Stage Assembly

**Module:** Industrial Automation and Robotics  
**University:** University of Birmingham  
**Project Type:** Collaborative MSc Project

## Project Overview

Design, simulation and optimisation of a compact automated manufacturing workcell for the assembly of motorised XY positioning stages.

The Factory-in-a-Box (FIAB) concept integrates industrial robotic manipulators, automated screwdriving, conveyor systems and packaging operations within a constrained manufacturing environment.

A hybrid double-ended robotic gripper was developed and evaluated to improve component handling flexibility and reduce assembly cycle time.

## Technologies

- RoboDK
- CAD modelling
- KUKA LBR iiwa 14 R820
- Robotiq 2F-85 gripper
- OnRobot screwdriver
- Mechanical and vacuum gripping systems

## System Features

- Three-robot automated manufacturing workcell
- Digital twin simulation
- Automated component assembly and screwdriving
- Conveyor-based material transportation
- Automated packaging and storage
- Assembly sequence optimisation
- Robot reach and payload analysis
- Multiple Tool Centre Point (TCP) configurations
- Hybrid mechanical and suction end-effector

## Hybrid End-Effector Design

The proposed end-effector combines a three-finger mechanical gripper with a vacuum suction cup, allowing different component geometries to be handled without external tool-changing operations.

Two independent TCPs were configured in RoboDK to support both gripping mechanisms.

## Simulation Results

The conventional and hybrid gripper configurations were evaluated using RoboDK.

| Performance Metric | Conventional | Hybrid | Reduction |
|---|---:|---:|---:|
| Assembly time | 232 s | 200 s | 13.8% |
| Robot motions | 34 | 28 | 17.6% |
| Travel distance | 86.81 m | 80.20 m | 7.61% |
| Empty-handed transit | 50% | 35% | 15 percentage points |

## Manufacturing Considerations

- Target production throughput of 300 units per week
- Compact workcell layout
- Lean manufacturing principles
- Assembly stability and graspability analysis
- End-effector selection
- Mechanical component and actuator sizing

## Engineering Limitations

Performance improvements were demonstrated through digital twin simulation rather than physical industrial deployment. The hybrid configuration also incorporated changes to the assembly sequence.

Further physical testing would be required to validate gripping reliability, dynamic performance and production throughput.

## Technical Documentation

The accompanying technical report documents the workcell design, engineering calculations, end-effector development, simulation methodology and comparative performance analysis.

## Skills Demonstrated

Industrial robotics, manufacturing automation, RoboDK, digital twins, CAD, robotic tooling, assembly planning and production optimisation.
