# Physics Stuff

Interactive simulations I created to help my students visualize physics concepts and develop an intuition for how physical parameters affect the behavior of a system.

Rather than treating equations as purely mathematical objects, these simulations allow students to change parameters and immediately observe the resulting changes in the system.

## Simulations

### 🌀 Magnus Effect

A numerical simulation of a spinning ball moving through air.

The simulation models:

- Gravitational force

- Air resistance

- Magnus force caused by spin

- Different launch angles and initial speeds

- Positive and negative spin

The trajectory is displayed from multiple perspectives, allowing the effect of spin to be compared directly with an otherwise identical trajectory without spin.

The simulation uses scipy.integrate.solve_ivp to numerically solve the equations of motion.

### 🪀 Oscillator with Drag

An interactive simulation of an oscillator subject to drag.

It is designed to help visualize how damping affects oscillatory motion and how changing the relevant physical parameters changes the system's behavior.

### 📦 Particle Box

A simulation of particles moving inside a box.

It can be used to visualize microscopic particle motion and connect it to macroscopic concepts such as collisions, pressure, and temperature.

## Why I Made These

These simulations were originally created as teaching tools.

In physics, it is easy to manipulate equations without developing an intuitive understanding of what they actually describe. I wanted my students to be able to experiment with the models themselves:

Change a parameter → run the simulation → observe the result → connect it back to the physics.

The goal is not to replace theoretical understanding, but to make the connection between equations and physical behavior more tangible.

## Technologies

The simulations are written in Python using:

- NumPy — numerical calculations

- Matplotlib — visualization and interactive controls

- SciPy — numerical integration and solving differential equations

## What I'm Exploring

Through these projects, I'm learning and experimenting with:

- Numerical integration

- Ordinary differential equations

- Computational modeling

- Numerical methods

- Data visualization

- Dynamical systems

- Translating physical models into code

## Future Simulations

This repository will continue to grow as I create more tools for teaching and exploring physics.

Some possible additions:

- Coupled oscillators

- Projectile motion with air resistance

- Orbital mechanics

- Wave propagation

- Electric and magnetic fields

- Heat diffusion

- Fluid dynamics

- Statistical mechanics

Note

These simulations are primarily educational models. Their purpose is to illustrate physical relationships and develop intuition, rather than to provide high-fidelity real-world predictions.
