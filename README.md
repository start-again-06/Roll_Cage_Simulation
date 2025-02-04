🚗 Baja Roll Cage Simulation Framework

📌 Overview:

This project provides a simulation framework for analyzing the structural integrity of a Baja roll cage. It utilizes Finite Element Analysis (FEA) techniques to compute modal analysis, factor of safety (FOS), and visualize the roll cage structure.

🔧 Features:

🏗️ Mesh Import: Reads a tetrahedral mesh from a .vtk file

🏋️ Load Application: Apply external forces to specific nodes

🔩 Material Properties: Define Young's modulus, Poisson's ratio, and density

📊 Modal Analysis: Compute eigenvalues and eigenvectors

🔥 Factor of Safety Analysis: Calculate and visualize FOS distribution

📈 3D Visualization: Render the roll cage mesh in 3D

📦 Dependencies:

Ensure you have the following Python libraries installed:

pip install numpy meshio matplotlib scipy

🚀 Usage:

Run the script and provide necessary material properties as user inputs:

python baja_rollcage_sim.py

Enter the required values when prompted:

Young’s Modulus (Pa)

Poisson’s Ratio

Density (kg/m³)

Yield Strength (Pa)

The simulation will:

Apply boundary conditions and loads

Perform modal analysis

Compute and plot the Factor of Safety

Display a 3D scatter plot of the roll cage structure

📊 Example Output:

Modal Analysis Results:

Eigenvalues: [x1, x2, x3, ...]

Factor of Safety Histogram:

📊 A histogram plot representing the FOS distribution

3D Roll Cage Visualization:

🖥️ A 3D scatter plot of nodes

🛠️ Future Enhancements:

✅ Implement real FEM stiffness/mass matrix calculation

✅ Improve boundary condition handling

✅ Integrate stress-strain visualization
