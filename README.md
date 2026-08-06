# Optimization of mRNA Secondary Structure Using Quantum Computing

## Challenge Selected

**WISER Summer Program 2026 – Moderna Challenge**

# Problem Statement

RNA secondary structure prediction is an important problem in computational biology because RNA molecules fold into structures that influence their biological functions. Finding the most stable secondary structure requires minimizing the free energy, but the number of possible folding combinations grows rapidly as the RNA sequence length increases.

This project investigates how quantum optimization techniques can be applied to model and solve RNA secondary structure prediction as a combinatorial optimization problem.

# Proposed Solution

A hybrid classical-quantum workflow was developed using **Python**, **ViennaRNA**, and **Qiskit**.

The workflow:

- Generates an RNA sequence.
- Predicts its secondary structure using ViennaRNA.
- Identifies valid RNA base pairs.
- Converts the folding problem into a **Quadratic Unconstrained Binary Optimization (QUBO)** model.
- Solves the optimization problem using both:
  - Classical optimization
  - Quantum Approximate Optimization Algorithm (QAOA)
- Compares the results obtained from both approaches.

# Project Overview

This project demonstrates how RNA secondary structure prediction can be formulated as a quantum optimization problem.

Instead of only calculating Minimum Free Energy (MFE), the RNA folding problem is transformed into a QUBO optimization model and solved using the Quantum Approximate Optimization Algorithm (QAOA). The obtained solution is then compared with the classical optimization result.

# Objectives

- Generate RNA sequences
- Predict RNA secondary structures using ViennaRNA
- Identify valid RNA base pairs
- Construct the QUBO optimization model
- Solve the optimization problem classically
- Solve the optimization problem using QAOA
- Compare both optimization methods
- Visualize optimization results

# Technologies Used

- Python
- Qiskit
- Qiskit Algorithms
- ViennaRNA
- NumPy
- Pandas
- Matplotlib
- Google Colab

# Installation

## Clone the repository

```bash
git clone https://github.com/Jishnu-2608/Moderna-mRNA-Quantum-Optimization.git
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Run the project

Open

```
Moderna_QAOA_Project.ipynb
```

in **Google Colab** or **Jupyter Notebook** and execute all cells in order.

---

# Workflow

1. Generate RNA sequence
2. Predict RNA secondary structure
3. Identify valid RNA base pairs
4. Construct the QUBO matrix
5. Perform classical optimization
6. Apply QAOA optimization
7. Compare optimization results
8. Visualize final energies

---

# RNA Secondary Structure

RNA secondary structure represents how nucleotides pair together through hydrogen bonding.

Allowed RNA base pairs include:

- A – U
- C – G
- G – U

The most stable RNA structure generally corresponds to the minimum free energy configuration.

---

# Quantum Optimization

The RNA folding optimization problem is formulated as a **Quadratic Unconstrained Binary Optimization (QUBO)** model.

Each binary variable represents whether a potential RNA base pair is selected.

The QUBO model is optimized using:

- Classical optimization
- Quantum Approximate Optimization Algorithm (QAOA)

implemented using Qiskit.

---

# Results

### Classical Optimization

Best Energy:

```
-4
```

### Quantum Optimization (QAOA)

Objective Value:

```
-4
```

### Comparison

The QAOA solution achieved the same optimal objective value as the classical optimizer for the tested RNA sequence.

This demonstrates that RNA secondary structure optimization can be formulated and solved using quantum optimization techniques.

---

# Limitations

- Tested on a short synthetic RNA sequence.
- QAOA was executed on a quantum simulator rather than real quantum hardware.
- Larger RNA molecules require more computational resources and larger quantum circuits.

---

# Future Scope

- Apply the workflow to longer RNA sequences.
- Implement Variational Quantum Eigensolver (VQE).
- Execute the optimization on IBM Quantum hardware.
- Improve scalability of the QUBO formulation.
- Explore advanced quantum optimization techniques.

---

# AI Usage Disclosure

ChatGPT was used for:

- Code explanation
- Documentation assistance
- Repository organization
- README preparation

All generated content was reviewed, verified, and tested before submission.

---

# Team Members

**Individual Project**

**Jishnunagasre Penumudi**

Responsibilities:

- Literature Review
- Project Design
- RNA Folding Analysis
- QUBO Formulation
- QAOA Implementation
- Classical Optimization
- Documentation
- GitHub Repository Management

---

# Repository Contents

```
Moderna-mRNA-Quantum-Optimization/

│── Moderna_QAOA_Project.ipynb
│── README.md
│── requirements.txt
│── RNA_Quantum_Comparison.csv
│── comparision_graph.png
│── Problem_Statement.md
│── Methodology.md
│── Results.md
│── References.md
```

---

# Author

**Jishnunagasre Penumudi**

B.Tech CSE

WISER Summer Program 2026 – Moderna Challenge

---

# References

1. Qiskit Documentation — https://qiskit.org
2. ViennaRNA Package Documentation — https://www.tbi.univie.ac.at/RNA/
3. Moderna Therapeutics — https://www.modernatx.com
4. IBM Quantum Documentation — https://quantum.ibm.com
