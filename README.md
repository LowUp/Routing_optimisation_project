# Wireless Sensor Network Routing Path Optimization

## Overview

This repository contains the research and implementation of multiple optimization strategies for routing paths in wireless sensor networks. The main goal is to maximize end-to-end transmission rates while minimizing latency.

## Contents

The PDF file [Group23_assessment.pdf](./Group23_assessment.pdf) in this repository covers the following topics:

1. **Problem Statement**: Detailed description of the multi-objective optimization problem in wireless sensor networks.

2. **Data Visualization**: Network map showing sensor nodes and base stations.

3. **Objective Function**: Explanation of the Weighted Sum Method (WSM) used to combine multiple objectives.

4. **Optimization Algorithms**:
   - Discrete Genetic Algorithm (DGA)
   - Ant Colony Optimization (ACO)
   - Hybrid approach (Genetic Algorithm + Simulated Annealing)

5. **Implementation Details**:
   - Initialization
   - Fitness calculation
   - Selection methods
   - Crossover and mutation (for genetic algorithms)
   - Pheromone updates (for ACO)
   - Temperature and cooling schedule (for Simulated Annealing)

6. **Results and Analysis**:
   - Path visualizations
   - Performance evaluations
   - Convergence curves
   - Runtime comparisons
   - Results comparisons for multiple test cases

7. **Discussion**: In-depth analysis of each algorithm's performance and overall results.

8. **Conclusion and Future Work**: Summary of findings and proposed improvements for future research.

## Key Features

- Multi-objective optimization balancing transmission rate and latency
- Implementation of three distinct optimization algorithms
- Comprehensive performance comparisons and visualizations
- Detailed code snippets and explanations

## Getting Started

To use the code and reproduce the results:
1. `git clone https://github.com/LowUp/Routing_optimisation_project.git`
2. `pip install -r requirements.txt`
3. Run the provided Python scripts to execute the optimization algorithms (Use Jupyter Notebook for better visibility)
