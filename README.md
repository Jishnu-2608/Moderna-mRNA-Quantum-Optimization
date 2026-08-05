# Optimization of mRNA Secondary Structure Using Quantum Computing

## Challenge Selected

WISER Summer Program 2026 - Moderna Challenge

## Problem Statement

RNA secondary structure prediction is a computationally challenging problem because the number of possible folding combinations increases rapidly with sequence length.

This project explores quantum computing approaches for optimizing RNA folding using energy minimization.

## Proposed Solution

A hybrid classical-quantum workflow is developed using Python and Qiskit to compare classical minimum free energy calculations with quantum optimization.

## Limitations

- Tested on short synthetic RNA sequences.
- Quantum simulation was used instead of real quantum hardware.
- Larger sequences require more computational resources.

## Future Scope

- Implement QAOA/VQE optimization.
- Test larger RNA sequences.
- Explore real quantum hardware.
- Improve scalability.

## AI Usage Disclosure

ChatGPT was used for documentation assistance, code explanation, and repository organization guidance. All content was reviewed and verified by the project developer.

## Project Overview

This project demonstrates how quantum computing can be applied to optimize mRNA secondary structure prediction. Classical minimum free energy (MFE) calculations are compared with a quantum-inspired optimization approach implemented using Qiskit.

## Objectives

- Generate RNA sequences
- Predict RNA secondary structures
- Calculate classical minimum free energy
- Build quantum circuits using Qiskit
- Compare classical and quantum energy values
- Visualize performance

## Technologies

- Python
- Qiskit
- NumPy
- Pandas
- Matplotlib
- Google Colab

## Workflow

1. Generate RNA sequences
2. Predict secondary structure
3. Calculate classical MFE
4. Build quantum circuit
5. Perform quantum optimization
6. Compare results
7. Visualize energies

## Results

Average Classical Energy: -0.35 kcal/mol

Average Quantum Energy: -0.55 kcal/mol

Average Improvement: 0.20 kcal/mol

## Conclusion

The quantum optimization workflow achieved lower energy values than the classical approach in this demonstration, showing the potential of quantum computing for biological optimization problems.

## Author

Jishnunagasre Penumudi
