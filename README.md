# Quantum System Optimization via Variational Monte Carlo

A computational physics suite designed to model and analyze quantum systems numerically. This project solves the Schrödinger Equation for various configurations by combining **Variational Monte Carlo (VMC)** for high-dimensional integration and **Stochastic Gradient Descent (SGD)** for Hamiltonian optimization.

## Systems Modeled
* **Simple Harmonic Oscillators (SHO):** Implementation of multiple oscillators.
* **Electronic Systems:** Modeling electron interactions and distributions.
* **Hydrogen Atoms:** Numerical simulation of the simplest atomic system to validate ground state accuracy.

## Methodology
This repository focuses on finding the ground state energy of quantum systems through:
1.  **Variational Monte Carlo Methods:** Using trial wavefunctions with tunable parameters.
2.  **Monte Carlo Integration:** Utilizing stochastic sampling to evaluate complex expectation values.
3.  **Optimization:** Applying SGD to iteratively minimize the energy functional and converge on the ground state.
