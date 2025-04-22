# 🚀 CFD Analysis of Converging-Diverging Nozzle (Gas Dynamics Project)

**Course:** MECH 6111 – Gas Dynamics  
**University:** Concordia University 

**Team Members:**  
- Prathmesh Deepak Gondkar  
- Allen Brightus Prince  

## 📌 Project Overview

This project investigates high-speed compressible flow through a converging-diverging (C-D) nozzle using CFD simulations and theoretical 1D analysis. It covers the effect of varying back pressure, visualizing flow features like:

- Choked flow at throat
- Supersonic flow
- Shock formation inside nozzle
- Oblique shocks
- Expansion waves outside the nozzle

## 🛠 Tools Used
- ANSYS Fluent & CFX (Simulation)
- ANSYS DesignModeler (Geometry)
- ANSYS Mesher (Structured Meshing)
- Excel + Isentropic/Normal Shock Tables (1D Theory)

## 📈 Methodology

1. Geometry creation based on isentropic ratios
2. Structured mesh (25,400 elements)
3. Density-based solver setup (steady, inviscid, planar)
4. Boundary conditions using Total Pressure & Temperature
5. Post-processing of Mach, Pressure, Temperature distributions
6. Validation against theoretical 1D gas dynamic equations

## 📊 Key Results

| Condition         | Analytical Mach | CFD Mach | Error % |
|------------------|------------------|----------|---------|
| Choked Flow Exit | 0.226            | 0.215    | 4.9%    |
| Supersonic Exit  | 2.5              | 2.5217   | 0.9%    |
| Oblique Shock    | 2.39             | 2.38     | 0.4%    |
| Expansion Wave   | 2.94             | 2.946    | 0.2%    |

## 📂 Files Included

- `Final Report Gas Dynamics.pdf` – Detailed report of the project  
- `project.wbpj` – ANSYS project file  
- `Images/` – Flow contours and graphs

## 📚 References

- Gas Dynamics by James E. John (3rd Edition)
- ANSYS Fluent User Guide (2024 R2)

## 📬 Contact
For any collaboration or questions, feel free to reach out on [LinkedIn]([https://www.linkedin.com/in/prathmeshgondkar)

---
