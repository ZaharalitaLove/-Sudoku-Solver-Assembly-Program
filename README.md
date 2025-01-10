# -Sudoku-Solver-Assembly-Program

Project Overview:

Sudoku solver for a 3x3 Latin Square written in HMMM assembly language. 
The solver starts at the first square, tries possible values, and recursively continues solving the puzzle. If a conflict occurs, it backtracks and tries different values. 

Features:

* Memory Management
* Backtracking 
* Recursive Depth-First Search
* Assembly Language

Files:

sudokish.hmmm - file containing the bare  HMMM instructions for solving the sudoku boards.


How-To:
* Load Sudokish.lbl into the HMMM simulator. http://shickey.github.io/HMMM.js/
* Input a 3x3 board with values 1,2,4 or 0 (0 for empty cells that need to be solved). 
* Run the program.
