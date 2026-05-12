
# GIC Technical Assessment - Data Engineering

## Project Overview
This repository contains solutions for the Auto Driving Car Simulation (Python) and the Batch Job Dependency Analysis (SQL).

### 1. Auto Driving Car Simulation
A robust Python simulation for autonomous vehicles.
- **Design Pattern:** Object-Oriented Programming (OOP) for scalability.
- **Collision Detection:** Real-time step-wise detection to identify the exact moment of impact.
- **Error Handling:** Robust input sanitization to handle formatting variations (commas, casing, etc.).

**To Run:** `python main.py`
**To Test:** `python test_simulation.py`

### 2. SQL Batch Job Analysis
A recursive query designed to map complex job dependencies.
- **Approach:** Recursive CTE (Common Table Expression).
- **Optimization:** Groups parallelizable steps to identify execution levels.
