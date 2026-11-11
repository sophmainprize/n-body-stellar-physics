# N-Body Stellar Dynamics Simulation

A computational astrophysics project investigating gravitational interactions and the dynamical evolution of stellar systems using Python.

## Overview

This project aims to develop a numerical N-body simulation to investigate how gravitational interactions influence the dynamical evolution of stellar systems.

The simulation will begin with a two-body gravitational model before being extended to systems containing multiple interacting particles. Different numerical integration methods will be implemented and compared to investigate their accuracy, stability and ability to conserve physical quantities.

The broader objective is to understand how numerical methods can be used to model gravitational systems and investigate the behaviour of idealised stellar clusters.

## Research Question

**How do gravitational interactions influence the dynamical evolution of a stellar cluster, and how accurately can different numerical integration methods reproduce this evolution?**

## Project Objectives

- Implement Newtonian gravitational acceleration.
- Develop a numerical simulation of interacting bodies.
- Extend the simulation from two bodies to multiple particles.
- Investigate gravitational influence and close particle encounters.
- Implement and compare numerical integration methods.
- Generate and analyse stellar cluster initial conditions.
- Investigate energy and angular momentum conservation.
- Explore how particle number, timestep and initial conditions affect simulation results.

## Planned Development

Week 1: Initial conditions and two-body gravitational simulation
Week 2: General N-body force calculation and gravitational softening
Week 3: Comparison of Euler, RK4 and leapfrog integration
Week 4: Development of a reusable simulation engine
Week 5: Stellar cluster initial conditions and virial theorem
Week 6: Energy and angular momentum diagnostics
Week 7: Numerical experiments and parameter investigations
Week 8: Final analysis, report and project documentation


## Units and Assumptions

The initial simulation uses dimensionless units, with:

\[
G=1
\]

The initial binary system contains two equal-mass particles with:

\[
m_1=m_2=1
\]

This simplified system provides a controlled environment for testing the numerical implementation before introducing more complex stellar systems.
