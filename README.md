# Maze Solver

## Overview
Maze Solver is a Python application that generates random mazes and attempts to solve them using a depth-first search (DFS) algorithm. The application features a graphical user interface that visually represents the maze and its solution path.

## Components

- **`main.py`**: Entry point that initializes and displays the maze.
- **`maze.py`**: Implements the `Maze` class, handling maze generation and solving.
- **`cell.py`**: Defines the `Cell` class, representing individual maze cells.
- **`graphics.py`**: Contains graphics primitives such as `Window`, `Point`, and `Line` for visualizing the maze.
- **`tests.py`**: Unit tests for validating maze generation and solving functionality.

## Usage

### Running the Application
To execute the program, run:

```sh
python main.py
```


## Features

- **Randomized maze generation**
- **Visual representation of maze walls and paths**
- **Animated solving process for better understanding**
- **Customizable maze dimensions and appearance**

## Customization

Users can modify maze properties by adjusting parameters in `main.py`:

```python
maze = Maze(rows=20, cols=20)  # Customize maze size
```

