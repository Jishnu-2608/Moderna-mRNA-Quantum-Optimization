# Results and Findings

## Experimental Results

The project successfully implemented a hybrid classical-quantum workflow for RNA secondary structure optimization.

The workflow included:

- RNA sequence generation
- RNA secondary structure prediction using ViennaRNA
- Identification of valid RNA base pairs
- Construction of a QUBO optimization model
- Classical optimization
- Quantum optimization using the Quantum Approximate Optimization Algorithm (QAOA)
- Comparison of optimization results

---

## Optimization Results

The optimization results obtained from the project are shown below.

| Method | Energy |
|---------|--------|
| Classical Optimization | -4 |
| QAOA Optimization | -4 |

For the tested RNA sequence, both optimization methods produced the same optimal objective value.

---

## Interpretation

The RNA folding problem was successfully formulated as a Quadratic Unconstrained Binary Optimization (QUBO) problem.

The QAOA algorithm was able to identify the same optimal solution as the classical optimizer, demonstrating that quantum optimization techniques can be applied to RNA secondary structure prediction.

---

## Visualization

The repository includes a comparison graph illustrating the optimization results obtained using:

- Classical Optimization
- Quantum Approximate Optimization Algorithm (QAOA)

The graph provides a visual comparison of the objective values produced by both methods.

---

## Key Findings

- ViennaRNA successfully predicted RNA secondary structures.
- A valid QUBO optimization model was constructed.
- Classical optimization identified the optimal RNA folding solution.
- QAOA successfully reproduced the same optimal solution.
- The project demonstrates the feasibility of using quantum optimization for RNA secondary structure prediction.

---

## Limitations

The current implementation has several limitations:

- Experiments were performed on short synthetic RNA sequences.
- QAOA was executed on a quantum simulator instead of real quantum hardware.
- The QUBO model is simplified for educational purposes.
- Larger RNA sequences require more qubits and increased computational resources.

---

## Future Improvements

Future work may include:

- Applying the workflow to larger RNA sequences.
- Running QAOA on IBM Quantum hardware.
- Comparing QAOA with Variational Quantum Eigensolver (VQE).
- Developing more realistic QUBO formulations for RNA folding.
- Investigating scalability for complex biological datasets.

---

## Conclusion

The project successfully demonstrated a hybrid classical-quantum approach for RNA secondary structure optimization. The QAOA algorithm achieved the same optimal objective value as the classical optimizer for the tested RNA sequence, indicating that quantum optimization techniques have promising potential for solving computational biology problems.
