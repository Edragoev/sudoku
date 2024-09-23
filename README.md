# Sudoku
#### Video Demo:  https://youtu.be/JFd_-z3iKh4
#### Description
My project is a sudoku generator with a playable aspect. I decided to create a sudoku board as it was something I did a lot during the pandemic and thought it would be interesting to understand how exactly a sudoku board is generated. I used a backtracking algorithm to initially create a sudoku solver however I thought it would be more interesting to create boards myself and still incorporate the algorithm but in a different way. Using this project I would later like to explore different methods in presenting it as using the terminal isn't the most effective way of making sudoku however, I used this project to sharpen my python skills and incorporate the knowledge I have learned throughout the course. The following list is the functions I incorporated within my project and their uses:

Functions
- validate_input(): validates the value being inputting into the sudoku puzzle
- correct(grid): takes the puzzle as an argument and verifies if it is a valid solution
- fill_grid(grid): takes the puzzle as an argument and solves the puzzle
- create_board(): creates a sudoku puzzle
- possible(): a part of the solution component (verifies if placement of number within the puzzle is possible)
- find_next_empty(): a part of the solution component (finds next empty square within the grid)
- solve(): return a boolean on whether or not the problem is solvable before outputting puzzle to the user
- solved(): checks if grid is filled

The functions work together to create my project. The create_board() function utilizes many of the functions from possible, find_next_empty, solve, fill_grid due to the fact that it is the most complicated of my functions. The remaining functions were used to create a more user-friendly experience by validating their input and checking their solution. Overall this was a very interesting project to me as it incorporated a new algorithm that I learned about regarding back-tracking as well as allowed me to create a project that could be adapted to something greater in the future.
