# TD-DFT Simulation Workflow – Conceptual Guide

This document outlines a simplified workflow based on common steps observed in the literature for simulating photosensitizer behavior using TD-DFT.

## General Steps:

1. **Geometry Optimization**
   - Prepare molecular structure using tools like Avogadro or GaussView.
   - Optimize geometry with a suitable ground-state DFT method (e.g. B3LYP/6-31G*).

2. **Excited State Calculation**
   - Apply TD-DFT to compute electronic transitions, particularly the S0 → S1 and T1 states.
   - Extract key parameters: excitation energies, oscillator strengths, HOMO–LUMO gap.

3. **Triplet State Analysis**
   - Model intersystem crossing and analyze triplet quantum yields.
   - Estimate ROS production potential via spin-orbit coupling analysis (where supported).

4. **Validation**
   - Compare simulated λmax and ROS yield with experimental benchmarks.

5. **Documentation**
   - Record functional/basis set choices, convergence criteria, and all visualized states.

This framework supports ongoing development of simulation-informed strategies for drug discovery in photomedicine.
