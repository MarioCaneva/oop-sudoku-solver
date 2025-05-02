# 🧩 Sudoku Solver in Python (OOP)

This project uses object-oriented programming to build a Sudoku solver. It uses backtracking recursion to fill the grid, ensuring that every row, column, and 3x3 subgrid contains all digits from 1 to 9 without repetition.

## 🚀 What It Does

- Defines a `Board` class to encapsulate the Sudoku grid and logic
- Checks row, column, and 3x3 square constraints
- Recursively fills empty cells using backtracking
- Solves standard 9x9 puzzles with a readable interface

## 🧠 Key Features

- `find_empty_cell()`: Locates the next unfilled cell
- `is_valid()`: Checks if a number can be placed without violating Sudoku rules
- `solver()`: Recursively tries values from 1–9 and backtracks if needed
- Custom string representation for pretty printing

## 📌 Example

```python
puzzle = [
  [0, 0, 2, 0, 0, 8, 0, 0, 0],
  [0, 0, 0, 0, 0, 3, 7, 6, 2],
  [4, 3, 0, 0, 0, 0, 8, 0, 0],
  ...
]
solve_sudoku(puzzle)
Output:
python-repl
Copy
Edit
Puzzle to solve:
* * 2 * * 8 * * *
...

Solved puzzle:
9 1 2 6 7 8 5 3 4
...
📚 Concepts Practiced
Object-Oriented Programming (OOP)

Recursion and backtracking

2D array manipulation

Algorithm design

🧰 Technologies Used
Python 3

Classes and objects

Custom string formatting
