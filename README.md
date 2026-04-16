# Pacman Search Algorithms

This project is my implementation of classic search algorithms in the Pacman AI environment. The assignment focuses on building and testing different search methods such as depth-first search, breadth-first search, uniform cost search, and A* search.

The goal is to help Pacman find paths through mazes while comparing how different algorithms behave in terms of correctness, efficiency, and optimality.

## Algorithms Implemented

- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Uniform Cost Search (UCS)
- A* Search

## Heuristics

- Euclidean Heuristic
- Random Heuristic

## Files Worked On

The main files edited for this project were:

- `search.py`
- `searchAgents.py`

## Project Overview

In this project, Pacman solves different maze and pathfinding problems using search algorithms. Each algorithm explores the state space in a different way:

- **DFS** goes deep along one path before backtracking.
- **BFS** explores the shallowest nodes first.
- **UCS** expands the node with the lowest total path cost.
- **A\*** expands the node with the lowest combined path cost and heuristic value.

This project also includes heuristic functions to improve informed search.

## How to Run

Make sure you are inside the project folder before running commands.

### Run Depth-First Search
```bash
python pacman.py -l tinyMaze -p SearchAgent
