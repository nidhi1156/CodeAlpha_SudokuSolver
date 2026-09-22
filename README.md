# Sudoku Solver

## CodeAlpha C++ Programming Internship – Task 3

### Project Overview

This project is a **Sudoku Solver** developed using C++. It solves a standard 9×9 Sudoku puzzle using a backtracking algorithm.

### Features

- Solves a standard 9×9 Sudoku puzzle
- Checks whether a number can be placed safely
- Validates rows, columns, and 3×3 boxes
- Uses a backtracking algorithm
- Displays the original Sudoku puzzle
- Displays the solved Sudoku puzzle
- Simple and beginner-friendly C++ implementation

### How It Works

The program first identifies an empty cell in the Sudoku grid.

It then tries numbers from **1 to 9** and checks whether the selected number is valid according to Sudoku rules.

If a valid number is found, the program places it in the cell and continues solving the remaining puzzle.

If a solution cannot be found, the program backtracks and tries another number.

### Algorithm Used

**Backtracking Algorithm**

The main steps are:

1. Find an empty cell.
2. Try numbers from 1 to 9.
3. Check whether the number is valid.
4. Place the number if it is safe.
5. Recursively solve the remaining cells.
6. If the solution fails, backtrack and try another number.
7. Continue until the complete Sudoku is solved.

### Technologies Used

- C++
- Functions
- Arrays
- Loops
- Conditional Statements
- Recursion
- Backtracking Algorithm

### File Structure

    CodeAlpha_SudokuSolver/
    │
    ├── Sudoku_Solver.cpp
    └── README.md

### Sample Sudoku

The program uses a predefined 9×9 Sudoku puzzle containing empty cells represented by `0`.

### Output

After successful execution, the program displays:

- Original Sudoku
- Solved Sudoku

### Concepts Demonstrated

- Two-dimensional arrays
- Functions
- Recursion
- Backtracking
- Conditional logic
- Searching and validation

### How to Run

Compile the program using a C++ compiler:

    g++ Sudoku_Solver.cpp -o Sudoku_Solver

Run the program:

    ./Sudoku_Solver

On Windows:

    Sudoku_Solver.exe

### Internship

**CodeAlpha C++ Programming Internship**

**Task:** Sudoku Solver

### Author

C++ Programming Internship Project

### Acknowledgement

This project was developed as part of the **CodeAlpha C++ Programming Internship**.
