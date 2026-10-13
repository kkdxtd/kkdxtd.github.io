---
title: "Multi-Solver CFD: Dynamic Mesh & UDF Simulation of Bionic Fins"
excerpt: "Unsteady flow simulation of undulating fin propulsion using ANSYS Fluent with custom C++ UDFs for dynamic mesh generation and kinematic boundary conditions."
collection: portfolio
tags:
  - ANSYS Fluent
  - UDF
  - Dynamic Mesh
  - Bionic Propulsion
---

## Overview

As part of the comprehensive investigation into bionic undulating fin propulsion at USTC, this project established a **finite-volume CFD validation platform using ANSYS Fluent** to cross-verify against Lattice Boltzmann (Palabos) and AMR (IAMReX) simulations.

## Key Technical Work

- **Custom Kinematic UDFs:** Implemented C-based User-Defined Functions (`DEFINE_CG_MOTION` / `DEFINE_GRID_MOTION`) to accurately prescribe travelling wave undulations:
  $$y(x, t) = A(x) \sin(k x - \omega t)$$
- **Dynamic Mesh Management:** Applied spring-based smoothing and 2.5D remeshing strategies to capture high-frequency, large-amplitude fin deformation without mesh distortion or negative volume errors.
- **Unsteady Vortex Dynamics:** Captured the generation, shedding, and downstream convection of reverse Kármán vortex streets.
- **Cross-Solver Benchmark:** Provided critical benchmark data comparing finite-volume pressure-velocity coupling (PISO/SIMPLE) against kinetic LBM algorithms in terms of convergence speed and hydrodynamic force predictions.

## Status

- **Status:** Completed comparative CFD study; integrated into ongoing bionic propulsion research at USTC.
