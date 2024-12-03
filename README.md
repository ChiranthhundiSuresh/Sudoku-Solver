# Sudoku-Solver
Sudoku Solver in Python

## Description
This project implements a Sudoku solver using the backtracking algorithm. It takes an incomplete Sudoku grid as input and attempts to solve it by filling in the empty cells (represented as 0) while adhering to the standard Sudoku rules.

The solver uses a recursive approach to try placing numbers in each empty cell and backtracks when it encounters an invalid state. The solution is displayed neatly in the console.

## Features
1. Validates the placement of numbers in the grid based on Sudoku rules:
2. A number can only appear once per row, column, and 3x3 subgrid.
3. Solves any valid Sudoku grid efficiently using backtracking.
4. Displays the original and solved grids for easy comparison.

## Requirements
1. Python 3.x
2. Jupyter Notebook (if running interactively)
3. Optional: NumPy (used for matrix-style operations or enhancements)

## How to Use
1. Clone or download the script.
2. Open the script in a Python environment or Jupyter Notebook.
3. Replace the predefined Sudoku grid in the sudoku_grid variable with your own puzzle.
4. Use a 9x9 matrix where empty cells are represented as 0.
5. Run the script.
6. View the original and solved Sudoku grids printed in the console.

