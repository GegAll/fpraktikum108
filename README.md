# J/ψ Decay Simulation and Inverse CDF Monte Carlo Sampling

This repository contains a Jupyter Notebook implementing a simulation of the decay of a J/ψ particle into two muons (\(\mu^+\) and \(\mu^-\)) using **Monte Carlo methods**, **Inverse CDF Sampling**, and the **Runge-Kutta 4th order (RK4)** numerical method for trajectory evolution.  

---

## Table of Contents

1. [Project Description](#project-description)
2. [Key Features](#key-features)
3. [Dependencies](#dependencies)
4. [How to Run](#how-to-run)
5. [Output and Results](#output-and-results)
6. [Acknowledgments](#acknowledgments)

---

## Project Description

This notebook focuses on simulating the decay of the **J/ψ particle** into two muons in a simplified center-of-mass frame. Using numerical methods and probabilistic techniques, the project generates the momentum distribution of muons, handles the decay dynamics, and visualizes the results.

Key computational techniques:
- **Inverse CDF Monte Carlo Sampling** to sample resonance masses from a distribution.
- **RK4 Integration** to solve equations of motion in an external electromagnetic field.
- **Simulation and visualization** of particle trajectories.

---

## Key Features

- **Decay Simulation**:
   - Decay of the J/ψ particle into two muons.
   - Calculation of muon momenta based on the invariant mass of the J/ψ particle.

- **Inverse CDF Sampling**:
   - Sampling a resonance mass from a given probability density function (PDF) using the inverse CDF method.
   - Ensures a realistic resonance distribution.

- **Trajectory Calculation**:
   - Use of the RK4 method to compute muon trajectories in a given field.
   - Simulates the influence of external electromagnetic fields on particle motion.

- **Visualization**:
   - Histogram plots of the sampled distributions.
   - Trajectory visualization of muons in \(x\)-\(y\) space.

---

## Dependencies

To run this notebook, the following libraries are required:

- Python 3.x
- Numpy
- Matplotlib
- Scipy
- Jupyter Notebook

You can install the required libraries using pip:

```bash
pip install numpy matplotlib scipy notebook
```

## How to Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/jpsi-decay-simulation.git
   cd jpsi-decay-simulation
   ```

2. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

3. Open the notebook file `FPraktikum108.ipynb` in your Jupyter Notebook environment.

4. **Run the cells sequentially** to perform the simulation.

---

## Output and Results

The notebook produces the following outputs:

1. **CDF and PDF Sampling**:
   - Plots showing the original PDF and sampled data using the Inverse CDF Monte Carlo method.

2. **Muon Momentum**:
   - Calculation and verification of muon momenta following the J/ψ decay.

3. **Muon Trajectories**:
   - \(x\)-\(y\) trajectory plots of the muons calculated using the RK4 numerical integration method.

4. **Histograms**:
   - Visualization of sampled resonance masses and resulting distributions.

---

## Acknowledgments

This project is inspired by theoretical and computational techniques in high-energy physics, particularly in the study of particle decays and numerical solutions of equations of motion. Special thanks to any external references or collaborators involved.

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
