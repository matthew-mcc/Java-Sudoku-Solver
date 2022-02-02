# Java-Sudoku-Solver

Simple terminal based sudoku solver written in Java using a _backtracking_ algorithm. Backtracking algorithm is a brute-force recursive solution to keep checking solutions and removing them if they
are not valid. In the case of this project, the algorithm attempts to place a number from 1-9 and then checks if it is valid along the three conditions for a sudoku game (valid in row, valid in col, valid in box) 
and keeps doing this until it fails one of these tests. Once it fails it backtracks to a previously valid solution and tries another number.

# Software / libraries used:
-Java

# ___USAGE___
To run the solver:
1. Navigate to the Solver.java class.
2. Run the program in your Java compiler.
Note, if you want to change the board, you have to do so in the Main function in the class, it is hardcoded in as a 2D array.

# Versions:
This is currently in Beta 1.1.

# Further implementation
Further implementation ideas include:
- Creating a GUI to visualize the backtracking algorithm at work.
- Creating an option to attempt to solve the game yourself, and then run the solver if you get stuck.
- Creating a random board each time if you do not provide on eas input.
# Sources:
Full tutorial from https://www.journaldev.com/42143/java-sudoku-solver was extremely helpful.
