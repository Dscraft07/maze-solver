# Maze Solver

A visual maze generation and solving application built with Python and Tkinter.

## Description

This project creates random mazes and solves them using a depth-first search algorithm. The solving process is animated to provide a visual representation of how the algorithm explores paths and backtracks when it reaches dead ends.

## Features

- Random maze generation
- Visual representation of maze solving process
- Depth-first search algorithm implementation
- Animation of the maze solving with backtracking visualization

## Technologies Used

- Python 3
- Tkinter for GUI
- Random and time modules

## Installation

1. Clone this repository:

```
git clone https://github.com/YOUR-USERNAME/maze-solver.git
```

2. Navigate to the project directory:

```
cd maze-solver
```

3. Run the application:

```
python main.py
```


## Usage

Simply run the application and watch as it:
1. Generates a random maze
2. Solves the maze using depth-first search
3. Visualizes the solving process with different colors

## Algorithm

The maze is solved using a depth-first search algorithm that:
- Explores as far as possible along each branch before backtracking
- Uses a stack to keep track of the path
- Colors the current exploration path and backtracks when reaching dead ends
