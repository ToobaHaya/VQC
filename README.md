# Variational Quantum Classifier (VQC) for Binary Data

This repository implements a **Variational Quantum Classifier (VQC)** for binary classification using [Qiskit Machine Learning](https://qiskit.org/documentation/machine-learning/).  
It allows training and testing on **random binary data** or user-uploaded CSV files, using **quantum feature maps** and **parameterized ansatz circuits**.

---

## 🚀 Features
- Uses **ZZFeatureMap** to encode classical data into quantum states  
- Parameterized **TwoLocal ansatz** for quantum circuit optimization  
- Optimized with **COBYLA** classical optimizer  
- Can run on:
  - **IBM Quantum backends** via IBM Runtime  
  - Local **AerSimulator**  
- Computes:
  - **Train and test accuracy**
  - **Classification report**
- Produces visualizations:
  - Accuracy bar chart
- Supports user-uploaded CSV data or random binary data generation

---

## 📦 Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/vqc-binary-classifier.git
cd vqc-binary-classifier
pip install qiskit qiskit-aer qiskit-ibm-runtime qiskit-machine-learning matplotlib pandas scikit-learn
