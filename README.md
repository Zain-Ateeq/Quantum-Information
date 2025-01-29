# Quantum-Information
This repository is dedicated to Quantum Information Science (QIS), featuring simulations, code, and implementations related to quantum computing, quantum channels, and other QIS-related topics. It serves as a collection of my research, experiments, and projects in quantum information theory, providing resources for future work and exploration.
## Quantum Channel Simulations
This notebook simulates quantum channels using quantum gates and density matrices. It includes visualization tools to represent transformations in 3D space.
On the left of the following picture you can see the comparison of pure and mixed states represented on a bloch ball. And on the right you can see the effect of amplitude damping channel on pure states
![GlimpseOfSimulations](https://github.com/user-attachments/assets/a71bba6a-6745-4521-8dbe-6ffa2ff2228a)

### Features
- Implements single-qubit quantum gates (X Y and Z Gates, Pauli matrices, Hadamard, Phase, T-gate, and rotation gates).
- Generates density matrices for pure and mixed states.
- Provides an interactive 3D visualization of quantum state transformations using Plotly.
- Simulates random quantum states and their evolution through quantum channels.

### Requirements
To run this notebook, install the following dependencies:
```bash
pip install numpy matplotlib plotly
```

### Usage
1. Clone the repository:
```bash
git clone <repository_url>
cd <repository_folder>
```
2. Open the Jupyter Notebook:
```bash
jupyter notebook Quantum Channels Simulations.ipynb
```
3. Run the cells sequentially to simulate quantum channels and visualize the results.

### Visualization
The notebook includes an `interactivePlot` function, which generates interactive 3D plots of original and transformed quantum states, aiding in the analysis of quantum operations.

### Author
Zain Ateeq

