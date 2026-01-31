# QAOA for Max-Cut Optimization

## Project Overview
This project focuses on implementing the Quantum Approximate Optimization Algorithm (QAOA) to solve small Max-Cut problems using Qiskit, and benchmarking its performance against classical optimization methods. The goal is to analyze solution quality, convergence behavior, and practical limitations of near-term quantum optimization approaches.

## Objectives
- Implement QAOA on toy graph instances.
- Compare quantum solutions with classical methods such as brute-force Max-Cut.
- Evaluate performance metrics including solution quality, convergence, and scalability limitations.

## Key Concepts
- **Max-Cut Problem**: A combinatorial optimization problem where the goal is to partition the nodes of a graph into two sets such that the number of edges between the sets is maximized.
- **QAOA**: A hybrid quantum-classical algorithm that approximates solutions to combinatorial optimization problems by encoding them into a quantum circuit and iteratively optimizing parameters.
- **Classical Benchmarking**: Comparing QAOA results to classical algorithms (like brute-force) to assess solution quality and convergence efficiency.

## Methodology
1. **Graph Preparation**: Toy graphs of 4–6 nodes are created for testing.
2. **Classical Solution**: Brute-force enumeration is used to find exact Max-Cut values.
3. **QAOA Implementation**: QAOA circuits are built using Qiskit, with variational parameters optimized to approximate the Max-Cut solution.
4. **Performance Analysis**: Solution quality, convergence behavior, and limitations arising from problem size and parameter selection are analyzed.

## Tools and Libraries
- **Qiskit** for quantum circuit simulation.
- **NetworkX** for graph representation.
- **Matplotlib** and **NumPy** for analysis and visualization.

## Summary
This project demonstrates the potential and limitations of near-term quantum optimization algorithms on small-scale problems. It provides insights into how QAOA can be benchmarked against classical methods, and highlights practical considerations for implementing quantum algorithms in real-world optimization tasks.
