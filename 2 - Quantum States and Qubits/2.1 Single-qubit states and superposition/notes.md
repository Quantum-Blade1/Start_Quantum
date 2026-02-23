# 2.1 Single-Qubit States and Superposition

## Key Concepts

### What is a Qubit?
A **qubit** (quantum bit) is the fundamental unit of quantum information. Unlike a classical bit that can only be 0 or 1, a qubit can exist in a **superposition** of both states simultaneously.

Mathematically, a qubit state is represented as:

```
|ψ⟩ = α|0⟩ + β|1⟩
```

where α and β are complex numbers called **probability amplitudes**, and they satisfy:

```
|α|² + |β|² = 1
```

### The Bloch Sphere
The Bloch sphere is a geometric representation of a single qubit state. Any pure qubit state can be written as:

```
|ψ⟩ = cos(θ/2)|0⟩ + e^(iφ) sin(θ/2)|1⟩
```

- **θ** (theta): polar angle from the z-axis (0 to π)
- **φ** (phi): azimuthal angle in the x-y plane (0 to 2π)

### Important Single-Qubit States

| State | Notation | Vector | Location on Bloch Sphere |
|-------|----------|--------|--------------------------|
| Zero  | \|0⟩     | [1, 0] | North pole               |
| One   | \|1⟩     | [0, 1] | South pole               |
| Plus  | \|+⟩     | [1/√2, 1/√2] | +X axis            |
| Minus | \|-⟩     | [1/√2, -1/√2] | -X axis           |

### Superposition
Superposition means a qubit exists in a combination of |0⟩ and |1⟩ until it is **measured**. Upon measurement:
- The qubit **collapses** to either |0⟩ or |1⟩
- Probability of getting |0⟩ = |α|²
- Probability of getting |1⟩ = |β|²

### The Hadamard Gate
The **Hadamard gate (H)** is the most common way to create superposition:

```
H|0⟩ = |+⟩ = (|0⟩ + |1⟩) / √2
H|1⟩ = |-⟩ = (|0⟩ - |1⟩) / √2
```

This gives a 50/50 chance of measuring 0 or 1.

## My Notes
- Superposition is NOT the qubit being "both 0 and 1 at the same time" — it's more accurate to say the qubit is in a state that has some probability of being measured as 0 and some probability of being measured as 1.
- The Bloch sphere is only useful for single qubits. Multi-qubit systems need different representations.
- Measurement destroys superposition — this is a fundamental aspect of quantum mechanics, not a limitation of our technology.
