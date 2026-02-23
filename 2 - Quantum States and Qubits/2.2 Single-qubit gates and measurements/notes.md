# 2.2 Single-Qubit Gates and Measurements

## Key Concepts

### Quantum Gates
Quantum gates are **unitary operations** that transform qubit states. They are represented by unitary matrices (U†U = I).

### Common Single-Qubit Gates

#### Pauli Gates

| Gate | Matrix | Effect |
|------|--------|--------|
| **X** (NOT) | [[0,1],[1,0]] | Flips \|0⟩ ↔ \|1⟩ (bit flip) |
| **Y** | [[0,-i],[i,0]] | Bit flip + phase flip |
| **Z** | [[1,0],[0,-1]] | Phase flip (\|1⟩ → -\|1⟩) |

#### Other Important Gates

| Gate | Matrix | Effect |
|------|--------|--------|
| **H** (Hadamard) | [[1,1],[1,-1]]/√2 | Creates superposition |
| **S** (Phase) | [[1,0],[0,i]] | π/2 phase rotation |
| **T** | [[1,0],[0,e^(iπ/4)]] | π/4 phase rotation |
| **Rₓ(θ)** | Rotation around X-axis | Parameterized rotation |
| **Rᵧ(θ)** | Rotation around Y-axis | Parameterized rotation |
| **Rᵤ(θ)** | Rotation around Z-axis | Parameterized rotation |

### Measurement
- Measurement in quantum computing is done in the **computational basis** {|0⟩, |1⟩}
- For state |ψ⟩ = α|0⟩ + β|1⟩:
  - P(outcome = 0) = |α|²
  - P(outcome = 1) = |β|²
- Measurement is **irreversible** — it collapses the quantum state

### Key Properties of Quantum Gates
1. **Reversibility**: Every quantum gate has an inverse (unlike classical logic gates)
2. **Unitarity**: Gates preserve the total probability (|α|² + |β|² = 1)
3. **No Cloning**: You cannot copy an arbitrary quantum state (No-Cloning Theorem)

## My Notes
- The X gate is the quantum equivalent of a classical NOT gate
- H gate is the most important gate for creating superposition — you'll use it constantly
- Z gate does nothing visible to |0⟩ but flips the phase of |1⟩ — phase matters in interference!
- All single-qubit gates are rotations on the Bloch sphere
