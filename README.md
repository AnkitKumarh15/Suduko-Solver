# Suduko-Solver
This is a Sudoku solver written in JavaScript. It is a command-line application that takes a Sudoku puzzle as input and solves it using backtracking algorithm.

# Sudoku Puzzle
A Sudoku puzzle is a 9x9 grid divided into nine 3x3 sub-grids. The goal is to fill in the empty cells with digits from 1 to 9, such that each column, each row, and each of the nine 3x3 sub-grids contains all of the digits from 1 to 9 without repetition.

# Algorithm
The Sudoku solver uses a backtracking algorithm to solve the puzzle. It follows these steps:

Find the first empty cell in the puzzle.
Try each digit from 1 to 9 in the empty cell.
If a digit is valid (i.e., it doesn't violate the Sudoku rules), move to the next empty cell and repeat steps 2 and 3.
If a digit is not
