# 2.3 Two-Qubit States, Entanglement, and Bell's Inequality

## Key Concepts

### Two-Qubit States
A two-qubit system lives in a 4-dimensional Hilbert space with basis states:
```
|00⟩, |01⟩, |10⟩, |11⟩
```

A general two-qubit state:
```
|ψ⟩ = α|00⟩ + β|01⟩ + γ|10⟩ + δ|11⟩
```
where |α|² + |β|² + |γ|² + |δ|² = 1

### Product States vs Entangled States
- **Product state**: Can be written as a tensor product of two single-qubit states
  - Example: |+⟩ ⊗ |0⟩ = (|00⟩ + |10⟩)/√2
- **Entangled state**: CANNOT be written as a tensor product
  - Example: (|00⟩ + |11⟩)/√2 — the Bell state |Φ⁺⟩

### Bell States (Maximally Entangled)
The four Bell states form a complete basis for the two-qubit system:

| Bell State | Expression |
|-----------|------------|
| \|Φ⁺⟩ | (|00⟩ + \|11⟩) / √2 |
| \|Φ⁻⟩ | (\|00⟩ - \|11⟩) / √2 |
| \|Ψ⁺⟩ | (\|01⟩ + \|10⟩) / √2 |
| \|Ψ⁻⟩ | (\|01⟩ - \|10⟩) / √2 |

### Creating a Bell State (Bell Circuit)
```
1. Start with |00⟩
2. Apply H to qubit 0 → (|0⟩ + |1⟩)/√2 ⊗ |0⟩
3. Apply CNOT (control=0, target=1) → (|00⟩ + |11⟩)/√2 = |Φ⁺⟩
```

### Entanglement
- When two qubits are entangled, measuring one **instantly** determines the state of the other
- This is NOT faster-than-light communication — you can't control the measurement outcome
- Entanglement is a **resource** used in quantum computing, teleportation, and cryptography

### Bell's Inequality (CHSH Inequality)
- **Classical bound**: S ≤ 2
- **Quantum bound**: S ≤ 2√2 ≈ 2.83
- Quantum mechanics violates Bell's inequality, proving that entanglement is a real physical phenomenon, not just a classical correlation

## My Notes
- Entanglement is THE key resource that makes quantum computing powerful
- Bell states are the simplest entangled states — understand these deeply before moving on
- The H + CNOT circuit is the most fundamental pattern in quantum computing
- Bell's inequality violation was experimentally confirmed — this is settled physics
