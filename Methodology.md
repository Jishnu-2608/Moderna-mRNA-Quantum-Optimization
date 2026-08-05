# Methodology

## Overview

The project follows a hybrid classical-quantum workflow to compare traditional RNA folding approaches with quantum optimization techniques.

## Workflow

RNA Sequence Generation
        |
        ↓
Classical MFE Calculation
        |
        ↓
Quantum Circuit Development
        |
        ↓
Quantum Optimization Simulation
        |
        ↓
Energy Comparison and Analysis


## Step 1: RNA Sequence Generation

Synthetic RNA sequences containing the four RNA nucleotides were generated:

- A (Adenine)
- U (Uracil)
- C (Cytosine)
- G (Guanine)

Only synthetic sequences were used to satisfy data privacy requirements.

## Step 2: Classical Benchmark

The classical approach was used as a reference method.

The Minimum Free Energy (MFE) represents the most stable RNA structure.

Classical energy values were calculated and used as a benchmark.

## Step 3: Quantum Computing Approach

A quantum circuit was created using Qiskit.

The workflow included:

- Quantum state preparation
- Quantum circuit simulation
- Optimization-based energy comparison

The quantum approach was evaluated using a quantum simulator instead of real quantum hardware.

## Step 4: Performance Comparison

Classical and quantum energy values were compared using:

- Energy values
- Average improvement
- Visualization graphs

## Tools and Technologies

Programming Language:
- Python

Libraries:
- Qiskit
- NumPy
- Pandas
- Matplotlib

Platform:
- Google Colab

## AI Usage Disclosure

ChatGPT was used for:

- Project documentation assistance
- Code explanation
- Repository organization guidance

All generated content and code were reviewed, modified, and verified by the project developer.
