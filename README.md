# 24-puzzle-problem

The 24-puzzle is a larger version of the 8-puzzle.

Goal:

| 1 | 2 | 3 | 4 | 5 |
|:-:|:-:|:-:|:-:|:-:|
| 6 | 7 | 8 | 9 | 10 |
| 11 | 12 | 13 | 14 | 15 |
| 16 | 17 | 18 | 19 | 20 |
| 21 | 22 | 23 | 24 |   |

Initial

| 9 | 24 | 3 | 5 | 17 |
|:-:|:-:|:-:|:-:|:-:|
| 6 |   | 13 | 19 | 10 |
| 11 | 21 | 12 | 1 | 20 |
| 16 | 4 | 14 | 12 | 15 |
| 8 | 18 | 23 | 2 | 7 |

For this programming assignment, you will create a set of search algorithms that find solutions to the 24-puzzle problem. You are requested to implement the programs to the 24-puzzle problem using

1. **breadth-first**  search (BFS)
2. **depth-first**  search (DFS)
3. **informed** search algorithms using

h1(x) = number of misplaced tiles

and

h2(x) = sum of the distances of every tile to its goal position.

For each of the search routines, avoid returning to states that have already been visited on the current solution path i.e., there should be no repeated states in a solution.

**What to Hand in**

1. Well documented codes implementing breadth first search, depth first search, and informed search. A README file should provide instructions on how to compile and execute the code.
2. Provide the sample solutions generated by your programs using BFS, DFS, and informed search.
3. Analysis of your program. Compare the computational time and lengths of solutions of BFS, DFS, and informed search using different heuristic functions.

Hints:

1. It is much better to model the problem of moving the blank around than moving movable tiles.
2. Good data structure representation can make your life easy.
3. You may want to start from the 8-puzzle problem.
