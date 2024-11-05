# Maze-Theories
This project explores basic graph theory by using different algorithms to generate, optimize, and solve mazes.


---------------------------------------------------------------------------------------------------------------------
### In Maze Generation – Generation.ipynb

#### Types of Mazes
-	Make random maze
-	Divide maze
-	Make room maze
-	Cellular automaton
-	Primitive (Prim’s algorithm)
-	Row by row
  
Inspiration for algorithms was taken from this [wiki page](https://en.wikipedia.org/wiki/Maze_generation_algorithm)

#### Optimize Maze:
Given the starting square, places the finish square at the end of the longest path

#### Saving the Mazes to File
Can print to file given a maze or print to file with parameters filename and optional for graph type, size, minimum solution length.

#### Playing the Mazes On the Device 
Can play the maze on your screen by creating a MazeLevel object that takes a maze input. Call playLevel() to play. Use the arrow keys to move your character and win by reaching the red finish square!
