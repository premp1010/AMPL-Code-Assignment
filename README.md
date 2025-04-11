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


# Output:
Output plot shows the feasible region and optimal solution for a linear programming problem involving two plants. The shaded blue area represents all combinations of outputs from Plant 1 (x₁) and Plant 2 (x₂) that satisfy the constraints:

x₁ ≤ 4 (green vertical line)

x₂ ≤ 6 (blue horizontal line)

3x₁ + 2x₂ ≤ 18 (orange sloped line)

The red dot marks the optimal production point that maximizes the objective function 3x₁ + 5x₂, which lies at the intersection of x₂ = 6 and 3x₁ + 2x₂ = 18.
