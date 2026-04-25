# PendulumLab  
### Scientific Computing Project: Modeling Pendulum Dynamics with Wind and Air Resistance

## Overview

PendulumLab is a Python-based simulation project that models the motion of a pendulum under the combined effects of gravity, external wind forcing, and air resistance. The system is solved numerically using differential equation methods and analyzed through visualizations including motion plots, energy curves, phase space diagrams, and animation.

The project highlights numerical methods, mathematical modeling, data analysis, and scientific visualization using Python.

## Objectives

- Model nonlinear pendulum motion using differential equations  
- Incorporate damping through air resistance  
- Apply periodic external forcing to represent wind  
- Track kinetic, potential, and total energy over time  
- Fit an exponential decay curve to energy loss  
- Visualize system behavior through plots and animation

## Mathematical Model

The pendulum is governed by a nonlinear second-order differential equation including:

- Gravitational restoring force  
- Sinusoidal external driving force  
- Quadratic air resistance

The equation of motion is converted into a first-order system and solved numerically using `scipy.integrate.solve_ivp`.

## Tools & Libraries

- Python  
- NumPy  
- SciPy  
- Matplotlib

## Features

- Angle vs. time graph  
- Kinetic energy vs. time  
- Potential energy vs. time  
- Total energy vs. time  
- Exponential energy decay fitting  
- Phase space visualization  
- Pendulum animation  
- MP4 simulation export

## Results

The simulation demonstrates expected damped oscillatory behavior:

- Oscillation amplitude decreases over time due to drag forces  
- External forcing influences the motion pattern  
- Kinetic and potential energy exchange periodically  
- Total mechanical energy decreases because of dissipation  
- Exponential regression provides a useful approximation of energy decay  
- Phase space trajectories contract toward equilibrium over time

These outcomes are consistent with a driven damped pendulum system.

## Skills Demonstrated

- Differential equations  
- Numerical ODE solving  
- Curve fitting / regression  
- Data visualization  
- Scientific computing  
- Mathematical modeling  
- Python programming

## Future Improvements

- Interactive parameter controls  
- Solver comparisons (Euler, RK4, adaptive methods)  
- Frequency response analysis  
- Chaotic motion exploration  
- Dashboard deployment with Streamlit

## Author

Created as an independent scientific computing project focused on applied mathematics, simulation, and data analysis.
