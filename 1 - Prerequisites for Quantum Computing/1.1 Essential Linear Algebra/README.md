# 1.1 Essential Linear Algebra

> "Linear algebra is the language of quantum mechanics."

This section provides a **rigorous, theory-first foundation** for quantum computing. Unlike other tutorials that hand-wave the math, we build it from the ground up. 

Each notebook is designed to be read like a chapter in a book. We explain the *why*, not just the *how*. We use analogies, geometric intuition, and Python code to make the abstract concrete.

## The Curriculum

| # | Topic | What You Will Learn |
|---|-------|---------------------|
| **01** | [Complex Numbers](01_complex_numbers.ipynb) | Why nature uses complex numbers. Rotations, Euler's Formula, and the "Circle of Life" for qubits. |
| **02** | [Vector Spaces](02_vector_spaces.ipynb) | The "Stage" of QM. What dimension really means. The exponential explosion of state space. |
| **03** | [Inner Products](03_inner_products_norms.ipynb) | The geometry of states. How to measure "overlap" and "angle" in 50 dimensions. Orthogonality. |
| **04** | [Dirac Notation](04_dirac_notation.ipynb) | The language of physics. Bras $\langle \phi|$, Kets $|\psi\rangle$, and the "sandwich" product. |
| **05** | [Matrices](05_matrices_transformations.ipynb) | Operators as "Machines". Linearity. Why almost all quantum ops must be reversible. |
| **06** | [Matrix Operations](06_matrix_operations.ipynb) | The Algebra. Why $A \times B \neq B \times A$. The Commutator and the Uncertainty Principle. |
| **07** | [Special Matrices](07_special_matrices.ipynb) | **Unitary** (Gates) vs **Hermitian** (Observables). The rules of the game. |
| **08** | [Eigenvalues](08_eigenvalues_eigenvectors.ipynb) | The mystery of measurement. Why we only see discrete outcomes. Spectral Decomposition. |
| **09** | [Exponentials](09_matrix_exponentials.ipynb) | How states evolve in time. Solving Schrödinger's equation with $e^{-iHt}$. |
| **10** | [Tensor Products](10_tensor_products.ipynb) | Combining systems. The math of **Entanglement**. Breaking the product state. |

## Prerequisites
- **Python**: Basic functions and variables.
- **Math**: High school algebra. We teach the rest.

## How to Use This Section
1. Read the notebooks in order.
2. Don't skip the text. The code is simple, but the concepts are deep.
3. When you see a formula, stop and visualize it.
4. Run the code cells to confirm your intuition.
