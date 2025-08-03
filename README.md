# SciPy ODE Solver Tutorial

This repository contains a set of Jupyter notebooks designed to teach and analyze the behavior of `scipy.integrate.solve_ivp` across various use cases. It includes both theoretical background and code-driven experimentation.

## 📘 Introduction

This notebook series provides a practical and visual exploration of SciPy’s ODE solver `solve_ivp`. It is designed to help learners and practitioners understand:
- Different solver methods (stiff vs non-stiff)
- Solver parameters and their influence
- How events and Jacobians are handled
- Performance comparisons via accuracy and runtime

Each notebook is modular and can be used independently for learning or demonstrations.

## 📁 Notebooks Overview

| Notebook File                | Description |
|-----------------------------|-------------|
| `1_overview.ipynb`          | High-level overview of ODE problems and solver landscape |
| `2_solve_ivp_parameters.ipynb` | Explanation of main `solve_ivp` arguments and options |
| `3_nonstiff_methods.ipynb`  | Detailed look at non-stiff solvers: RK45, RK23, DOP853 |
| `4_stiff_methods.ipynb`     | Covers stiff solvers: BDF, Radau, LSODA and Jacobian usage |
| `5_event_handling.ipynb`    | Shows how to use events to control solver flow |
| `6_solver_analyzer.ipynb`   | Compare solver performance by runtime and accuracy (RMSE) |


## 🧠 Learning Goals

- Understand the mathematical foundations of stiff vs non-stiff ODEs
- Learn how `solve_ivp` handles event detection and adaptive step sizes
- Compare solver performance (accuracy, steps, runtime) on different ODE systems
- Understand Jacobian usage in stiff solvers and how to improve performance

