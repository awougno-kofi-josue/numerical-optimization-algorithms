<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-0F172A?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/NumPy-1E3A8A?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/SciPy-0284C7?style=flat-square&logo=scipy&logoColor=white" alt="SciPy" />
  <img src="https://img.shields.io/badge/Jupyter-0F172A?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter" />
</p>

---

### Overview

This repository provides clean, from-scratch Python and Jupyter Notebook implementations of foundational algorithms in **numerical optimization**, **linear programming**, and **iterative nonlinear equation solving**. Each module pairs clear algorithmic logic with convergence diagnostics and computational benchmarks.

---

### Implemented Algorithms

#### 1. Linear Programming: The Simplex Method
Solves constrained linear optimization problems in standard canonical form by traversing extreme vertices of the feasible region via Gauss-Jordan pivot operations.

* **Capabilities:** Tableau construction, slack and surplus variable augmentation, Bland's anti-cycling pivot rule, infeasibility and unboundedness detection, and dual shadow-price extraction.

---

#### 2. Unconstrained Nonlinear Optimization: Gradient Descent
Minimizes differentiable multivariate objective functions using first-order directional derivatives and adaptive step-size selection.

* **Capabilities:** Fixed learning rate schedules, backtracking line search (Armijo-Goldstein condition), momentum acceleration, and trajectory visualization on convex and non-convex test surfaces (Rosenbrock and quadratic functions).

---

#### 3. Iterative Root-Finding Solvers
Computes real roots of scalar nonlinear equations across bracketed and open-domain regimes:

* **Newton-Raphson Method:** Fast quadratic convergence using local first-derivative tangent approximations.
* **Secant Method:** Derivative-free superlinear convergence using finite-difference slope approximations.
* **Bisection Method:** Guaranteed linear convergence by iteratively halving sign-changing intervals.

---

