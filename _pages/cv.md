---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-bar" style="display: flex; flex-wrap: wrap; gap: 8px; margin: 15px 0 25px 0;">
  <a href="{{ base_path }}/files/cv-english.pdf" class="btn btn--primary" target="_blank"><i class="fas fa-file-pdf"></i> Download CV (English)</a>
  <a href="{{ base_path }}/files/cv-chinese.pdf" class="btn btn--info" target="_blank"><i class="fas fa-file-pdf"></i> 下载中文版简历 (PDF)</a>
  <a href="{{ base_path }}/files/transcripts/graduate-transcript-ustc-en.pdf" class="btn btn--success" target="_blank"><i class="fas fa-graduation-cap"></i> USTC Graduate Transcript (EN)</a>
  <a href="{{ base_path }}/files/transcripts/undergraduate-transcript-heu-en.pdf" class="btn btn--warning" target="_blank"><i class="fas fa-award"></i> HEU Undergraduate Transcript (EN)</a>
</div>

---

## Education

**M.Eng. in Mechanics** &nbsp;·&nbsp; *Sep 2024 – Present*  
**University of Science and Technology of China (USTC)**, Hefei, China  
- **Department:** Department of Modern Mechanics  
- **Advisor:** Assoc. Prof. Fenghua Qin  
- **Research Topic:** Propulsion hydrodynamics of tandem undulating fins, LBM, IBM, vortex dynamics  
- **Key Courses:** Advanced Fluid Mechanics (90), Computational Fluid Dynamics (87), Experimental Fluid Mechanics, GPU Parallel Computing  
- **Official Transcript:** [📄 Graduate Transcript (English PDF)]({{ base_path }}/files/transcripts/graduate-transcript-ustc-en.pdf)

**B.Eng. in Naval Architecture & Ocean Engineering** &nbsp;·&nbsp; *Sep 2020 – Jun 2024*  
**Harbin Engineering University (HEU)**, Harbin, China — **Outstanding Graduate (优秀毕业生)**  
- **Academic Standing:** GPA: **89.1 / 100** &nbsp;·&nbsp; Rank: **13 / 191** (Top 7%)  
- **Undergraduate Thesis:** *Wave Loads and Green Water Impact of a Trimaran in Irregular Waves* (Advisor: Assoc. Prof. Xuhui Li) — Grade: Excellent  
- **Key Courses:** Engineering Mathematical Analysis (95), Linear Algebra & Analytic Geometry (96), Probability & Statistics (90), Fluid Mechanics for Naval Architecture (92), Ship Resistance (93)  
- **Official Transcript:** [📄 Undergraduate Transcript (English PDF)]({{ base_path }}/files/transcripts/undergraduate-transcript-heu-en.pdf)

---

## Publications & Manuscripts

<p style="font-size: 0.95rem; color: var(--global-text-color-light); margin-bottom: 1rem;">
  Detailed summaries, abstracts, and citations can be explored on the <a href="/publications/">Publications Page</a>.
</p>

1. **Wenzhuo Li**, Ming Xu, Shunxiang Pang, Fenghua Qin*, Jun Jing**, Wan Cheng, Xisheng Luo.  
   *"Optimized design and investigation about propulsion of bionic Tandem undulating fins II: The coupled effect of phase difference and fin spacing."*  
   **Ocean Engineering** (Elsevier), 2026. *(Under Review)*  
   [📄 Download PDF]({{ base_path }}/files/papers/2026-tandem-undulating-fins.pdf) &nbsp;|&nbsp; [<i class="fas fa-diagram-project"></i> Related CFD Project](/portfolio/tandem-undulating-fins)

2. Chun Li, Xuzhu Li, Yiliang Wang, Dewen Liu, Shuai He, Boqiao Huang, Haoran Cheng, Xiaokai Li, **Wenzhuo Li**, Mingze Tang, Zhengping Zhu, Yadong Zeng.  
   *"IAMReX: an adaptive framework for the multiphase flow and fluid–particle interaction problems."*  
   **Journal of Open Source Software (JOSS)**, 2025. DOI: [10.21105/joss.08080](https://doi.org/10.21105/joss.08080)  
   [📄 Download PDF]({{ base_path }}/files/papers/2025-iamrex-joss.pdf) &nbsp;|&nbsp; [<i class="fab fa-github"></i> GitHub Code](https://github.com/hswind4/IAMReX) &nbsp;|&nbsp; [<i class="fas fa-diagram-project"></i> Related Solver Project](/portfolio/iamrex-solver)

3. Xuzhu Li, Chun Li, Xiaokai Li, **Wenzhuo Li**, Mingze Tang, Yadong Zeng, Zhengping Zhu.  
   *"An open-source, adaptive solver for particle-resolved simulations with both subcycling and non-subcycling methods."*  
   **Physics of Fluids**, 36, 103328, 2024. DOI: [10.1063/5.0236509](https://doi.org/10.1063/5.0236509)  
   [📄 Download PDF]({{ base_path }}/files/papers/2024-iamrex-physics-of-fluids.pdf) &nbsp;|&nbsp; [<i class="fab fa-github"></i> GitHub Code](https://github.com/hswind4/IAMReX) &nbsp;|&nbsp; [<i class="fas fa-diagram-project"></i> Related Solver Project](/portfolio/iamrex-solver)

4. **Wenzhuo Li**, Xuhui Li.  
   *"CFD investigation on the seakeeping of a trimaran in regular and irregular waves."*  
   **Proceedings of the 35th National Conference on Hydrodynamics**, 2024. (EI Compendex, Chinese title: 三体船在规则波和不规则波中耐波性 CFD 模拟研究)  
   [📄 Download PDF]({{ base_path }}/files/papers/2024-trimaran-seakeeping-cfd.pdf) &nbsp;|&nbsp; [<i class="fas fa-diagram-project"></i> Related Marine CFD Project](/portfolio/trimaran-wave-loads)

5. Haoyue Cheng, Jun Guo, Yin Zhang, **Wenzhuo Li**.  
   *"Experimental research on damage identification of fully free beams based on modal shapes."*  
   **Applied Ocean Research**, 139, 103689, 2023. DOI: [10.1016/j.apor.2023.103689](https://doi.org/10.1016/j.apor.2023.103689)  
   [📄 Download PDF]({{ base_path }}/files/papers/2023-modal-damage-identification.pdf)

---

## Research & Engineering Experience

### Hydrodynamic Propulsion of Tandem Undulating Bionic Fins &nbsp;·&nbsp; *USTC (2024 – Present)*
- **Multi-Solver Framework:** Conducted high-fidelity simulations comparing Palabos (Lattice Boltzmann Method), ANSYS Fluent (dynamic mesh UDFs), and IAMReX.
- **Palabos LBM + IBM + LES:** Integrated regularized BGK collision models with Inamuro iterative velocity-correction immersed boundary method for moving bio-fin boundaries.
- **Novel Equivalent Phase Model:** Discovered and formulated an analytical model ($R^2 > 0.97$) predicting posterior fin thrust by normalizing spatial vortex convection lag with temporal phase shift, identifying optimal propulsion parameters ($\Delta x/L = 0.5, \Delta \phi = 240^\circ$).
- [Explore CFD Project Page &rarr;](/portfolio/tandem-undulating-fins)

### IAMReX Adaptive Solver Development & Particle-Resolved DNS &nbsp;·&nbsp; *Collaborator (2023 – 2024)*
- **AMReX Ecosystem Integration:** Contributed to the C++/MPI open-source adaptive mesh solver IAMReX.
- **Immersed Boundary Method (IBM):** Implemented and verified multi-direct forcing IBM for solid-fluid coupling.
- **Benchmark Validation:** Carried out multi-level AMR grid validation and single/multi-particle sedimentation benchmark tests.
- [Explore Solver Project Page &rarr;](/portfolio/iamrex-solver)

### Seakeeping CFD & Slamming Impact of Trimaran in Irregular Waves &nbsp;·&nbsp; *HEU (2023 – 2024)*
- **Overset Grid & VOF:** Used STAR-CCM+ overset meshing and Volume of Fluid (VOF) method to simulate coupled 6-DOF ship motions under regular and irregular JONSWAP waves.
- **Extreme Impact Loads:** Analyzed cross-deck green water impact pressures and structural shear/bending responses, verified against 1:32 scale towing tank experimental data.
- [Explore Marine CFD Project Page &rarr;](/portfolio/trimaran-wave-loads)

---

## Technical Skills

- **Programming Languages:** Python (proficient, NumPy/SciPy/PyTorch), C++ (proficient, modern C++14/17, OOP), Fortran (familiar), MATLAB (familiar)
- **CFD Solvers & Methods:** Palabos (LBM), AMReX (Adaptive Mesh Refinement), ANSYS Fluent (UDF / Dynamic Mesh), STAR-CCM+, OpenFOAM
- **Numerical Methods:** Lattice Boltzmann Method (LBM), Immersed Boundary Method (IBM), Large Eddy Simulation (LES), Volume of Fluid (VOF), Finite Volume Method (FVM)
- **HPC & Engineering Tools:** Linux/Unix, SLURM, MPI / OpenMP parallel computing, Git, Docker, ParaView, Tecplot, SolidWorks, Typst, LaTeX
- **Languages:** English (IELTS 6.0, CET-6; fluent in academic paper writing and technical exchange), Mandarin (Native)

---

## Honors & Awards

- **Outstanding Graduate of Harbin Engineering University (校优秀毕业生)** &nbsp;·&nbsp; *2024*
- **National Motivational Scholarship (国家励志奖学金)** &nbsp;·&nbsp; *2022*
- **Merit Student Award (三好学生)** &nbsp;·&nbsp; *Harbin Engineering University, 2021, 2022, 2023*
- **First-Class Academic Scholarship** &nbsp;·&nbsp; *Harbin Engineering University (top 5%), 2021, 2022*
- **National Second Prize, National Marine Vehicles Design & Creation Competition** &nbsp;·&nbsp; *2022*
