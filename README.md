
# Maze Game
<img width="1101" alt="Screenshot 2024-07-06 at 10 27 31" src="https://github.com/chinnanj666/maze-game/assets/114425702/53a2281c-00e2-46a2-b9ed-95c12e1215fe">

## Introduction

The "Rat in a Maze" problem is a classic example of a maze-solving puzzle. 

Applying the same concept the goal of the puzzle is to find a path for the KEY from the starting point to the destination of its HOUSE, while avoiding obstacles or walls within the maze. 

This project is a JavaScript-based implementation of the Rat in a Maze problem using the RECURSION and BACKTRACKING algorithm. The solution is visualized on a website using JavaScript and CSS.

## Demo
You can see a live demo of the Rat in a Maze solver here: 


## Features

- Interactive maze visualization.
- Recursive and backtracking algorithm for solving the maze.
- Animation to visualize the pathfinding process.
- Start and end point selection.
- Wall placement feature for custom maze creation.

## Algorithm

The Rat in a Maze problem is solved using a recursive and backtracking algorithm. Here's a high-level overview of the algorithm:

- Check if the current position is the destination. If yes, the maze is solved.
- If not, check if the current position is a valid move (i.e., not a wall and within the maze boundaries).
- If it's a valid move, mark the current position as part of the solution path and recursively explore the adjacent cells.
- If no valid move is found, backtrack to the previous cell and explore other directions.

Continue this process until a solution is found or all possibilities are exhausted.

When Successfully completed it will generate and return the user with number of steps taken for the completion of the Game AND also a button for !TRY AGAIN! as COOL.# maze-game
