# PendulumLab  
### Scientific Computing Project: Modeling Pendulum Dynamics with Wind and Air Resistance

## Overview

PendulumLab is a Python-based simulation project that models the motion of a pendulum under the combined effects of gravity, external wind forcing, and air resistance. The system is solved numerically using differential equation methods and analyzed through visualizations including motion plots, energy curves, phase space diagrams, and animation.

The project highlights numerical methods, mathematical modeling, data analysis, and scientific visualization using Python.

<details>
<summary>📊 View Project Presentation</summary>
<br>

📄 [View presentation (PDF)](https://github.com/kwhite3754/pendulum-lab/blob/main/presentations/Pendulum%20Simulation%20-%20Wind%20and%20Air%20Resistance.pdf)

</details>

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

## Visual Analysis 

<p align="center">
    <img width="370" height="290" src="https://github.com/kwhite3754/pendulum-lab/blob/main/outputs/Pendulum%20with%20Wind%20and%20Air%20Resistance.png" hspace=10>
    <img width="370" height="290" src="https://github.com/kwhite3754/pendulum-lab/blob/main/outputs/Kinetic%20Energy%20vs.%20Time.png" hspace=10>
</p>
<p align="center">
  <img width="370" height="290" src="https://github.com/kwhite3754/pendulum-lab/blob/main/outputs/Potential%20Energy%20vs.%20Time.png" hspace=10>
  <img width="370" height="290" src="https://github.com/kwhite3754/pendulum-lab/blob/main/outputs/Comparing%20Kinetic%20and%20Potential%20Energy.png" hspace=10>
</p>
<p align="center">
  <img width="370" height="290" src="https://github.com/kwhite3754/pendulum-lab/blob/main/outputs/Total%20Energy%20vs.%20Time.png" hspace=10>
  <img width="370" height="290" src="https://github.com/kwhite3754/pendulum-lab/blob/main/outputs/Energy%20Decay%20with%20Fitted%20Curve.png" hspace=10>
</p>
<p align="center">
  <img width="370" height="290" src="https://github.com/kwhite3754/pendulum-lab/blob/main/outputs/Comparing%20the%20Angular%20Velocity%20with%20Angles.png" hspace=10>
<img width="370" height="290" src="https://github.com/kwhite3754/pendulum-lab/blob/main/outputs/pendulum.gif" hspace=10>

</p>

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
