---
title: "An open-source, adaptive solver for particle-resolved simulations with both subcycling and non-subcycling methods"
collection: publications
category: manuscripts
permalink: /publication/2024-iamrex-solver
excerpt: 'An open-source adaptive solver (IAMReX) for particle-resolved direct numerical simulations (PR-DNS), supporting both subcycling and non-subcycling time-integration schemes within the AMReX framework.'
date: 2024-10-01
venue: 'Physics of Fluids'
paperurl: '/files/papers/2024-iamrex-physics-of-fluids.pdf'
codeurl: 'https://github.com/hswind4/IAMReX'
doi: 'https://doi.org/10.1063/5.0236509'
bibtexurl:
citation: 'Xuzhu Li, Chun Li, Xiaokai Li, <b>Wenzhuo Li</b>, Mingze Tang, Yadong Zeng, Zhengping Zhu. &quot;An open-source, adaptive solver for particle-resolved simulations with both subcycling and non-subcycling methods.&quot; <i>Physics of Fluids</i>, 2024. DOI: 10.1063/5.0236509'
---

<div class="pub-action-links" style="margin: 10px 0 16px 0;">
  <a href="/files/papers/2024-iamrex-physics-of-fluids.pdf" class="btn btn--danger btn--small" target="_blank"><i class="fas fa-file-pdf"></i> Download PDF</a>
  <a href="https://github.com/hswind4/IAMReX" class="btn btn--inverse btn--small" target="_blank"><i class="fab fa-github"></i> IAMReX GitHub</a>
  <a href="https://doi.org/10.1063/5.0236509" class="btn btn--info btn--small" target="_blank"><i class="fas fa-external-link-alt"></i> DOI</a>
</div>

**IAMReX** is an open-source, high-performance adaptive mesh refinement (AMR) solver designed for **particle-resolved direct numerical simulations (PR-DNS)**. Built on the AMReX framework, it supports both subcycling and non-subcycling time-integration strategies, offering flexibility for a wide range of particle–fluid interaction problems.

**Contributions:**
- Contributed to code development and validation of the particle–fluid coupling module
- Implemented and tested benchmark cases for particle sedimentation and drag force validation

**Key features of IAMReX:**
- Adaptive mesh refinement (AMR) for efficient resolution of particle boundary layers
- Immersed boundary method (IBM) for no-slip enforcement
- Parallel scalability on HPC clusters via MPI + OpenMP

**Citation:** Xuzhu Li, Chun Li, Xiaokai Li, **Wenzhuo Li**, Mingze Tang, Yadong Zeng, Zhengping Zhu.  
*Physics of Fluids*, 2024. DOI: [10.1063/5.0236509](https://doi.org/10.1063/5.0236509)
