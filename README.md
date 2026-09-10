# evolutionaryAI
Project and homework problems for Evolutionary AI Course

# Homework 1

This project implements and compares search algorithms to solve two classic problems: the **15-Puzzle** and a **Railroad Navigation Network**.

## Project Files

* 'boards.ipynb' - Jupyter notebook containing the 4x4 puzzle logic, Manhattan distance heuristic, and search implementations (A* and Greedy Best-First). Runs test boards and exports results.
* 'Astar-railway.ipynb' - Jupyter notebook for the railroad network graph search (DFS, BFS, UCS, Greedy, and A*).
* 'graph.json' - Station coordinates and connection data used by the railway script.
* 'check_submission.py' - Script provided to validate 'puzzle-solutions.json' output formatting.
* 'puzzle-solutions.json' - Generated benchmark results.
* 'AI Report.pdf' - Final written report.

## How to Run

### 15-Puzzle
1. Open `boards.ipynb` in Jupyter Notebook or other.
2. Run all cells to process the initial test boards.
3. The script verifies board solvability before running searches and automatically saves the output to 'puzzle-solutions.json'.
4. To test a custom starting board, pass a row-formatted string ('"1 2 7 3 / 5 6 _ 4 / 9 10 11 8 / 13 14 15 12"').

### Railroad Problem
1. Make sure 'graph.json' is in the same location as 'Astar-railway.ipynb'.
2. Open and run 'Astar-railway.ipynb' to load the railway graph and run the routing searches.

Check submission directly using 'check_submission.py'.
