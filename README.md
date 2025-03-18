<h1>Quantum Key Distribution (QKD) - BB84 and B92 Protocols </h1>
<Br>
<h2>Overview </h2>
<Br>
This repository implements Quantum Key Distribution (QKD) using the BB84 and B92 protocols with Qiskit. QKD is a cryptographic technique that enables two parties to share encryption keys securely using quantum mechanics, ensuring resilience against eavesdropping.
<Br>
A report is attached in the repository which contains all the prior knowledge and in-depth analysis of Quantum Key Distribution Protocols.
<h2>BB84 Protocol</h2>
<Br>
-Uses two mutually unbiased bases (rectilinear and diagonal) for encoding qubits.
<Br>
Alice randomly prepares qubits and sends them to Bob, who measures them with randomly chosen bases.
<Br>
After transmission, Alice and Bob publicly compare bases and discard mismatched measurements.
<Br>
The remaining bits form a shared secret key.
<Br>
<h2>B92 Protocol</h2>
<Br>
Uses two non-orthogonal states for secure key distribution.
<Br>
Bob can only detect a qubit in certain cases, enhancing security.
<Br>
The protocol reduces transmission redundancy while maintaining security.
<Br>
<h2>Installation</h2>
<Br>
<h3>Prerequisites</h3>
<Br>
Python 3.x
<Br>
Jupyter Notebook
<Br>
Qiskit (Quantum computing framework)
<Br>
<h2>Setup</h2>
<Br>

Install dependencies:
<Br>
**pip install qiskit numpy matplotlib**
<Br>
Open the Jupyter Notebook:
<Br>
**jupyter notebook "QKD BB84 and B92 protocols code.ipynb"**
<Br>
Usage
<Br>
Run the notebook step by step to execute BB84 and B92 protocols.
<Br>
The code simulates quantum key generation using Qiskit’s Aer simulator.
<Br>
After execution, Alice and Bob will have a shared secret key, with eavesdropping attempts detectable via quantum properties.
<Br>
<h2>Results</h2>
<Br>
Simulated key exchange between Alice and Bob.
<Br>
Detection of eavesdroppers using quantum state collapse.
<Br>
Visualization of quantum states using Bloch spheres and histograms.
<Br>
<h2>Future Scope</h2>
<Br>
Implement error correction and privacy amplification to improve practical security.
<Br>
Extend QKD simulations to real quantum hardware instead of simulators.
<Br>
Explore integration with post-quantum cryptographic algorithms.
<Br>
<h2>Acknowledgments</h2>
<Br>
This project uses Qiskit, an open-source quantum computing framework developed by IBM. The quantum computing community is to be credited with contributing to QKD research.
