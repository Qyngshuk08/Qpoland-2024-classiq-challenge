# Quantum Machine Learning: Variational Ansatz for Solving Linear Systems

## Overview

This repository implements a variational quantum algorithm to solve linear systems of equations, inspired by the methods proposed by Carlos Bravo-Prieto et al. The primary objective of this project is to create a robust, flexible, and optimized quantum program using the Classiq framework, which leverages quantum gates to design an effective variational ansatz. This solution is reimplemented to improve upon the original research, aiming for better efficiency and performance.

This work was developed as part of a hackathon project to demonstrate the potential of quantum computing in addressing problems that are traditionally challenging for classical systems, especially as the size of the system grows.

## Problem Description

Linear systems of equations are a fundamental part of many fields, including:

- **Physics** (e.g., solving differential equations)
- **Engineering** (e.g., circuit analysis)
- **Computer Science** (e.g., 3D transformations)
- **Data Science** (e.g., regression models)

However, as the size of the system grows, classical methods can become inefficient. Variational quantum algorithms offer a promising alternative by potentially speeding up the process using quantum machine learning techniques. This repository reimplements and improves a quantum algorithm to solve linear systems of equations by building a variational ansatz.

## Implementation Details

The variational ansatz is a parametric quantum circuit designed to minimize a cost function. It adjusts the parameters of quantum gates to achieve an optimal solution, making it well-suited for tasks like solving linear systems. In this repository, the ansatz is constructed using Classiq, a framework that facilitates the design and synthesis of complex quantum circuits.

