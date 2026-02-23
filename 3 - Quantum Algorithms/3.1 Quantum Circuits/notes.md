# 3.1 Quantum Circuits

## Key Concepts

### What is a Quantum Circuit?
A quantum circuit is a model for quantum computation where:
- **Qubits** are represented as horizontal lines (wires)
- **Gates** are applied to qubits in sequence (left to right)
- **Measurements** are typically placed at the end

### Circuit Structure
```
|0⟩ ──[H]──●──[M]→ c₀
            │
|0⟩ ────────⊕──[M]→ c₁
```
This creates a Bell state and measures both qubits.

### Circuit Elements

| Symbol | Name | Description |
|--------|------|-------------|
| ─[H]─ | Hadamard | Creates superposition |
| ─[X]─ | Pauli-X | Bit flip (NOT gate) |
| ─●─ / ─⊕─ | CNOT | Controlled-NOT (2-qubit gate) |
| ─[M]→ | Measurement | Collapses qubit to classical bit |
| ═══ | Classical wire | Carries measurement results |

### Circuit Depth and Width
- **Width**: Number of qubits in the circuit
- **Depth**: Number of time steps (layers of gates that can run in parallel)
- Shallower circuits = less error accumulation on real hardware

### Reversibility
- All quantum gates are reversible (unitary)
- To "undo" a gate, apply its inverse (conjugate transpose)
- Measurement is the ONLY irreversible operation

### Circuit Identities
Some useful equivalences:
- HXH = Z (conjugation)
- HZH = X
- XX = I (applying X twice = identity)
- HH = I (applying H twice = identity)

## My Notes
- Think of quantum circuits like classical circuits but read left to right
- Keep circuits shallow — every gate adds noise on real quantum hardware
- The CNOT gate is the essential two-qubit gate — it's how we create entanglement
- Circuit diagrams are the "language" of quantum computing, learn to read them fluently
