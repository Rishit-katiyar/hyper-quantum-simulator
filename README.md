# Hyper Quantum Simulator 🌌

Welcome to the Hyper Quantum Simulator repository! This project aims to provide a hyper-complex quantum computing simulator implemented in Haskell, featuring advanced abstractions, optimizations, and various quantum gates and operations.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Quantum computing is a cutting-edge field that promises revolutionary advancements in computation, cryptography, and more. This simulator allows you to experiment with quantum algorithms, gates, and circuits in a hyper-complex environment, providing insights into the behavior of quantum systems.

## Features

- Implemented in Haskell for clarity, expressiveness, and performance.
- Supports a wide range of quantum gates, including Pauli-X, Pauli-Y, Pauli-Z, and Hadamard.
- Flexible quantum circuit representation for composing complex algorithms.
- Operations for entangling qubits, measuring qubits, and more.
- Efficient state representation using Haskell's Map data structure.

## Installation

To use the Hyper Quantum Simulator, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rishit-katiyar/hyper-quantum-simulator.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd hyper-quantum-simulator
   ```

3. **Install Haskell Stack (if not already installed):**
   Follow the instructions on the [Haskell Stack website](https://docs.haskellstack.org/en/stable/README/) to install Stack for your platform.

4. **Build the project:**
   ```bash
   stack build
   ```

## Usage

Once the project is built, you can run the quantum simulator using Haskell's Stack tool. Here's how you can run the simulator:

1. **Run the simulator:**
   ```bash
   stack run hyper_quantum_simulator.hs
   ```

2. **Experiment with quantum circuits:**
   Modify the `hyper_quantum_simulator.hs` file to define your quantum circuits and operations. You can create custom circuits, apply various quantum gates, entangle qubits, measure qubits, and more.

3. **Explore the results:**
   The simulator will output the final state of the quantum system after applying the specified quantum circuit. Analyze the results to understand the behavior of your quantum algorithms and circuits.

## How It Works

The Hyper Quantum Simulator operates by representing quantum states using qubits, which are complex vectors. Quantum gates are then applied to these qubits to perform operations such as entanglement, measurement, and state manipulation. The simulator maintains a quantum state as a Map data structure, allowing for efficient representation and manipulation of quantum systems.

### Quantum Gates
The simulator supports a variety of quantum gates, including:
- Pauli-X gate
- Pauli-Y gate
- Pauli-Z gate
- Hadamard gate
- Custom gates can also be implemented by extending the QuantumGate typeclass.

### Quantum Circuits
Quantum circuits are composed of sequences of quantum gates applied to qubits. The simulator provides a QuantumCircuit data type for representing quantum circuits, allowing users to define complex algorithms and experiments.

### Quantum Operations
In addition to quantum gates and circuits, the simulator supports quantum operations such as:
- Entangling qubits
- Measuring qubits and collapsing them to definite states
- Applying custom transformations to quantum states

## Contributing

Contributions to the Hyper Quantum Simulator project are welcome! Whether you're interested in adding new features, optimizing performance, fixing bugs, or improving documentation, your contributions are valuable. Here's how you can contribute:

1. **Fork the repository:** Click the "Fork" button on GitHub to create your own copy of the repository.
2. **Make changes:** Make your changes to the codebase, documentation, or any other relevant files.
3. **Submit a pull request:** Once you're happy with your changes, submit a pull request to merge your changes into the main repository. Be sure to provide a clear description of your changes and any relevant context.

## License

This project is licensed under the GNU General Public License v3.0 (GNU GPLv3). See the [LICENSE](LICENSE) file for details.
