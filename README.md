# Multi-Echelon VRP Optimization Engine

This repository showcases the core algorithmic components developed for complex, large-scale urban logistics networks, specifically focusing on the Two-Echelon Vehicle Routing Problem (2E-VRP).

## Key Features
* **Scalable Offline Heuristics:** Implementation of a constructive metaheuristic architecture with custom Local Search operators (Relocate, Swap, Drop-off modification) to solve Multi-Period models.
* **Exact Dynamic Modeling:** Snippets demonstrating integration with IBM ILOG CPLEX via Python (`docplex`) for handling demand using a Multi-Stage Rolling Horizon (MSRH) control loop.
* **Software Engineering:** Object-oriented design utilizing Python `dataclasses`, strict type hinting, and incremental objective evaluation for rapid local search convergence.

*Note: Due to ongoing peer-review processes for academic publication, the primary clustering-based algorithms and monolithic datasets are omitted. This repository serves as a technical portfolio demonstrating Operations Research proficiency and Python algorithm development.*

## Tech Stack
- **Core Language:** Python 3.x (Advanced OOP, `dataclasses`, Strict Type Hinting)
- **Mathematical Modeling:** IBM Decision Optimization (`docplex`)
- **Data & Numerical Processing:** `numpy`, `pandas`
- **I/O & Pipelines:** `openpyxl`

Copyright (c) 2026 Mohammad Hamed Mahdavi. All Rights Reserved.
