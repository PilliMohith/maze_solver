# Maze Solver - DFS Implementation 🧩

An educational implementation of a maze solver using the **Depth-First Search (DFS)** algorithm. This project is designed for learning fundamental algorithms and contributing to open source!

## 🎯 What is This?

This project demonstrates how to solve mazes using DFS, a fundamental graph traversal algorithm. It's perfect for:
- Learning about graph algorithms
- Understanding recursion and backtracking
- Contributing to open source projects
- Visualizing algorithm behavior

## 🚀 Quick Start

### Prerequisites
- Python 3.6 or higher

### Running the Maze Solver

```bash
python main.py
```

This will run the solver on all example mazes and display the solutions!

## 📚 How It Works

### Depth-First Search (DFS) Algorithm

DFS explores a maze by:
1. **Starting** at the initial position (S)
2. **Exploring** one direction as far as possible
3. **Marking** visited positions to avoid cycles
4. **Backtracking** when hitting a dead end
5. **Finding** the goal position (E)

### Code Structure

```
maze_solver/
├── maze.py           # Maze representation and utilities
├── dfs_solver.py     # DFS algorithm implementation
├── example_mazes.py  # Pre-defined test mazes
├── main.py           # Main entry point
└── README.md         # This file!
```

### Key Components

#### 1. **Maze Class** (`maze.py`)
Represents the maze as a 2D grid where:
- `0` = walkable path
- `1` = wall
- `'S'` = start position
- `'E'` = end position

#### 2. **DFSSolver Class** (`dfs_solver.py`)
Implements the DFS algorithm with:
- Recursive exploration
- Visited tracking
- Path reconstruction
- Statistics collection

#### 3. **Example Mazes** (`example_mazes.py`)
Provides test mazes of varying difficulty:
- **Simple**: Great for beginners (5x5)
- **Medium**: Requires backtracking (8x8)
- **Complex**: Many dead ends (10x10)
- **Spiral**: Interesting pattern (7x7)
- **Impossible**: No solution (demonstrates correctness)

## 🎓 Understanding the Output

When you run the program, you'll see:

```
Original Maze:
S . . . .
█ █ █ █ .
. . . . .
. █ █ █ █
. . . . E

Maze with Solution Path (marked with *):
S * * * .
█ █ █ █ *
. . . . *
. █ █ █ █
. . . . E

Statistics:
  - Path length: 9 steps
  - Nodes visited: 13
  - Efficiency: 69.23%
```

## 🤝 How to Contribute

We welcome contributions! Here are some ideas:

### For Beginners:
1. **Add new example mazes** in `example_mazes.py`
2. **Improve documentation** with more explanations
3. **Add comments** to explain tricky parts of the code
4. **Test edge cases** and report issues

### Intermediate:
1. **Implement BFS** (Breadth-First Search) as an alternative solver
2. **Add maze generation** functionality
3. **Create visualization** (e.g., animated solution)
4. **Add performance benchmarks** comparing algorithms

### Advanced:
1. **Implement A\*** or other pathfinding algorithms
2. **Add GUI** using pygame or tkinter
3. **Support different maze formats** (images, text files)
4. **Optimize for very large mazes**

### Contributing Steps:
1. Fork this repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Test your code
5. Commit your changes (`git commit -m 'Add some feature'`)
6. Push to your branch (`git push origin feature/your-feature`)
7. Open a Pull Request

## 📖 Learning Resources

- [DFS Algorithm Explanation](https://en.wikipedia.org/wiki/Depth-first_search)
- [Graph Traversal Algorithms](https://www.geeksforgeeks.org/graph-data-structure-and-algorithms/)
- [Python Recursion Tutorial](https://realpython.com/python-recursion/)

## 🧪 Testing Your Changes

After making changes, run the program to ensure everything works:

```bash
python main.py
```

Check that:
- All solvable mazes find solutions
- The impossible maze reports "No solution"
- The output is clear and readable

## 💡 Ideas for Extensions

- **Multiple algorithms**: Compare DFS, BFS, A*, Dijkstra
- **Maze generator**: Create random mazes
- **3D mazes**: Extend to three dimensions
- **Weighted paths**: Different terrain costs
- **Animation**: Show the algorithm in action
- **File I/O**: Load mazes from files
- **Web interface**: Make it accessible online

## 📝 Code Style

- Use meaningful variable names
- Add docstrings to functions and classes
- Follow PEP 8 style guidelines
- Comment complex logic

## 🐛 Found a Bug?

Please open an issue with:
- Description of the bug
- Steps to reproduce
- Expected vs actual behavior
- Your Python version

## 📜 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

Created for club members to learn algorithms and contribute to open source!

Happy coding! 🎉