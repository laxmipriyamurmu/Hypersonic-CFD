# 🚀 Aerodynamic Performance Analysis of Hypersonic Vehicles Using Computational Fluid Dynamics

## Project Overview

This project investigates the aerodynamic and aerothermal performance of three hypersonic vehicle configurations operating at **Mach 5** and **Mach 7** using **ANSYS Fluent 2024 R1**.

The study focuses on understanding how different nose geometries influence shock-wave formation, aerodynamic drag, pressure distribution, temperature rise, and overall aerodynamic efficiency in hypersonic flight.

---

# Objectives

* Investigate hypersonic flow characteristics around different vehicle geometries.
* Compare aerodynamic performance at Mach 5 and Mach 7.
* Analyze shock-wave formation and stand-off distance.
* Evaluate pressure and temperature distributions.
* Study the influence of nose geometry on drag reduction and aerodynamic efficiency.

---

# Vehicle Configurations

Three different nose configurations were analyzed.

| Model   | Configuration                           |
| ------- | --------------------------------------- |
| Model 1 | Flat / Blunt Nose (NASA X-43A Inspired) |
| Model 2 | Moderate Conical Nose                   |
| Model 3 | Elongated Sharp Conical Nose            |

### CAD Models

| Model 1            | Model 2            | Model 3            |
| ------------------ | ------------------ | ------------------ |
| ![](images/h4.png) | ![](images/h5.png) | ![](images/h6.png) |

---

# CFD Methodology

### Workflow

![](images/h7.png)

The numerical analysis followed these steps:

1. Geometry Creation
2. Computational Domain Generation
3. Mesh Generation
4. Solver Setup
5. Numerical Simulation
6. Convergence Assessment
7. Post Processing
8. Comparative Performance Analysis

---

# Simulation Parameters

| Parameter        | Value                              |
| ---------------- | ---------------------------------- |
| Software         | ANSYS Fluent 2024 R1               |
| Solver           | Density-Based Implicit             |
| Turbulence Model | SST k-ω                            |
| Working Fluid    | Air (Ideal Gas)                    |
| Mach Numbers     | Mach 5 & Mach 7                    |
| Analysis Type    | Three-Dimensional Steady-State CFD |

---

# Mesh Generation

A high-quality unstructured computational mesh was developed for accurate prediction of shock structures and boundary layer effects.

### Computational Mesh

![](images/h8.png)

### Mesh Statistics

* Approximately **4.14 Million Cells**
* Approximately **8.41 Million Faces**
* Approximately **756,000 Nodes**

### Mesh Quality

![](images/h2.png)

---

# Engineering Analysis

The simulations investigated:

* Shock-wave structures
* Pressure distribution
* Temperature distribution
* Density variation
* Drag coefficient
* Lift coefficient
* Aerothermal characteristics
* Flow-field behavior

---

# Results

### Drag Coefficient Convergence

![](images/h1.png)

### Comparative Configuration Summary

![](images/h3.png)

### Key Findings

* Flat/blunt nose produced a detached bow shock.
* Shock stand-off distance decreased with increasing nose sharpness.
* Sharp conical configuration generated lower aerodynamic drag.
* Elongated conical geometry demonstrated the highest aerodynamic efficiency.
* Pressure and temperature concentrations increased near sharper nose tips.
* Nose geometry significantly influences hypersonic aerodynamic performance.

---

# Software & Tools

* ANSYS Fluent 2024 R1
* ANSYS Meshing
* SolidWorks
* Microsoft Excel

---

# Skills Demonstrated

* Computational Fluid Dynamics (CFD)
* Compressible Flow Analysis
* Hypersonic Aerodynamics
* Numerical Simulation
* Mesh Generation
* Aerodynamic Performance Analysis
* Engineering Research
* Scientific Documentation

---

# Repository Structure

```text
Hypersonic-CFD
│
├── images
│   ├── h1.png
│   ├── h2.png
│   ├── h3.png
│   ├── h4.png
│   ├── h5.png
│   ├── h6.png
│   ├── h7.png
│   └── h8.png
│
├── report
│   └── Hypersonic_CFD_Report.pdf
│
├── results
│
└── README.md
```

---

# Technical Report

📄 The complete project report is available in the **report** directory.

> **Download:**
> `[Hypersonic_CFD_Report.pdf](report/Hypersonic_CFD_Report.pdf)`

> **Note:** Replace `Hypersonic_CFD_Report.pdf` with the exact filename of your PDF if it is different.

---

# Future Work

* Grid independence study
* Turbulence model comparison
* Thermal Protection System (TPS) analysis
* Optimization of hypersonic vehicle geometry
* Transient CFD simulations
* Higher Mach number investigations

---

# Authors

* **Laxmipriya Murmu**
* Gowtham Kumar Talla
* Shaikh Mohd Zafar Iqbal Jawaid Ashraf
* Mounish Damera
* Jitesh Jambulkar

### Faculty Guide

**Dr. Rahul Kumar**

---

## License

This repository is intended for academic, educational, and research purposes.
