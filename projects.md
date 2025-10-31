---
layout: page
title: "Projects"
permalink: /projects/
---

A selection of current projects from my work as a **Project Scientist at the Molecular Foundry, Lawrence Berkeley National Laboratory**, focusing on **advanced electron microscopy**, **autonomous characterization**, and **energy/semiconductor materials**.

## 1) Autonomous Electron Microscopy for Energy Materials
**Goal.** Develop closed-loop, AI-assisted TEM/STEM workflows that optimize acquisition in real time to maximize information per electron.  
**Methods.** Aberration-corrected STEM, adaptive sampling, Bayesian optimization, reinforcement learning controllers, EDX/EELS co-acquisition.  
**Recent.** Prototype agent that tunes probe/scan parameters to stabilize beam-sensitive battery interfaces; latency-aware pipeline for on-the-fly drift/defocus correction.  
**Artifacts.** Toolkit (WIP) · Demo notebooks · Preprint (coming soon)

## 2) EELS Spectral Imaging & Denoising Pipelines
**Goal.** Robust extraction of bonding/valence signatures in **battery and semiconductor** systems under low dose.  
**Methods.** MCR, nonlocal spectral denoising, dictionary learning, physics-guided NN priors, automated edge fitting.  
**Recent.** Automated EELS edge finder with uncertainty estimates; batch processing for large spectral cubes (>10⁶ spectra).  
**Artifacts.** `eels-auto` (open-source, WIP) · Example datasets · Parameter recipes

## 3) In-situ TEM of Battery Interfaces
**Goal.** Correlate electrochemical states with nanoscale structure/chemistry during cycling to explain degradation pathways.  
**Methods.** Environmental/in-situ TEM, operando biasing holders, time-resolved STEM/EELS, drift-corrected scanning.  
**Recent.** Quantified interphase growth kinetics in next-gen anodes; mapped beam-dose thresholds for solid-electrolyte phases.  
**Artifacts.** Analysis scripts · Data schema · Preprint link (TBD)

## 4) Semiconductor Defects & Correlative X-ray Microscopy
**Goal.** Identify electrically active defects and their local chemistry/strain in wide-bandgap and 2D semiconductors.  
**Methods.** STEM HAADF/ABF, nano-diffraction, EELS fine structure, nano-XRD/XRF correlation.  
**Recent.** Strain-chemistry co-mapping workflow; automated defect cataloging from large tilts/series.  
**Artifacts.** Pipeline modules · Example figures · Collaboration notes

## 5) Modeling Bridge: DFT → Kinetic Monte Carlo
**Goal.** Close the loop between **atomistic modeling** and **high-resolution microscopy** to interpret transport/thermodynamics.  
**Methods.** DFT energetics, cluster expansion, kMC/MC transport, thermodynamic phase analysis; synthetic image generation for ML.  
**Recent.** Fast kMC kernels validated against EELS-observables; scripts to generate physics-faithful training pairs.  
**Artifacts.** Reproducible workflows · HPC job templates · Code snippets

### Open Science & Software
I maintain open-source **toolkits for image analysis and data processing of complex microscopy signals** and welcome collaborations. See **Publications** and my GitHub for releases and preprints.
