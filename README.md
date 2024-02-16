# Conway's Game of Life

The Game of Life, also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input.

## Rules

There are an infinite number of cells. Every cell can interact with its neighbor (8 cells).

At each new generation the following rules apply:

Live cell:
- Fewer than 2 live neighbors, it dies. < 2
- More than 3 live neighbors, it dies. > 3
- 2 or 3 live neighbors, survives. 2 or 3

Dead cell:
- Exactly 3 live neighbors, it lives!

First generation is created by applying these rules to every cell in seed:
- Births and deaths apply across all cells in tandem (a tick)
