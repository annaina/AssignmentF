# README

## Hybrid Intelligent Systems - MATLAB Code

This repository contains the MATLAB code for the Hybrid Intelligent Systems assignment.

### Implementation 1: Neuro-Fuzzy Controller Training
- The code trains a neuro-fuzzy inference system (ANFIS) based on input/output data.
- You must have the **fuzzy water tank controller** example (`tank.fis`) from the MATLAB Fuzzy Logic Toolbox.
- Ensure that you **read** the `tank.fis` file using `readfis`, and **set the FIS variable** correctly inside the Simulink **Fuzzy Logic Controller** block before running any simulations.

### Implementation 2: Hybrid Intelligent System - Fuzzy Optimization
- The code uses Genetic Algorithm (GA), Particle Swarm Optimization (PSO), and ANFIS tuning methods.
- You must have the **Auto MPG** dataset (`auto-mpg.csv`) available in the same folder as the scripts.
- The scripts automatically handle normalization, training, optimization, and evaluation.

### Important
- Scripts are written for MATLAB R2023a or later.
- Make sure the required toolboxes are installed:
  - Fuzzy Logic Toolbox
  - Global Optimization Toolbox (for GA and PSO)

### Author
Anna Naylor

