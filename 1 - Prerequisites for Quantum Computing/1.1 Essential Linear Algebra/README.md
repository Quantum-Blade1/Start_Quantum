# 1.1 Essential Linear Algebra

Linear algebra is the language of quantum computing — every qubit is a vector, every quantum gate is a matrix, and every measurement is an eigenvalue problem.

> **Tip:** Run the code cells yourself and experiment with different values. The best way to learn linear algebra for QC is by doing.

## Notebooks

Work through these in order. Each one builds on the previous.

| # | Notebook | What You Learn |
|---|----------|---------------|
| 01 | Complex Numbers | Real/imaginary, conjugate, modulus, polar form, qubit amplitudes |
| 02 | Vectors and Dirac Notation | Kets, bras, basis states, superposition, normalization |
| 03 | Inner and Outer Products | Measurement probability, orthogonality, projection operators |
| 04 | Matrices and Operations | Gate application, matrix multiplication, dagger, gate chaining |
| 05 | Special Matrices | Hermitian, unitary, Pauli gates, Hadamard, phase gates |
| 06 | Eigenvalues and Eigenvectors | Measurement outcomes, spectral decomposition |
| 07 | Tensor Products | Multi-qubit states, entanglement, exponential scaling |
| 08 | Linear Algebra in Action | Build a Bell state circuit from scratch, verify with Qiskit |

## Requirements

- Python 3
- NumPy
- Qiskit (for notebook 08)

```
pip install numpy qiskit
```
