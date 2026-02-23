# 4.1 Quantum Teleportation

## Key Concepts

### What is Quantum Teleportation?
Quantum teleportation is a protocol that transfers a quantum state from one qubit to another using:
1. A shared **entangled pair** (Bell state)
2. **Two classical bits** of communication
3. NO physical transfer of the qubit itself

### The Protocol Step-by-Step

**Setup**: Alice has qubit |ψ⟩ = α|0⟩ + β|1⟩ that she wants to send to Bob.
Alice and Bob share an entangled Bell pair |Φ⁺⟩ = (|00⟩ + |11⟩)/√2.

**Step 1**: Alice applies CNOT (her qubit as control, her half of Bell pair as target)

**Step 2**: Alice applies Hadamard to her original qubit

**Step 3**: Alice measures both her qubits, getting two classical bits (b₁, b₂)

**Step 4**: Alice sends the two classical bits to Bob (over a regular channel)

**Step 5**: Bob applies corrections based on Alice's measurement results:
- If b₂ = 1: Apply X gate
- If b₁ = 1: Apply Z gate

**Result**: Bob's qubit is now in state |ψ⟩ = α|0⟩ + β|1⟩

### The Circuit
```
|ψ⟩   ──●──[H]──[M]──────────────── b₁
         │                            
|0⟩ ─[H]─●──⊕──────[M]──────────── b₂
          │                          
|0⟩ ─────⊕──────────────[X^b₂][Z^b₁]── |ψ⟩
```

### Why Teleportation Doesn't Violate Physics
- It does NOT transfer information faster than light
- Alice must send 2 classical bits to Bob (limited by speed of light)
- Without those classical bits, Bob's qubit looks completely random
- The original qubit |ψ⟩ is destroyed during the process (No-Cloning Theorem is preserved)

### Applications
- **Quantum networks**: Moving quantum states between distant nodes
- **Quantum error correction**: Transferring logical qubit states
- **Distributed quantum computing**: Connecting separate quantum processors

## My Notes
- Teleportation doesn't "move" anything — it reconstructs the state at a new location
- The No-Cloning Theorem is why Alice's original state must be destroyed
- This was experimentally demonstrated — it's real physics, not just theory
- Understanding teleportation deeply is essential for quantum networking and communication
