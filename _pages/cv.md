---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[📄 Download PDF (English)]({{ base_path }}/files/cv-english.pdf) &nbsp;|&nbsp; [📄 下载中文版简历]({{ base_path }}/files/cv-chinese.pdf)

---

## Education

**M.Eng. in Mechanics** — *Sep 2024 – Present*  
University of Science and Technology of China (USTC), Hefei, China  
- Advisor: Assoc. Prof. Fenghua Qin (Department of Modern Mechanics)  
- Research: Propulsion hydrodynamics of tandem undulating fins  
- Key Courses: Advanced Fluid Mechanics, Computational Fluid Dynamics, Experimental Fluid Mechanics, GPU Parallel Computing

**B.Eng. in Naval Architecture & Ocean Engineering** — *Sep 2020 – Jun 2024*  
Harbin Engineering University (HEU), Harbin, China — **Outstanding Graduate (优秀毕业生)**  
- Thesis: *Wave Loads and Green Water Impact of a Trimaran in Irregular Waves*  
- Advisor: Assoc. Prof. Xuhui Li  
- GPA: 89.1 / 100 &nbsp;·&nbsp; Rank 13 / 191  
- Key Courses: Engineering Mathematical Analysis, Linear Algebra & Analytic Geometry, Probability & Statistics, Complex Analysis, Fluid Mechanics for Naval Architecture

---

## Publications

{% assign publications = site.publications | sort: 'date' | reverse %}
{% for post in publications %}
  {% include archive-single-cv.html %}
{% endfor %}

---

## Research Projects

{% for post in site.portfolio %}
  {% include archive-single-cv.html %}
{% endfor %}

---

## Skills

**Programming Languages**  
Python (proficient), C++ (proficient), Fortran (familiar), MATLAB (familiar)

**CFD & Simulation Tools**  
OpenLB (Lattice Boltzmann), OpenFOAM, Ansys Fluent, Ansys AQWA, CATIA

**Engineering & HPC Tools**  
Git, Docker, SLURM, MPI/OpenMP parallel computing, LaTeX, Typst

**Languages**  
- Mandarin: Native  
- English: CET-6 — 588 pts; proficient in academic writing and international conference presentations
