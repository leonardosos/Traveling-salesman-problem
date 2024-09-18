# Problem with Time Windows (TSPTW) Solver

This project provides a solver for the Traveling Salesman Problem with Time Windows (TSPTW). The main goal is to find a minimal-cost tour that visits a set of customers exactly once within their designated time windows, starting and ending at a depot.

## Features

- **Optimal Solution Using PuLP:** The project first solves the TSPTW using PuLP, a Python library for linear programming. It provides an optimal solution given the constraints of the problem.

- **Heuristic Approaches:** Two heuristic methods are implemented:
  - **Pure Heuristic:** A simple heuristic that prioritizes visits based on the closing time of customer time windows.
  - **A* Enhanced Heuristic:** An advanced heuristic that uses the A* algorithm to further refine the route and improve over the pure heuristic approach.

- **Dataset Generation:** The project includes functionality to generate random datasets to simulate TSPTW scenarios, including time windows and cost matrices.

## Conclusion

This project showcases different approaches to solving the TSPTW, each with its own benefits and limitations. The optimal solution provided by PuLP is highly accurate but computationally demanding, making it suitable for smaller datasets. On the other hand, the heuristic methods offer quicker solutions that are more feasible for larger datasets, albeit with slightly reduced accuracy. This balance between precision and efficiency makes the project a versatile tool for tackling real-world routing challenges involving time constraints.

-----------------

Authors:
Leonardo Brighenti, Simone Giovanardi

Date: 11/2023
