---
title: "IAMReX: Open-Source Adaptive Solver for Particle-Resolved DNS"
excerpt: "Contributed to the development of IAMReX, an open-source high-performance solver for particle-resolved direct numerical simulations with adaptive mesh refinement."
collection: portfolio
puburl: '/publication/2024-iamrex-solver'
paperurl: '/files/papers/2024-iamrex-physics-of-fluids.pdf'
codeurl: 'https://github.com/hswind4/IAMReX'
---

<div class="project-action-links" style="margin: 12px 0 20px 0; display: flex; flex-wrap: wrap; gap: 8px;">
  <a href="/publication/2024-iamrex-solver" class="btn btn--primary btn--small"><i class="fas fa-book-open"></i> Associated Paper: Physics of Fluids (2024)</a>
  <a href="/files/papers/2024-iamrex-physics-of-fluids.pdf" class="btn btn--danger btn--small" target="_blank"><i class="fas fa-file-pdf"></i> Download PDF</a>
  <a href="https://github.com/hswind4/IAMReX" class="btn btn--inverse btn--small" target="_blank"><i class="fab fa-github"></i> IAMReX GitHub</a>
</div>

## Overview

[IAMReX](https://github.com/hswind4/IAMReX) is an open-source, high-performance solver for **particle-resolved direct numerical simulations (PR-DNS)** of particle–fluid systems. It is built on the AMReX (Adaptive Mesh Refinement) framework and supports both subcycling and non-subcycling time-integration strategies.

I contributed to this project as a collaborator, focusing on code development, module validation, and benchmark testing.

## Technical Details

**Core Framework:** AMReX (C++/Fortran, developed by LBNL)  
**Physical Model:** Incompressible Navier-Stokes + Immersed Boundary Method (IBM)  
**Parallelism:** MPI + OpenMP hybrid parallelization  

**My Contributions:**
- Developed and tested the particle–fluid coupling module using IBM no-slip boundary enforcement
- Validated solver performance against benchmark cases (Stokes drag, sedimentation in quiescent fluid)
- Assisted in implementing adaptive mesh refinement strategies near particle surfaces

## Key Features of IAMReX

- **Adaptive Mesh Refinement (AMR):** Dynamically refines mesh near particles for accurate boundary layer resolution
- **Dual Time-Integration:** Supports both subcycling (different time steps for fluid and particles) and non-subcycling methods
- **Scalability:** Tested on HPC clusters with thousands of CPU cores
- **Open-Source:** Available on GitHub under permissive license

## Publication

The solver is described in detail in the paper published in *Physics of Fluids* (2024):

> Xuzhu Li, Chun Li, Xiaokai Li, **Wenzhuo Li**, Mingze Tang, Yadong Zeng, Zhengping Zhu.  
> "An open-source, adaptive solver for particle-resolved simulations with both subcycling and non-subcycling methods."  
> *Physics of Fluids*, 2024. DOI: [10.1063/5.0236509](https://doi.org/10.1063/5.0236509)
