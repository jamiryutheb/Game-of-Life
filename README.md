# Conway's Game of Life

The Game of Life, also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a **zero-player game**, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves.


## Rules

The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead (or populated and unpopulated, respectively). Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

- Any **live** cell with **fewer than two live neighbours** dies, as if by **underpopulation.**
- Any **live** cell with **two or three live neighbours** lives on to the next generation.
- Any **live** cell with **more than three live neighbours** dies, as if by **overpopulation.**
- Any **dead** cell with **exactly three live** neighbours becomes a live cell, as if by **reproduction.**

These rules, which compare the behaviour of the automaton to real life, can be condensed into the following:

- Any live cell with two or three live neighbours survives.
- Any dead cell with three live neighbours becomes a live cell.
- All other live cells die in the next generation. Similarly, all other dead cells stay dead.


## How it works?

We can change the rules in this version of the program;

|                |Description                          |Default|
|----------------|------------------------------------|-----------------------------|
|Lower Bound 	 |`Controls the underpopulation rule` | 2|
|Upper Bound     |`Controls the overpopulation rule`  | 3|
|Populate        |`Determines the reproduction rule`  | 3|

## Preview

![GoL-def](https://user-images.githubusercontent.com/48869563/218652910-dfe68add-9d5d-4827-bb99-c966dae01f45.gif)
![GoL-rul](https://user-images.githubusercontent.com/48869563/218654056-a602bbe5-18e9-48a1-83cd-ba6aef4f606a.gif)

