# Start Quantum

This is my personal learning repository for quantum computing. This is not a textbook, nor is it an attempt to be one. This is a set of things I've built, broken, fixed, and learned about along the way.

---

## About Me

I am a student who was interested in quantum computing and chose to learn it rather than just reading theories about it, I am not a person who listens to pages of theory and remembers it all That is just not how my brain is worked. I learn by doing, I make something, it doesn’t work, I see why, and then the Learning sticks.

This repo is essentially my notebook. Each folder in this repository is a subject that I have learned about by writing code, running circuits, and seeing what happens If this repository has helped you, that is great If not, at least it helped me.

---

## How I'm Learning

I use the QPIAI syllabus as a guide, but my process is more applied first.

Here is how that process looks:

1. I ask myself why this concept exists and what problem it solves, Without the "why," nothing else will stick.
2. I read enough theory to grasp the concept, not the math, just the concept.
3. I open a notebook and attempt to build the simplest version of it, Something small that I can actually run.
4. It breaks, I read the error message, go back to the theory, and fix it, Then I run it again. This is where the real learning is.
5. Once it is working, I attempt to break it on purpose to see what happens and what doesn't, This is how I learn the concepts.
6. I relate it back to what I already know, How does this new concept fit into the big picture? What can I combine it with?

I am not saying that theory & Math's, Physics is irrelevant It is not. But for me, making something and seeing it work is more educational than ten pages of math & Physics could ever be, The math & Physics makes sense after I see the thing work.

---

## Syllabus - Quantum (QPIAI)

This is the actual syllabus I am following. Each chapter maps to a folder in this repo.

### Chapter 1: Prerequisites for Quantum Computing
- 1.1 Essential Linear Algebra *(hands-on with NumPy & Qiskit)*
- 1.2 Basics of Quantum Mechanics *(theory-heavy, 10 deep-dive notebooks)*
- 1.3 General Lecture on Quantum Technology
- 1.4 Essential Computer Science

### Chapter 2: Quantum States and Qubits
- 2.1 Single-qubit states and superposition
- 2.2 Single-qubit gates and measurements
- 2.3 Two-qubit states, entanglement, and Bell's inequality
- 2.4 Two-qubit gates and observable
- 2.5 Multi-Qubit states (GHZ and W states)
- 2.6 Universal gates and quantum circuit model
- 2.7 Quantum adiabatic computation and the Ising model

### Chapter 3: Quantum Algorithms
- 3.1 Quantum Circuits
- 3.2 Deutsch-Jozsa Algorithm
- 3.3 Bernstein-Vazirani Algorithm
- 3.4 Quantum Fourier Transform
- 3.5 Quantum Factoring: Shor's Algorithm
- 3.6 Quantum Database Search: Grover's Algorithm
- 3.7 Circuit Simulations on QpiAI Explorer Software

### Chapter 4: Quantum Protocols
- 4.1 Quantum Teleportation
- 4.2 Superdense Coding
- 4.3 Simulation of QpiAI Explorer Software
- 4.4 Quantum Cryptography and Key Distribution
- 4.5 Quantum Communication and Networks
- 4.6 Guest Lecture - QKD, Communications

### Chapter 5: Quantum Hardware: Superconducting Qubits
- 5.1 Introduction to physical qubits
- 5.2 Circuit Quantum Electrodynamics
- 5.3 Transmon and Coupled Qubits
- 5.4 Control and Readout

### Chapter 6: NISQ Devices
- 6.1 Noise Models
- 6.2 Quantum Error Mitigation
- 6.3 Quantum Volume and Performance Metrics
- 6.4 Hybrid Quantum-Classical Computing

### Chapter 7: Quantum Algorithms for Applications
- 7.1 Quantum Inspired Computing
- 7.2 Variational Quantum Algorithms
- 7.3 Variational Quantum Eigensolver
- 7.4 Quantum Approximate Optimization Algorithm
- 7.5 Quantum Machine Learning: QNNs
- 7.6 HHL Algorithm for Solving Linear Systems

### Chapter 8: Quantum Hardware: Semiconducting Qubits
- 8.1 Introduction to physical qubits
- 8.2 Spin Physics and Quantum Dots
- 8.3 Control and Readout
- 8.4 Scalability

Each folder has notes, and experiments as I work through.

## Current Progress

- ✅ **1.1 Essential Linear Algebra** — 8 hands-on notebooks (complex numbers → tensor products → Bell state capstone)
- ✅ **1.2 Basics of Quantum Mechanics** — 10 theory-heavy notebooks (classical physics → quantum computing bridge)
- 🔲 **1.3 onwards** — Coming soon

---

## My Views on Quantum Computing

Quantum computing is not magic, and it is not going to replace Every Technology, It is a paradigm shift in the way that we process information. Classical computers process information in bits, zeros, and ones. Quantum computers process information in qubits, which can exist in a state of superposition and entangle with each other. This provides a whole different realm of computational power for certain types of problems.

The truth is that we are still very early, The hardware is noisy, The qubits are fragile, and we don’t have a quantum computer that can do everything a classical computer can do, But the progress is real, and the potential is huge.

I think it is fascinating because it is the intersection of physics, math, and computer science. It is not just engineering it is science that we are still learning.

---

## Quantum vs Classical Computing

Classical computers are amazing at what they do, they perform everyday tasks, host servers, train neural networks, and process data for most problems, a classical computer is the best tool for the job.

A quantum computer is not better at all things. It is better at some specific things, some problems which classical computers cannot solve, such as breaking down large complex numbers, simulating molecules, and searching unstructured data, have quantum algorithms that solve them exponentially faster than the best known classical methods.

In my opinion, quantum is not a replacement for classical it is an extension Like a GPU is an extension of a CPU. The future is probably a hybrid model where classical computers do most of the work and quantum processors are used for the parts where they have a real advantage.

---

## Quantum vs AI, ML, Data Science, and Other Fields

This is a question "Why quantum when AI is booming?"

Here is my Views, AI and machine learning are powerful, but they are fundamentally running on classical hardwares they are optimization machines that learn patterns from data, Quantum computing could eventually accelerate parts of that process, things like optimization, sampling, and linear algebra operations that sit at the core of classical ML & AI.

But quantum is not competing with AI they are different layers of the stack AI is about algorithms and data, Quantum is about the hardware and computational model, Quantum machine learning is already a growing field where people are exploring what happens when you run ML algorithms on quantum circuits.

Data science, software engineering, and other tech areas are all founded on classical computing, Quantum does not replace any of these areas it simply provides a new tool for the toolbox and to be honest understanding classical computing in depth will make you a better in quantum computing, because you have to understand what you are comparing to.

I decided to learn quantum not because I believe it to be superior to AI or any other area, but simply because it is a difficult problem that very few people are trying to solve, and I would like to be one of the people who actually understands it when it becomes mainstream.

---

## My Goals

- Develop a strong foundation in quantum computing from scratch.
- Master the entire QPIAI curriculum with hands-on examples for each key concept.
- Familiarize myself with coding and debugging quantum circuits.
- Learn quantum hardware to the point where I understand what is actually going on at the physical level.
- Participate in open-source quantum computing projects once I have the skills.
- Work on practical quantum computing applications, whether it is optimization, cryptography, or simulation.

---

## Why This Repo is Public

I’m doing this because I think learning in public keeps you honest it forces you to structure your thoughts, write things down correctly, If someone happens to read this and finds it helpful, that’s great but the main purpose of this is for me to keep track of my own progress.

---

If you’re like me and are just starting out with quantum computing & Information Theory, my only advice is to just start, Don’t wait until you understand the math & Physics, Don’t wait until you feel ready. Pick a topic, open a notebook, and start Reading, You’ll figure it out as you go.
