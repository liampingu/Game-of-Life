# Conway's Game of Life

The Game of Life is a cellular automaton created by John H. Conway in 1970. The game is a zero-player game in which an initially configured 2D grid of cells evolves according to the Game of Life [ruleset](#Ruleset).

Built using Python 3.5, this implementation of Conway's Game of Life allows the user to easily run the Game of Life using a 2D grid of choosen number of rows and columns in either a Linux or Windows terminal/console.

This project is licensed under the terms of the MIT license.

## Ruleset

Using the following ruleset the 2D grid of cells will evolve from generation to generation until it reaches a static state of either all dead cells or a mix of still, oscillating, or moving (spaceship) cells.

1. _**Underpopulation**_ - If a live cell has is surrounded by less than two surrounding neighbours it dies and does not make it to the next generation.
2. _**Equilibrium**_ - If a live cell is surrounded by two or three living neighbors the cell stays alive and makes it to the next generation.
3. _**Overpopulation**_ - If a live cell is surrounded by more than three living neighbors the cell dies and does not make it to the next generation.
4. _**Reproduction**_ - If a dead cell is surrounded by three living neighbors the cell stays alive and makes it to the next generation.

## How to Run

Get started with `python3 main.py 50 50 15` to run the Game of Life with 50 rows, 50 columns and starting density of 15%.
