# Methodology

## Overview

This project follows a hybrid classical-quantum workflow to investigate RNA secondary structure optimization. Classical RNA folding is performed using ViennaRNA, while quantum optimization is implemented using the Quantum Approximate Optimization Algorithm (QAOA) in Qiskit.

---

## Workflow

RNA Sequence Generation
        |
        ↓
RNA Secondary Structure Prediction (ViennaRNA)
        |
        ↓
Identification of Valid Base Pairs
        |
        ↓
QUBO Matrix Construction
        |
        ↓
Classical Optimization
        |
        ↓
QAOA Optimization
        |
        ↓
Result Comparison and Analysis

---

## Step 1: RNA Sequence Generation

Synthetic RNA sequences containing the four RNA nucleotides were generated:

- A (Adenine)
- U (Uracil)
- C (Cytosine)
- G (Guanine)

Synthetic sequences were used for experimentation and demonstration purposes.

---

## Step 2: RNA Secondary Structure Prediction

The ViennaRNA package was used to predict the RNA secondary structure and calculate the Minimum Free Energy (MFE) for each RNA sequence.

These results serve as the classical biological reference.

---

## Step 3: Base Pair Identification

Possible RNA base pairs were identified according to RNA pairing rules:

- A – U
- C – G
- G – U (Wobble Pair)

These valid base pairs were used to construct the optimization problem.

---

## Step 4: QUBO Model Construction

The RNA folding problem was formulated as a Quadratic Unconstrained Binary Optimization (QUBO) model.

The QUBO matrix includes:

- Objective function for minimizing energy
- Constraints to prevent invalid or conflicting base pairs

This formulation allows the optimization problem to be solved using quantum algorithms.

---

## Step 5: Classical Optimization

A classical optimization approach was used to search all possible binary solutions and identify the configuration with the minimum objective value.

This solution serves as the baseline for comparison.

---

## Step 6: Quantum Optimization (QAOA)

The QUBO problem was solved using the Quantum Approximate Optimization Algorithm (QAOA) implemented with Qiskit.

The algorithm was executed on a quantum simulator to obtain the optimal solution.

---

## Step 7: Performance Comparison

The results obtained from classical optimization and QAOA were compared using:

- Objective (energy) values
- Selected RNA base pairs
- Comparison graph

---

## Tools and Technologies

### Programming Language

- Python

### Libraries

- Qiskit
- Qiskit Algorithms
- ViennaRNA
- NumPy
- Pandas
- Matplotlib

### Platform

- Google Colab

---

## AI Usage Disclosure

ChatGPT was used for:

- Code explanation
- Documentation assistance
- Repository organization
- Debugging support

All generated content was reviewed, verified, and modified before inclusion in the final project.
