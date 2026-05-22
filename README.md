# THz-Metamaterial-Absorber-using-VO-for-Tunable-Terahertz-Applications
Design and simulation of a VO₂-based tunable terahertz metamaterial absorber using ANSYS HFSS, focusing on broadband absorption, resonance tuning, parametric analysis, and electromagnetic field distribution for advanced THz applications.
📌 Overview

This project focuses on the design and simulation of a VO₂-based tunable terahertz metamaterial absorber using ANSYS HFSS.
The goal is to reproduce and further enhance the performance reported in a published IEEE research paper on THz absorbers.

The absorber operates in the terahertz (THz) frequency range and demonstrates tunable absorption characteristics through variations in:

VO₂ conductivity
SiO₂ substrate thickness
Geometrical parameters

This work explores:

Broadband absorption
Resonance tuning
Reflection suppression
Electromagnetic field localization
🔬 Current Progress
✅ 1. HFSS Model Creation

Designed the complete multilayer absorber structure in HFSS including:

VO₂ resonator layer
Silicon dioxide (SiO₂) substrate
Metallic ground plane
Vacuum region

Implemented:

Elliptical ring resonator geometry
Parametric dimensions
Periodic unit-cell structure
✅ 2. Boundary Conditions & Excitations

Configured:

Lattice/Periodic boundaries
Floquet ports
THz frequency sweep setup

This enables accurate simulation of infinite periodic metamaterial structures.

✅ 3. Absorption & Reflection Analysis

Successfully generated:

Absorption spectra
Reflection spectra

Observed:

Resonance peaks
Broadband absorption behavior
Frequency-dependent tunability

Implemented:

A=1−∣S11∣
2
−∣S21∣
2

Since transmission is suppressed using a metallic ground plane:

A≈1−∣S11∣
2
✅ 4. Parametric Studies Performed
✔ SiO₂ Thickness Sweep

Analyzed absorber performance for different substrate thicknesses:

1 µm
3 µm
5 µm
7 µm
9 µm

Observed:

Resonance shifting
Bandwidth variation
Absorption peak changes
✔ VO₂ Conductivity Analysis

Studied the effect of conductivity variation on absorption behavior.

Conductivity range explored:

2 × 10²  S/m  →  2 × 10⁵  S/m
✅ 5. Electromagnetic Field Distribution

Generated:

Electric field (E-field) plots
Resonance field localization analysis

Observed:

Strong field concentration near resonator edges
Enhanced resonance localization at peak absorption frequencies
✅ 6. Simulation Optimization

Improved:

Mesh refinement
Adaptive passes
THz solution setup
Frequency sweep accuracy

Explored:

Discrete sweeps
Interpolating sweeps
High-resolution frequency analysis
📊 Current Results
Successfully Reproduced:
Thickness-dependent absorption trends
Resonance shifting behavior
Reflection suppression
Tunable THz absorption response
🛠 Tools & Technologies
Tool	Purpose
ANSYS HFSS	Electromagnetic simulation
CST Paper Reference	Research comparison
IEEE Research Paper	Reference model
MATLAB/Python (planned)	Post-processing & plotting
GitHub	Version control & research documentation
📈 Future Work
🔄 1. Exact Paper Reproduction
Fine-tune geometry parameters
Improve resonance alignment
Match CST results more closely
⚡ 2. Broadband Absorption Enhancement

Aim:

Increase absorption bandwidth
Achieve near-perfect absorption across wider THz ranges
🧠 3. AI-Assisted Optimization (Planned)

Explore:

AI/ML-based parameter optimization
Automated resonance tuning
Intelligent geometry prediction

Potential techniques:

Genetic Algorithms
Bayesian Optimization
Neural Network based surrogate models
🌐 4. Advanced Tunability

Investigate:

Thermal tuning of VO₂
Dynamic conductivity switching
Multi-band THz absorber behavior
📡 5. Additional Electromagnetic Analysis

Planned simulations:

Surface current distribution
Impedance matching analysis
Effective permittivity/permeability extraction
Polarization sensitivity analysis
📷 Planned Repository Additions
HFSS screenshots
Field distribution plots
Parametric sweep graphs
Simulation setup documentation
Research notes
📚 Research Inspiration

This work is inspired by IEEE research on:

VO₂-based tunable metamaterial absorbers
THz wave manipulation
Broadband electromagnetic absorption
🎯 Project Goal

To build a high-performance, tunable THz metamaterial absorber capable of:

Broadband absorption
Dynamic tunability
Efficient THz wave manipulation

with potential applications in:

THz sensing
Imaging
Wireless communication
Stealth technology
Electromagnetic shielding
<img width="1744" height="470" alt="image" src="https://github.com/user-attachments/assets/70affd01-d60f-4bf0-917d-18e5e8717e2e" />
<img width="1743" height="520" alt="image" src="https://github.com/user-attachments/assets/fc36419a-d596-47e9-9d71-e5b2cda43a47" />
<img width="1066" height="319" alt="image" src="https://github.com/user-attachments/assets/6ad89c21-1c77-407c-9ef1-d2cf867fb02f" />
<img width="386" height="357" alt="image" src="https://github.com/user-attachments/assets/f360bbf3-9c2a-4f7a-b585-3d6c4a72e2fb" />
<img width="1585" height="505" alt="Screenshot 2026-05-20 105457" src="https://github.com/user-attachments/assets/ef0f0d5a-e168-4f07-8d65-0917b69981a8" />






