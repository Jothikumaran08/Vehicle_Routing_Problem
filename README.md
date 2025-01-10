# Vehicle_Routing_Problem
Vehicle Routing Problem (VRP) Solution using Genetic Algorithms This repository provides an advanced implementation of the Vehicle Routing Problem (VRP) using genetic algorithms. It includes features like custom fitness evaluation, mutation, crossover, and selection operations, along with visualizations for optimized routes and workload balance.

# Vehicle Routing Problem (VRP) using Genetic Algorithms

## Overview
This project tackles the **Vehicle Routing Problem (VRP)**, optimizing routes for a fleet of vehicles to minimize total travel distance and balance workload among vehicles. It employs **genetic algorithms** for efficient computation and features advanced visualizations for the results.

## Features
- **Custom Genetic Operators**:
  - **Fitness Evaluation**: Minimizes total distance and balances workload.
  - **Selection**: Tournament selection for evolutionary pressure.
  - **Crossover**: Options include partially matched crossover (PMX) or ordered crossover.
  - **Mutation**: Shuffle mutation for diverse solutions.
- **Visualization**:
  - Optimal routes for vehicles.
  - Workload distribution across vehicles.
- **Statistical Insights**:
  - Tracks average and minimum fitness during evolution.

## Installation
Install the required libraries with:
```bash
pip install matplotlib deap

How It Works
Data Generation:
Random locations for customer sites and a central depot.
Fitness Evaluation:
Computes the total distance and workload balance (standard deviation).
Evolutionary Operations:
Selection, crossover, and mutation refine the population iteratively.
Visualization:
Generates plots for routes and workload balance.
Usage
Run the notebook Vehicle_Routing_Problem.ipynb in a Python environment like Jupyter Notebook or directly as a script. Customize parameters like:

num_locations: Number of customer sites.
num_vehicles: Number of available vehicles.
population_size: Size of the genetic algorithm's population.
Example Outputs
Optimized Routes: Displays routes with distances minimized.
Workload Balance: Bar chart showing balanced workload across vehicles.
Libraries Used
Matplotlib: For visualizing results.
DEAP: For implementing genetic algorithms.
NumPy: For numerical computations.
Key Results
Generates optimized solutions for the VRP.
Highlights balanced workload and minimized total travel distance.
Provides clear visual interpretations of results.
