# Computational Fluid Dynamics Investigation of Motorcycle Aerodynamics

**Candidate:** Garimella Vihaan Snuhith  
**Assignment:** Section B - Option A (External Aerodynamics)  

---

## 🎯 Project Scope & Objectives

This project entails a steady-state Computational Fluid Dynamics (CFD) investigation into the external aerodynamics of a high-performance motorcycle fairing. The primary objective is to validate a "Blockage Model" geometry designed to minimize aerodynamic drag while enhancing vehicle stability at cruising velocities.

The scope of this analysis encompasses:

1.  **Geometric Modeling:** Development of a parametric CAD model in **Autodesk Fusion 360** representing the frontal area and bluff-body characteristics of a sport motorcycle, featuring a parabolic nose and windshield assembly.
2.  **Flow Domain Discretization:** Generation of a hybrid unstructured mesh with high-fidelity boundary layer resolution (inflation layers targeting $y+ \approx 30$) to accurately capture near-wall flow physics.
3.  **Physics Simulation:** Execution of a 2D steady-state RANS (Reynolds-Averaged Navier-Stokes) simulation using **Ansys Fluent**. The **$k-\omega$ SST** turbulence model was selected to resolve flow separation under adverse pressure gradients.
4.  **Performance Quantification:** Evaluation of key aerodynamic coefficients, including:
    * **Drag Force ($F_d$):** Assessing the efficiency of the fairing shape.
    * **Lift Force ($F_l$):** Analyzing vertical forces for high-speed stability (Downforce vs. Lift).
    * **Wake Topology:** Visualizing recirculation zones and vortex shedding mechanisms.

## 🛠️ Methodology
* **Velocity Inlet:** $33.33~m/s$ ($120~km/h$)
* **Ground Condition:** Moving Wall (Translational)
* **Wheel Boundary:** Rotating Wall (Tangential Velocity $\omega = 111.1~rad/s$)
* **Fluid Properties:** Incompressible Air ($\rho = 1.225~kg/m^3$)

## 📊 Key Results
The simulation validated the design efficiency, yielding a total drag force of **203.6 N** and a net downforce of **-19.2 N**, confirming the effectiveness of the fairing geometry in suppressing front-end lift.

---
## 🤖 AI Usage Declaration
* **Documentation:** Gemini LLM was utilized to structure the technical report and refine engineering terminology.
* **Engineering:** All CAD modeling, mesh generation, physics setup, and post-processing were performed manually by the candidate.
