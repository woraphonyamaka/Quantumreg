# Quantum-optimization Linear Regression in R
_QUBO → Ising → QAOA (Pure-R, QuantumOps optional, Qiskit optional)_

> Discretized linear regression solved via a quantum-inspired pipeline: encode least squares as a QUBO, map to an Ising Hamiltonian, and minimize using a Variational Quantum Approximate Optimization Algorithm (QAOA). Comes with a **pure-R** QAOA simulator (no Python needed), plus optional backends (**QuantumOps** in R, **Qiskit** via reticulate).

---

## ✨ Features
- **Pure-R QAOA simulator** using `Matrix` + `expm` (no external runtimes)
- Discretized coefficients via **fixed-point bit encoding**
- QUBO builder for ridge least squares; **Ising** mapping
- OLS baseline and utilities (standardization, MSE)
- Optional: **QuantumOps** backend (R) for QAOA
- Optional: **Qiskit** backend (Python) for QAOA (with pinned versions)

---

## 🗂️ Repository Layout
