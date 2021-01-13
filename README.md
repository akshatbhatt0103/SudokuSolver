# SudokuSolver using C++:
This program is to solve Sudoku using C++. Here we use a 9x9 matrix to input our values between 0-9 in our sudoko where 0 represents empty space and rest are valid inputs.
We will use the following functions:
- ***canPlace9x9***: to check the condition whether our cell is empty or not, the function takes three parameters array, size of row and column and the number we want to 
    input. It returns **TRUE** if the cell is empty and **FALSE** if cell has a value.
- ***solveSudoku9x9***: to return **TRUE** if sudoku is solvable and **FALSE** if not. It take 3 parameters array/matrix, size of row and column.
- ***findPlaceables***: returns set of numbers that can be placed at the cell.
- ***copyArrray***: to copy the value placed into another array.
- ***nextEmpty***: to find the next empty row and column indexes for the value to be placed.
- ***printSudoku9x9***: to print the sudoku.

# Output:
 - ![INPUT:](https://github.com/akshatbhatt0103/SudokuSolver/blob/main/input.PNG)
 - ![OUTPUT:](https://github.com/akshatbhatt0103/SudokuSolver/blob/main/output.PNG)
  
