# MINESWEEPER_Pr8
The "Text-Based Minesweeper Game in Python" project is designed to offer a console-based rendition of the well-known puzzle game Minesweeper. It provides an interactive, text-based setting for players to experience the game's challenge, where they reveal cells on a grid while avoiding hidden mines. 


Libraries 
1.	Random: The random library in Python is a standard library module that provides functions for generating random numbers and performing various randomization tasks. It is a versatile library that can be used for tasks like generating random numbers, shuffling sequences, selecting random items, and more.
2.	OS Library: The OS library in Python is a standard library module that provides a platform-independent way to interact with the operating system. It allows you to perform various operating system-related tasks, such as working with files and directories, executing system commands, and accessing environment variables. The os module is an essential part of many Python programs that need to interact with the file system or manage system-related tasks.


Code Explanations

1.print_grid(grid) is a function to print the game grid.
2.initialize_grid(size, mines) creates the game grid and randomly places mines on it.
3.count_adjacent_mines(grid, row, col) counts the number of adjacent mines to a given cell.
4.reveal_cell(grid, revealed, row, col) is a recursive function that reveals cells and adjacent cells if they are empty.
5.play_minesweeper(size, mines) is the main game loop where the player interacts with the game

About the game:
Minesweeper is a single-player game in which the player has to clear a square grid containing mines and numbers. The player has to prevent himself from landing on a mine with the help of numbers in the neighbouring tiles.
