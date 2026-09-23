# Scalable Heuristic Routing Engine

This repository showcases the algorithmic components developed for large-scale urban logistics networks, focusing on the Two-Echelon Vehicle Routing Problem (2E-VRP).

## Key Features
* **Clairvoyant Heuristics:** Implementation of a "Cluster-First, Route-Second" metaheuristic architecture to solve Multi-Period static models.
* **Algorithmic Complexity:** Specialized routing sub-routines utilizing incremental delta calculations for TSP operators (2-opt, Or-opt) to drastically minimize execution time.
* **Software Engineering:** Object-oriented design utilizing Python `dataclasses`, strict type hinting, and dynamic time-budgeting.

*Note: Proprietary K-Medoids clustering algorithms, monolithic datasets, and specific local search capacity-repair loops are omitted due to academic publishing confidentiality.*

## Tech Stack
- Python 3.x
- `numpy`

Copyright (c) 2026 Mohammad Hamed Mahdavi. All Rights Reserved.
