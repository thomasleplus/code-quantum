# Code Quantum

A place to stash my quantum computing experiments

## [Hadamard Basic](Hadamard%20Basic.qasm)

This is the simplest quantum circuit: a single input quibit goes through an Hadamard gate. The output is a qubit which if measured has a 50/50 chance to be a 0 or 1.

See [https://en.wikipedia.org/wiki/Hadamard_transform#Quantum_computing_applications](https://en.wikipedia.org/wiki/Hadamard_transform#Quantum_computing_applications)
for more details.

## [Grover's Search](Grover's%20Search.qasm)

An implementation of Grover's quantum search algorithm using 5 qubits and 3 classical bits for measurement. Grover's algorithm provides a quadratic speedup for searching an unsorted database, finding a marked item in O(√N) time compared to O(N) classically.

The circuit demonstrates the key components of Grover's algorithm:
- Initialization with Hadamard gates to create superposition
- Oracle function that marks the target solution
- Diffusion operator for amplitude amplification
- Multiple iterations to increase the probability of measuring the correct answer

See [https://en.wikipedia.org/wiki/Grover%27s_algorithm](https://en.wikipedia.org/wiki/Grover%27s_algorithm) for more details.

## [Quantum 8-Ball](quantum_8ball.ipynb)

A quantum version of the Magic 8-Ball fortune teller implemented as a Jupyter notebook using Qiskit. This experiment uses 3 qubits in superposition to generate 8 equally likely outcomes (2³ = 8), each mapped to a different fortune-telling answer.

The notebook demonstrates:
- Creating quantum circuits with superposition using Hadamard gates
- Measuring quantum states and interpreting results
- Running circuits on both quantum simulators and real IBM quantum hardware
- The difference between true quantum randomness and classical pseudo-randomness

Perfect for understanding quantum uncertainty and getting started with Qiskit programming.
