# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver

For this project, I built an agent that can solve diagonal sudoku by utilizing three sudoku strategies: elimination, only-choice, and naked twins.

Run solution.py to test the solution!  Python 3 required.  Also make sure pygame is installed to see the visualization of the solution.

# Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: We use constraint propagation to solve the naked twins problem by enforcing the constraint that no squares outside of the twins can be assigned the twin values.  

# Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: We enforce the constraint that the squares along the main diagonals of the sudoku board must have the numbers 1-9 appear exactly once, similar to the requirements in regular sudoku for rows and columns.
