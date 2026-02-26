---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="/files/Bryant_Li_CV.pdf" class="btn btn--primary" style="margin-bottom:1em;">Download Full CV (PDF)</a>

## Education

**University of California, Berkeley** &emsp;&emsp; Ph.D. Materials Science & Engineering *(Aug 2021 – May 2026)*
- Advisor: Prof. Kristin A. Persson, Lawrence Berkeley National Laboratory

**University of California, Berkeley** &emsp;&emsp; M.S. Materials Science & Engineering *(Dec 2023)*
- GPA: 3.80, Graduate Certificate in Applied Data Science

**The Pennsylvania State University** &emsp;&emsp; B.S. Materials Science & Engineering *(May 2021)*
- *Magna cum laude*, GPA: 3.87, Minor: Applied Mathematics, Dean's List (all semesters)

---

## Research Experience

### Graduate Student Researcher, Persson Group
*Lawrence Berkeley National Laboratory / UC Berkeley* &emsp;&emsp; Aug 2021 – Present

**AI/ML Algorithm Development**
- Developed and benchmarked MLIPs (MACE, ACE, GRACE, NequIP, M3GNet, CHGNet, DeepMD-kit) for reactive disordered systems
- Identified ACE-based descriptors outperform spherical-harmonic architectures for amorphous morphology prediction, 100× faster inference on CPUs while maintaining accuracy for million-atom simulations

**Interface & Surface Reaction Modeling**
- Discovered 4-layer heterogeneous SEI morphology (Li<sub>x</sub>P, nanocrystalline Li<sub>2</sub>S, disordered Li<sub>x</sub>P-Li<sub>2</sub>S, amorphous electrolyte) invisible to in-situ XPS/SEM
- Explained passivation via electronic bandgap analysis: Li<sub>2</sub>S acts as insulating barrier while Li<sub>x</sub>P phases are semiconducting (1.1–1.8 eV)
- Distinguished SEI from mixed-conductor interphase (MCI) based on Na<sub>x</sub>P percolation pathways

**Million-Atom Reactive Simulations**
- Executed 1M-atom, 10 ns reactive interface simulations, equivalent to millions of CPU-hours of AIMD, to characterize SEI vs. MCI formation kinetics

**Open-Source Development (MPMorph/Atomate2)**
- Architected core MPMorph module for automated melt-quench MD; integrated Packmol backend for molecular packing
- Adopted by 50+ researchers across NERSC matgen allocation; maintained with 90% unit test coverage and CI/CD

**Active Learning Framework**
- Developed pipeline combining structural generation with MaxVol and DIRECT sampling
- Outperformed generative models (MatterGen, ChgGEN) for discovering interface reactivity intermediates

**High-Throughput Data Analytics**
- Managed scalable data pipelines across 3 MongoDB databases (50k+ entries each)
- Contributed 15k entries to Materials Project R2SCAN database (public release v2025.09.25)

**Technical Leadership**
- Lead representative for DOE BMR and ESRA consortiums; present quarterly to multi-institutional teams
- Mentored 5+ PhD students and postdocs across 5 consortiums on MLIP development and deployment

---

### Undergraduate Research Assistant, Dabo Group
*The Pennsylvania State University* &emsp;&emsp; Sept 2018 – May 2021

- Executed 1000+ DFT calculations (Quantum ESPRESSO) to model surface adsorption and charge transfer kinetics for Pt–Pd nanoparticle electrocatalysts (DOE-funded)
- Developed cluster basis sets with ICET for cluster expansion; performed Monte Carlo simulations to predict surface morphology
- First-author contribution demonstrating thermodynamic favorability of Pd channel formation; published in *Physical Review B*

---

### Research Assistant, Lemke Group
*University of Hong Kong* &emsp;&emsp; Sept 2016 – Dec 2017

- Modeled catalytic NH₃ production on Fe–Ni alloy clusters (Awaruite, Tetrataenite) for prebiotic nitrogen fixation
- Classical modeling using Finnis–Sinclair, Lennard–Jones, and Sutton–Chen potentials (n ≤ 24 atoms)
- Presented at 2017 AGU Fall Meeting

---

## Technical Skills

**AI/ML & Algorithm Development**
PyTorch, TensorFlow, JAX | MLIPs: MACE, ACE, GRACE, NequIP, Allegro, M3GNet, CHGNet, DeepMD-kit | Active Learning (MaxVol, DIRECT) | GPU/CPU Deployment

**Atomistic Simulation & Electronic Structure**
DFT (VASP, Quantum ESPRESSO, PBEsol, r²SCAN) | AIMD | Classical MD (LAMMPS) | Bandstructure & DOS | Interface Reactivity | Amorphous/Disordered Systems

**Software Engineering**
Python | atomate2/pymatgen (core contributor) | Git/GitHub | Unit Testing (90% coverage) | Kokkos-enabled LAMMPS | Docker | AI-Assisted Dev (Claude Code, Cursor)

**Data & HPC**
MongoDB (150k+ entries) | Pandas, NumPy, SciPy | NERSC Perlmutter, NREL Kestrel | SLURM | CUDA/Kokkos Parallelization

**Visualization**
OVITO Pro | VESTA | Trajectory Analysis | Electronic Structure Visualization

**Languages**
English (fluent) | Mandarin (fluent) | Cantonese (fluent)

---

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

## Talks & Presentations

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

---

## Teaching

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

## Honors & Awards

| Award | Year |
|-------|------|
| UCB MSE Corrosion Award | 2025–2026 |
| DOE Energy Storage Research Alliance (ESRA) | 2023–Present |
| DOE Advanced Battery Materials Research (BMR) | 2021–Present |
| Sam Zerfoss Memorial Scholarship | 2019–2021 |
| Matthew J. Wilson Honors Scholarship | 2020–2021 |
| The Sobota Family Scholarship | 2020 |
| Edward S. Sproles, Jr. Scholarship Fund | 2020 |
| John and Elizabeth Holmes Teas Merit Scholarship | 2019 |
| Virginia S. and Phillip L. Walker, Jr. Scholarship | 2018 |

---

## Certifications

- Graduate Certificate in Applied Data Science
- International Baccalaureate (IB) Bilingual Diploma
