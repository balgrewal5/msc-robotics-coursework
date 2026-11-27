
# Quanser Aero 2 – PID and LQR Control

**Module:** Advanced Project (MSc Dissertation)  
**University:** University of Birmingham  
**Project Type:** Individual Research Project  
**Supervisor:** Roger Dixon

## Research Title

Control Design and Predictive Evaluation of a Coupled Quanser Aero 2 System

## Project Overview

Mathematical modelling, controller design and predictive evaluation of a coupled two-degree-of-freedom dual-rotor aerospace system.

The research investigates how accurately a reduced-order mathematical model predicts closed-loop controller performance in the higher-fidelity QLabs Virtual Aero 2 environment.

## Technologies

- MATLAB
- Simulink
- Quanser QLabs Virtual Aero 2
- QUARC
- MATLAB Control System Toolbox

## Methodology

- Newton–Euler derivation of coupled pitch and yaw dynamics
- Four-state MIMO state-space modelling
- Independent PID controller design and tuning
- Full-state Linear Quadratic Regulator (LQR) design
- Bryson-style Q and R weighting selection
- Equilibrium-voltage estimation and calibration
- Controller implementation in QLabs
- Comparative performance analysis under voltage constraints

## Experimental Results

Both controllers were evaluated using simultaneous 10-degree pitch and yaw reference commands.

### LQR Equilibrium-Voltage Calibration

| Metric | Initial QLabs | Calibrated QLabs |
|---|---:|---:|
| Pitch tracking error | 1.00° | 0.22° |
| Yaw tracking error | 1.65° | 0.05° |
| Pitch rise time | 3.12 s | 1.99 s |
| Yaw rise time | Not reached | 2.52 s |

Calibration reduced final-window pitch and yaw tracking errors by approximately 78% and 97%, respectively, without modifying the LQR feedback gain.

## Key Research Findings

- Reduced-order mathematical models can provide effective stabilising feedback without accurately predicting detailed system behaviour.
- PID gains required platform-specific retuning.
- LQR feedback gains transferred without retuning, but equilibrium voltages required empirical calibration.
- Model accuracy, actuator saturation and controller implementation influence closed-loop performance.

## Research Limitations

- Validation conducted in QLabs rather than on physical hardware.
- Calibration evaluated at a single principal operating point.
- Unequal controller recording durations.
- No repeated-trial statistical analysis.

## Technical Documentation

The accompanying dissertation provides the mathematical derivations, controller designs, state-space matrices, experimental graphs, results and critical evaluation.

## Skills Demonstrated

System dynamics, mathematical modelling, MIMO control, PID, optimal control, LQR, state-space analysis, MATLAB, Simulink and quantitative model validation.
