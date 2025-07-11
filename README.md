# 🧭 Maze Solver 
> 🗓️ Created during my **Second Year** of university.

## 🎯 Project Overview
This project was implemented as a **two-person collaborative assignment**, focusing on data structures and algorithmic problem solving.

The task was to implement a maze-solving robot using a stack-based approach in Java. The robot begins at the upper-left corner of a maze and navigates toward the bottom-right corner by exploring paths and backtracking when necessary.

---

## 📌 Implementation Summary

- A 2D integer array represents the maze:
  - `0` → empty space  
  - `1` → wall  
  - `2` → current path

- The robot starts at coordinate `[1][1]` and aims to reach `[2n-1][2n-1]` (for an `n x n` grid).

- The robot's path is explored using a **stack**, enabling backtracking in case of dead ends.

- After every step or backtrack, the maze is displayed using the `MazeUtility.plotMaze()` method, making the robot’s progress visually traceable.

- No changes were made to the provided files:
  - `MazeSolverProject.java`
  - `MazeUtility.java`
  - `Stack.java`

- The project compiles and runs correctly, successfully navigating the maze and showing the steps in the console.

---

## 🧪 Example Output Behavior

At each step, the console output displays a graphical view of the maze:
- `X` → walls
- `O` → path traced by the robot

The robot continuously explores until it finds a valid path to the goal or exhausts all options.

