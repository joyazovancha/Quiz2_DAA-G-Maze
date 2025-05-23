# **Quiz 2 (DAA) - Maze Generator & Solver** 
Repository for Design & Analysis of Algorithms Secondary Quiz.

## **Group Members**
| Name                              | Student ID | Class  |
| ----------------------------------|------------|:------:|
| Alya Putri Salma                  | 5025211174 | DAA G  |
| Meyroja Zovancha Firoos           | 5025211204 | DAA G  | 
| Danno Denis Dhaifullah            | 5025211027 | DAA G  |

# **Question**
<div align=justify>

You are free to make any computer program for your group project (e.g., game, start-up,
etc.). However, you have to implement any algorithms (e.g., DFS, BFS, DAG, Prim-Jarnik,
Kruskal, etc.) that have been taught in our lectures. For instance, a game that determines
the closest distance, a minesweeper game or a web application that examines the
minimum distance for sending the goods from one point to another point.


# **Answer**
The following is the result of our work based on the questions above.

## **Main Topic Problem**
<div align=justify>

Using Prim's (Minimum Spanning Trees) and Depth First Search algorithms to create a maze generator program, and then solving it using the Depth First Search Algorithm.

## **Maze Description**
<div align=justify>
Maze is a puzzle-like structure composed of interconnected passages or paths that challenges navigational skills. It serves various purposes such as entertainment, education, and research. Mazes can be created in different shapes and sizes and can be two-dimensional or three-dimensional. The objective is usually to find a path from a starting point to a finishing point while navigating through complex twists and turns, which can include obstacles like dead ends, false paths, and traps. Mazes have a long history and have been used for spiritual, entertainment, and educational purposes. Today, they are commonly used in theme parks and video games. Mazes can be created using various methods and require careful planning and consideration of factors such as the purpose, level of difficulty, and target audience.

- **Maze Generator (Prim's MST and DFS Algorithm)** <br>
<div align=justify>
To create a maze, combine Prim's algorithm and DFS. Prim's algorithm starts with a grid where all cells are walls. It randomly selects a starting cell, adds it to visited cells, and adds neighboring cells to the unvisited list. The algorithm selects the cell with the minimum weight, removes it from the unvisited list, and marks walls as passages. This continues until all cells are visited, resulting in a connected maze. DFS adds complexity to the generated maze. It starts at a random cell and explores neighboring cells recursively. It removes walls, creates passages, and continues exploring until reaching a dead end. The algorithm backtracks and explores other unvisited neighboring cells. DFS ensures all cells are interconnected, creating a challenging maze. <br><br/>

- **Maze Solver (Depth First Search Algorithm)**

DFS is a widely used algorithm for maze problem solving. It explores the maze by going as deep as possible along each branch before backtracking. To apply DFS to a maze, we start at the entrance and mark it as visited. Then, we recursively explore neighboring cells that haven't been visited. If we encounter a dead end, we backtrack to the previous cell and explore other paths. DFS uses a stack to keep track of the current path and allows us to search for alternative routes. Although DFS doesn't guarantee the shortest path, it efficiently solves mazes by systematically exploring interconnected cells until finding a path from entrance to exit. 
  
# **Contribution List**

The following is the division of tasks and the percentage contribution of each member in working on Quiz 2.
## **Percentage**
| Name                              | Student ID | Work Contribution  |
| ----------------------------------|:----------:|:------------------:|
| Alya Putri Salma                  | 5025211174 |       33.33%       | 
| Meyroja Zovancha Firoos           | 5025211204 |       33.33%       | 
| Danno Denis Dhaifullah            | 5025211207 |       33.33%       |

## **Work Structural**
**Alya Putri Salma:** <br>
- Make problem Analysis 
- Compiling reports 
- Help develop generator program ideas (structural and completion solutions)
- Edit and help complete the README.md

**Meyroja Zovancha Firoos:**
- Create Design Problems
- Develop a conclusion, concept, or idea
- Completing the program (main)
- Edit and help compile README.md

**Danno Denis Dhaifullah:**
- Arranging Implementation Problems
- Making Conclusions, finish reports
- Develop the program structure and complete the generator program
- Compile and complete README.md.
