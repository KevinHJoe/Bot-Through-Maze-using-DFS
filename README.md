## Maze Solver using DFS Algorithm

### Overview
This project implements a maze solver using Depth-First Search (DFS) in Java. The solver navigates a maze represented as a 2D array, starting from a given point and finding the path to the exit while marking its route and handling dead ends.

Sample of what it looks like:
https://imgur.com/AKFmEab

### Project Structure
- **Main Class**: Contains the main logic for the maze solver.
- **Coordinate Class**: Represents coordinates within the maze.

### How It Works
1. **Initialization**: The maze is a 2D array with:
   - `1`: walls
   - `0`: open paths
   - `3`: entrance
   - `5`: exit
   - `4`: bot's path
   - `-1`: dead ends

2. **DFS Algorithm**:
   - Explores paths in the order: down, up, right, left.
   - Marks the path taken and dead ends.
   - Prints the maze state at each step with delays.

3. **Visualization**:
   - Shows the bot's progress.
   - Prints "You're Free!" and the optimal route upon reaching the exit.

### Usage
1. **Compile and Run**:
   - Compile: `javac Main.java`
   - Run: `java Main`

2. **Output**:
   - Prints the maze at each step.
   - Displays the optimal route taken.

### Key Methods
- **dfs(int i, int j)**: Implements the DFS algorithm.
- **printMaze(int[][] m)**: Prints the maze state.
- **eraseDeadEndPrint(Deque<Coordinate> deq)**: Marks dead ends.
- **setOptimumRoute(Deque<Coordinate> deq)**: Prints the optimal route coordinates.
