# Quantum Machine Learning - Spring 2024 🌌  
[![Made With](https://img.shields.io/badge/Made%20with-Python%2C%20Qiskit%2C%20PyTorch-blue)]()  
[![University](https://img.shields.io/badge/University-University%20of%20Tehran-red)]()

---

## 📚 Table of Contents  
- [Course Description](#-course-description)  
- [Problem Sets](#%EF%B8%8F-problem-sets)  
- [Bonus Project](#-bonus-project)  
- [Getting Started](#-getting-started)  
- [How to use](#-How-to-use)
---

## 🎓 Course Description  
**Advanced Topics in Quantum Machine Learning**  
*University of Tehran - Spring 2024*  

This repository contains:  
- 📝 Theoretical problem sets (quantum computing + ML)  
- 💻 Jupyter notebooks with Qiskit implementations  
- 🏆 Bonus project on hybrid quantum-classical NNs  

Key topics covered:  
✅ Quantum state manipulation  
✅ Deutsch-Josza algorithm  
✅ SVM and logistic regression  
✅ Quantum circuit simulations with Qiskit

---

## ⚛️ Problem Sets  

### Quantum Computing  
**Core Concepts:**  
```python
# Example quantum circuit
qc = QuantumCircuit(2)
qc.h(0)  # Hadamard gate
qc.cx(0,1)  # CNOT gate
```
- State normalization conditions
- Pauli operator transformations
- Density matrix calculations
### Machine Learning
#### Key Problems:
| Problem    | Description                                 |
|-------------|---------------------------------------------|
| SVM        | Linear decision boundary for 2D data        |
| NN         | 2-layer network with sigmoid activation     |
| Regression | MSE optimization for y=2x                   |

## 🏆 Bonus Project: Hybrid Quantum-Classical Neural Network

**File:** [`Quantum_NN.ipynb`](./[Quantum_NN.ipynb](https://github.com/ARSH2001/Quantum/blob/main/HW01-Bonus.ipynb))

### 🔧 Implements:
```
### 📦 Requirements: 
```bash
  pip install qiskit matplotlib
```

### 🛠 Getting Started
1. Clone repository:
   ```bash
       git clone https://github.com/ARSH2001/Quantum.git
       cd Quantum
2. Install dependencies (see Requirements).
3. Run the Jupyter notebooks (e.g., HW01-Bonus.ipynb) to explore the implementations.
