# Sudoku Solver using Java (GUI)

## Overview
This project implements a **Sudoku Solver** using the **Backtracking algorithm** with a **Java Swing GUI**.
Users can input an unsolved Sudoku puzzle and the program automatically computes a valid solution.

## Features
- Interactive 9×9 Sudoku grid
- Backtracking-based algorithm
- Solve and Clear functionality
- Input validation
- User-friendly GUI

## Algorithm
The solver uses the **Backtracking Algorithm**, which:
1. Finds an empty cell
2. Tries numbers from 1 to 9
3. Checks row, column, and 3×3 subgrid constraints
4. Backtracks when a conflict occurs

## Technologies Used
- Java
- Java Swing (GUI)

## Project Structure
```
Sudoku-Solver-Java/
│
├── SudokuSolverGUI.java
├── README.md
```
## How to Run
1. Install JDK (Java 8 or above)
2. Compile the program:
```
javac SudokuSolverGUI.java
```
3. Run the program:
```
java SudokuSolverGUI
```

## Usage

-Enter numbers (1–9) in the grid

-Leave empty cells blank

-Click Solve to generate the solution

-Click Clear to reset the grid
