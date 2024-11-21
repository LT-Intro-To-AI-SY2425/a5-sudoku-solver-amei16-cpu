# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. How do the performance and efficiency of the Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms compare when solving Sudoku puzzles? In what scenarios might one approach be preferable over the other?

It makes things more efficient than a human when solving it since using depth-first search and breadth-first search does the whole solving process for us and the sort of guess and check for us. But for the sudoku scenario, we would definitely want to use a depth-first search

2. How did the choice of data structures (like the Stack for DFS and Queue for BFS) impact the implementation and functionality of the algorithms? Are there alternative data structures or design patterns that could have been used to achieve the same objectives?

The impact of data structures like Stack makes it a lot easier to work on the coding part like with the copy data structure made it where we can make a copy of the board and if there was a problem we can find it and move on to another without affecting the actual board itself. Some design patterns that could also implement DFS and BFS would be those math triangles where you have to add each side to make it all add up to the same sum.

3. Considering the current implementation, how might the Sudoku solver be adapted or extended for larger puzzles or different types of grid-based logic games? How can the lessons learned from this assignment be applied to real-world problem-solving or optimization challenges?

Sort of like what I said on the top with the triangle and all the circles add up to make the same sum with numbers like 1,2,3,4,5,6 have to add up on all sides of a triangle to equal 9. Lessons from this assignment to me can be used sort of like for an investigation where DFS would be you focusing down on one piece of evidence and see what it leads you and where BFS is where you look at all the pieces of evidence.