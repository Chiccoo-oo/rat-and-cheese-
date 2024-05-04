# Rat in a Maze problem 
**Overview**
The Rat in a Maze problem is a classic puzzle where a rat needs to find its way from the starting point to the destination in a maze. 
The rat can only move in four directions: up, down, left, and right, and it cannot move through walls or obstacles.
This project provides a Python implementation to solve the Rat in a Maze problem using both backtracking and Depth-First Search (DFS) algorithms.

## Problem Statement 
There will be a maze of size nxn, with walls at random position with random shape. The source will be at the top left, and the destination will be at the bottom right.
*Task*
The task is to find the cheese which is at the destination from the source.
**Constraints:**
The maze is typically represented as a square grid, but it can also be of arbitrary shape.

The maze may contain obstacles or blocked cells that the rat cannot pass through.

The rat can only move horizontally or vertically from one cell to another, not diagonally.

The rat must find a valid path from the starting point to the destination without revisiting any cell or going out of bounds.


**Approach:**
Depth-First Search (DFS): One common approach to solving the Rat in a Maze problem is to use the Depth-First Search algorithm. DFS systematically explores all possible paths in the maze, starting from the initial cell and recursively exploring neighboring cells until it finds the destination or exhausts all options.

**Priority to move**
right -> down -> left -> up


**Data-Structure Used:**
Stack(Linked list)
> In this, stack is implemented using list(append and pop)

**Traversal Method:**
Depth First Search(DFS):Depth-First Search (DFS) is a fundamental graph traversal algorithm used in computer science and graph theory. It systematically explores all vertices and edges of a graph, visiting as far as possible along each branch before backtracking.

**Implementation:**
Grid Representation: The maze is typically represented as a 2D grid, where each cell is either open (passable) or blocked (impassable).
Algorithm: The DFS algorithm is applied to explore the maze, with each recursive call representing a move by the rat from one cell to another. The algorithm backtracks when it reaches a dead end or encounters a blocked cell.
Termination Condition: The algorithm terminates when the rat reaches the destination cell, indicating that a valid path has been found, or when all possible paths have been explored without finding a solution.


**Applications:**
The Rat in a Maze problem serves as a fundamental example of graph traversal and pathfinding algorithms in computer science.
It has applications in various fields, including robotics, artificial intelligence, and game development, where pathfinding is essential for navigation and decision-making.


**Modules Used**

* Time

* Numpy

* Termcolor

* **Gui Modules**

    * Tkinter

    * Pillow
# Steps to run:
*Installation of Dependencies:* Ensure that you have the required dependencies installed on your system. The program requires the following dependencies:
-Python 3.x
-NumPy
-tkinter (for GUI components)
-termcolor (for colored terminal output)
-PIL (Python Imaging Library, for image processing)
*Download the Code:* Download the "rat-in-a-maze.py" file from the source.
*Navigate to the Directory:* Open your command-line interface or terminal and navigate to the directory where the "rat-in-a-maze.py" file is located.

*Enter Maze Dimensions and Positions:* Follow the prompts to enter the dimensions of the maze, as well as the positions of the rat (source) and cheese (destination). Make sure to enter valid positions within the maze boundaries.
*Explore the Maze:* Once the program starts, it will display the maze grid along with the rat's position. The rat will navigate through the maze to find the cheese. You can observe the progress of the rat's movements visually on the grid.
*Outcome:* Depending on the maze configuration and the rat's navigation, the program will either successfully find the cheese or indicate that the rat is unable to find the cheese within the maze.
*Exit the Program:* After the outcome is displayed, you can close the program or follow any additional prompts.

Following these steps will allow you to run the "Rat in a Maze" program and observe its behavior in navigating through the maze to find the cheese.

# Conclusion:
Solving the Rat in a Maze problem requires applying graph traversal algorithms such as DFS to explore possible paths through the maze and find a valid route from the starting point to the destination.
Understanding and solving this problem helps in developing algorithmic thinking and problem-solving skills, particularly in the context of graph algorithms and maze navigation.
By understanding the problem's details and constraints, developers can implement efficient algorithms to solve the Rat in a Maze problem and apply them to various real-world scenarios requiring pathfinding and navigation.







