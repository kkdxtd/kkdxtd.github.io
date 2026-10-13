---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
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

**M.Eng. in Mechanics** — *Sep 2024 – Present*  
University of Science and Technology of China (USTC), Hefei, China  
- **Advisor:** Assoc. Prof. Fenghua Qin (Department of Modern Mechanics)  
- **Research:** Propulsion hydrodynamics of tandem undulating fins, LBM, IBM  
- **Key Courses:** Advanced Fluid Mechanics, Computational Fluid Dynamics, Experimental Fluid Mechanics, GPU Parallel Computing  
- **Official Transcript:** [📄 Graduate Transcript (English PDF)]({{ base_path }}/files/transcripts/graduate-transcript-ustc-en.pdf)

**B.Eng. in Naval Architecture & Ocean Engineering** — *Sep 2020 – Jun 2024*  
Harbin Engineering University (HEU), Harbin, China — **Outstanding Graduate (优秀毕业生)**  
- **Thesis:** *Wave Loads and Green Water Impact of a Trimaran in Irregular Waves*  
- **Advisor:** Assoc. Prof. Xuhui Li  
- **Academic Standing:** GPA: **89.1 / 100** &nbsp;·&nbsp; Rank **13 / 191** (Top 7%)  
- **Key Courses:** Engineering Mathematical Analysis, Linear Algebra & Analytic Geometry, Probability & Statistics, Complex Analysis, Fluid Mechanics for Naval Architecture  
- **Official Transcript:** [📄 Undergraduate Transcript (English PDF)]({{ base_path }}/files/transcripts/undergraduate-transcript-heu-en.pdf)

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
Palabos (LBM), AMReX (AMR), STAR-CCM+, ANSYS Fluent, OpenFOAM, ParaView, Tecplot, SolidWorks

**Engineering & HPC Tools**  
Git, Docker, SLURM (HPC), Linux, MPI/GPU parallel computing, LaTeX, Typst

**Languages**  
- Mandarin: Native  
- English: IELTS 6.0, CET-6 passed; proficient in academic literature reading and scientific writing
