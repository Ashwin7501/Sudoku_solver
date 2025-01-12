# Sudoku Solver

A simple Python program to solve 9x9 Sudoku puzzles using a backtracking algorithm.

---

## Features
- Solves any valid 9x9 Sudoku puzzle.
- Uses a backtracking approach for efficient solving.
- Includes functions to print the board in a readable format.

---

## How to Use
1. Clone the repository or download the script.
2. Modify the `board` variable in the script with your Sudoku puzzle. Use `0` for empty cells.
3. Run the script:
   ```bash
   python sudoku_solver.py
   ```
4. The program will print the unsolved board, solve it, and print the completed board.

---

## Example

### Input Puzzle:
```
7 8 0 | 4 0 0 | 1 2 0
6 0 0 | 0 7 5 | 0 0 9
0 0 0 | 6 0 1 | 0 7 8
- - - - - - - - - - - -
0 0 7 | 0 4 0 | 2 6 0
0 0 1 | 0 5 0 | 9 3 0
9 0 4 | 0 6 0 | 0 0 5
- - - - - - - - - - - -
0 7 0 | 3 0 0 | 0 1 2
1 2 0 | 0 0 7 | 4 0 0
0 4 9 | 2 0 6 | 0 0 7
```

### Output Puzzle:
```
7 8 5 | 4 3 9 | 1 2 6
6 1 2 | 8 7 5 | 3 4 9
4 9 3 | 6 2 1 | 5 7 8
- - - - - - - - - - - -
8 5 7 | 9 4 3 | 2 6 1
2 6 1 | 7 5 8 | 9 3 4
9 3 4 | 1 6 2 | 7 8 5
- - - - - - - - - - - -
5 7 8 | 3 9 4 | 6 1 2
1 2 6 | 5 8 7 | 4 9 3
3 4 9 | 2 1 6 | 8 5 7
```

---

## Functions
- **`solve(board)`**: Solves the Sudoku puzzle using backtracking.
- **`valid(board, num, pos)`**: Checks if a number is valid in a given position.
- **`print_board(board)`**: Prints the board in a readable format.
- **`find_empty(board)`**: Finds the next empty cell.

---

Feel free to fork and experiment! 🎉
