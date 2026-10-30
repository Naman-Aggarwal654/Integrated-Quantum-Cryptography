# Integrated Quantum Cryptography for Secure Data and Authentication

## Project Overview

This project presents a simulation-based implementation of selected mechanisms from an integrated quantum cryptography protocol for secure bidirectional data transmission and authentication.

The implementation is based on the research paper:

**Privacy-Preserving Bidirectional Data Transmission of Smart Grid Via Semi-Quantum Computation: On Mutual Identity and Message Authentication**

**Authors:** Xiaoping Lou et al.  
**Journal:** IEEE Transactions on Dependable and Secure Computing, 2025.

## Project Repository

GitHub Repository: [Integrated Quantum Cryptography](https://github.com/Naman-Aggarwal654/Integrated-Quantum-Cryptography)

## Project Objectives

- Study quantum state preparation and Bell states.
- Explore mutual identity authentication.
- Simulate bidirectional quantum data transmission.
- Implement XOR-based message authentication.
- Evaluate selected protocol mechanisms using quantum circuit simulation.

## Repository Structure

```text
Integrated-Quantum-Cryptography/
│
├── src/
│   └── bdt.ipynb
│
├── report/
│
├── presentation/
│
├── results/
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

## Technologies Used

- Python 3.12
- Qiskit
- Qiskit Aer
- NumPy
- Matplotlib
- Jupyter Notebook

## Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
cd Integrated-Quantum-Cryptography
```

Replace `YOUR_REPOSITORY_URL` with the URL of this GitHub repository.

### 2. Create a virtual environment

```bash
python -m venv quantum_env
```

Activate it on Windows:

```bash
quantum_env\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
pip install notebook
jupyter notebook
```

Open `src/bdt.ipynb` and execute the notebook cells in order.

## Implementation Overview

The notebook covers the following stages:

1. Quantum state preparation.
2. Decoy-state generation and eavesdropping checks.
3. Mutual identity authentication.
4. Semi-quantum duplex communication.
5. Mutual message authentication using XOR operations.

A separate BB84-style intercept-and-resend experiment is also included as an additional benchmark.

## Simulation Environment

The project uses Qiskit Aer for ideal quantum circuit simulation and includes selected noisy simulation experiments.

**Note:** The implementation contains simplified simulation components. The project report documents the assumptions, implementation scope and limitations. The simulation results should not be interpreted as a formal proof of protocol security.

## Project Materials

- **Source code:** `src/`
- **Project report:** `report/`
- **Presentation:** `presentation/`
- **Simulation results:** `results/`

## Research Reference

Lou, X., et al. (2025). *Privacy-Preserving Bidirectional Data Transmission of Smart Grid Via Semi-Quantum Computation: On Mutual Identity and Message Authentication*. IEEE Transactions on Dependable and Secure Computing.

DOI: https://doi.org/10.1109/TDSC.2025.3568707
