# Simple Pathfinding Algorithm in C++

A beginner-friendly implementation of pathfinding algorithm with visualization.

## What This Does
Finds a path from start (S) to goal (G) while avoiding walls (X) in a 5x5 grid.

## How It Works
1. Starts at position (0,0)
2. Checks 4 directions (up, down, left, right)
3. Avoids walls and visited cells
4. Builds path step by step
5. Reaches goal (4,4)

## Example Output
Grid (X=wall, .=empty, S=start, G=goal):
S . . . .
. X X . .
. . X . .
. . X . .
. . . . G

Path: (0,0) (0,1) (0,2) (0,3) (0,4) (1,4) (2,4) (3,4) (4,4)

Visualization:
S . . . .
P X X . .
P . X . .
P . X . .
P P P P G

## Code Structure
- `Node` struct: Represents each cell
- `findPathSimple()`: Core pathfinding logic
- `main()`: Creates grid and displays results

## Key Concepts Learned
- Grid-based navigation
- Path reconstruction
- Simple AI decision making
- Algorithm visualization

## Real-World Applications
- Video game AI (NPC movement)
- Robotics (obstacle avoidance)
- GPS navigation systems
- Maze solving algorithms
