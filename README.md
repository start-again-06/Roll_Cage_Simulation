# Baja Roll Cage Simulation Framework

## Overview
This project provides a simulation framework for analyzing the structural integrity of a Baja roll cage. It applies Finite Element Analysis (FEA) techniques to perform modal analysis, compute Factor of Safety (FOS), and visualize the roll cage structure.

---

## Features
- Mesh import from tetrahedral `.vtk` files  
- External load application on selected nodes  
- Material property definition (Young’s modulus, Poisson’s ratio, density)  
- Modal analysis using eigenvalue computation  
- Factor of Safety (FOS) calculation and visualization  
- 3D visualization of roll cage geometry  

---

## Inputs
Provide the following values when prompted:
- Young’s Modulus (Pa)
- Poisson’s Ratio
- Density (kg/m³)
- Yield Strength (Pa)

---

## Simulation Workflow
The simulation performs:
- Boundary condition and load application
- Modal analysis
- Factor of Safety (FOS) computation
- 3D visualization of the roll cage

---

## Example Output

### Modal Analysis
- Eigenvalues: `[λ₁, λ₂, λ₃, ...]`

### Factor of Safety
- Histogram representing the FOS distribution

### Visualization
- 3D scatter plot of roll cage nodes

---

## Future Enhancements
- Full FEM stiffness and mass matrix formulation
- Improved boundary condition handling
- Stress–strain and deformation visualization

---

## License
MIT License. Free to use, modify, and distribute for academic and research purposes.

