# AMPL-Code-Assignment
Problem Overview
The goal is to maximize the total benefit from two production plants:

Objective:
Maximize 3x₁ + 5x₂
where x₁ and x₂ are outputs from Plant 1 and Plant 2, respectively.
x₁ ≤ 4        (Plant 1 capacity)
x₂ ≤ 6        (Plant 2 capacity)
3x₁ + 2x₂ ≤ 18  (Resource constraint)
x₁, x₂ ≥ 0     (Non-negativity)

Features
LP model defined using AMPL.
Uses amplpy to solve the model with a Python interface.
Plots the feasible region and highlights the optimal solution.

How to Use
Install Dependencies:
pip install amplpy matplotlib numpy

Run the Jupyter Notebook:
Open LP.ipynb or the updated LP_modified.ipynb
Execute each cell to define, solve, and visualize the LP model.
