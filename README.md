# Aircraft Shock Absorber Dynamics Simulator

A MATLAB-based numerical study on the dynamic response of aircraft landing gear shock absorbers. This project was developed as part of the Aerospace Engineering Bachelor's degree curriculum.

## Overview
This repository contains two primary scripts designed to simulate and analyze the damping characteristics of different shock absorber architectures. By solving the non-linear Ordinary Differential Equations (ODEs) governing the system, the scripts calculate the vertical displacement, velocity, and force dissipation during a landing impact.

## Features & Models
The project analyzes two distinct piston configurations:

1.  **Metering Pin Piston (`metering_pin.m`):** * Simulates a variable-orifice damping system.
    * Models the hydraulic resistance as a function of the stroke, optimized for progressive energy absorption.
2.  **Double Floating Piston (`double_floating.m`):**
    * Simulates a more complex dual-chamber architecture.
    * Analyzes the interaction between gas (pneumatic) and oil (hydraulic) stages for enhanced vibration isolation.

## Technical Approach
* **Mathematical Modeling:** The system is modeled as a mass-spring-damper system with non-linear damping coefficients.
* **Numerical Integration:** Utilizes MATLAB's ODE solvers (e.g., `ode45`) to compute the time-history of the landing gear stroke.
* **Key Parameters:** Includes initial sink rate (vertical velocity), structural mass, gas pre-charge pressure, and orifice geometry.

## Requirements
* MATLAB (R2020a or later recommended)
* Control System Toolbox (optional, depending on specific plot functions)

## How to Use
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/shock-absorber-dynamics.git](https://github.com/your-username/shock-absorber-dynamics.git)
