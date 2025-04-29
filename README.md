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
✅ Quantum neural networks  
✅ SVM and logistic regression  

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
```python
from qiskit import QuantumCircuit
from qiskit.circuit import Parameter
import torch

class QuantumLayer(torch.nn.Module):
    def __init__(self, n_qubits=2):
        super().__init__()
        self.circuit = QuantumCircuit(n_qubits)
        self.theta = Parameter('θ')
        # Add parameterized gates
        self.circuit.ry(self.theta, 0)
        self.circuit.cx(0, 1)
```
### 📦 Requirements: 
```bash
  pip install qiskit==0.45.0 pytorch==2.0.1 matplotlib==3.7.0
```
### 🎯 Key Features:
  - Quantum circuit as a PyTorch layer
  - Parameterized quantum gates (RY, CNOT)
  - Gradient-based optimization

### 🛠 Getting Started
1. Clone repository:
   ```bash
   git clone https://github.com/ARSH2001/UT-Quantum-ML.git
   cd UT-Quantum-ML
