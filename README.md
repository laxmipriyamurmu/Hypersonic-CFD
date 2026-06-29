# Aerodynamic Performance Analysis of Hypersonic Vehicles Using Computational Fluid Dynamics

## Project Overview

This project presents a Computational Fluid Dynamics (CFD) investigation of three hypersonic vehicle configurations operating at **Mach 5** and **Mach 7** using **ANSYS Fluent 2024 R1**.

The objective was to evaluate the influence of nose geometry on aerodynamic performance by analyzing shock-wave behavior, pressure distribution, temperature rise, drag characteristics, and overall aerodynamic efficiency under hypersonic flow conditions.

---

## Objectives

* Analyze hypersonic flow behavior around different vehicle geometries.
* Investigate detached and attached shock-wave formation.
* Compare aerodynamic performance at Mach 5 and Mach 7.
* Evaluate pressure and temperature distributions over the vehicle surface.
* Study the influence of nose geometry on drag characteristics and aerodynamic efficiency.

---

## Vehicle Configurations

Three hypersonic configurations were investigated:

| Model   | Nose Configuration                      |
| ------- | --------------------------------------- |
| Model 1 | Flat / Blunt Nose (NASA X-43A Inspired) |
| Model 2 | Moderate Conical Nose                   |
| Model 3 | Elongated Sharp Conical Nose            |

---

## Simulation Methodology

### CFD Software

* ANSYS Fluent 2024 R1

### Flow Conditions

| Parameter        | Value                              |
| ---------------- | ---------------------------------- |
| Flow Regime      | Compressible Hypersonic Flow       |
| Mach Numbers     | 5 and 7                            |
| Solver           | Density-Based Implicit             |
| Turbulence Model | SST k-ω                            |
| Working Fluid    | Air (Ideal Gas)                    |
| Analysis Type    | Three-Dimensional Steady-State CFD |

---

## Mesh Generation

A high-quality computational mesh was generated for each configuration to accurately capture hypersonic shock structures and boundary layer effects.

### Mesh Characteristics

* Approximately **4.14 Million Cells**
* Approximately **8.41 Million Faces**
* Approximately **756,000 Nodes**
* Orthogonal Quality Assessment
* Local mesh refinement near the vehicle surface

---

## Engineering Analysis

The simulations evaluated:

* Shock-wave structures
* Pressure distribution
* Temperature distribution
* Density variation
* Lift coefficient
* Drag coefficient
* Aerothermal behavior
* Flow-field characteristics

---

## Key Contributions

* Developed three-dimensional hypersonic vehicle geometries.
* Generated high-quality computational meshes for CFD analysis.
* Performed numerical simulations at Mach 5 and Mach 7.
* Evaluated aerodynamic forces and pressure distributions.
* Compared the influence of nose geometry on aerodynamic performance.
* Investigated aerothermal characteristics under hypersonic flight conditions.

---

## Software & Tools

* ANSYS Fluent 2024 R1
* ANSYS Meshing
* SolidWorks
* Microsoft Excel

---

## Results

The study demonstrated:

* Accurate prediction of hypersonic flow behavior.
* Visualization of detached and attached shock waves.
* Comparative evaluation of three nose geometries.
* Reduction in aerodynamic drag with sharper nose configurations.
* Higher aerodynamic efficiency for elongated conical designs.
* Significant influence of nose geometry on pressure and temperature distributions.

---

## Skills Demonstrated

* Computational Fluid Dynamics (CFD)
* Hypersonic Aerodynamics
* Compressible Flow Analysis
* Numerical Simulation
* Mesh Generation
* Aerodynamic Performance Analysis
* Flow Visualization
* Engineering Research

---

## Future Work

* Grid independence studies
* Comparison of turbulence models
* Thermal protection system (TPS) analysis
* High-temperature material evaluation
* Transient hypersonic simulations
* Optimization of vehicle geometry

---

## Repository Structure

```text
Hypersonic-CFD
│
├── images/        # CAD models, mesh, plots and figures
├── report/        # Complete project report
├── results/       # CFD outputs and analysis
└── README.md
```

---

## Author

**Laxmipriya Murmu**

B.Tech Aerospace Engineering
Lovely Professional University

---

## Acknowledgements

This project was carried out as part of the B.Tech Aerospace Engineering curriculum under the guidance of **Dr. Rahul Kumar**.
