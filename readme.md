# Game of Life.c

A simple implementation of Conway's Game of Life in C.

## How to use

1. Compile the program with `gcc -o run run.c`
2. Run the program with `./run`

## How it works

The program uses a 2D array to represent the grid of cells. Each cell is
either alive (represented by a `#` character) or dead (represented by a
space character). The program then iterates over the grid, applying the
rules of the Game of Life to determine the state of each cell in the next
generation.

## Rules of the Game of Life

The rules of the Game of Life are as follows:

1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

## Configuration

The program can be configured by modifying the following constants at the
top of the file:

* `WIDTH`: the width of the grid
* `HEIGHT`: the height of the grid
* `ITERATION`: the number of iterations to run the program for
* `SPEED`: the number of milliseconds to wait between each iteration

## Acknowledgments

This program was written by MUCKA & comment by Codeium AI. The Game of Life was invented by John Conway.
