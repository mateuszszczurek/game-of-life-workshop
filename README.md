# game.of.life
Objective of this task is to write Conway's Game of Life using the TDD approach.

https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

Given:
The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead, or "populated" or "unpopulated" (the difference may seem minor, except when viewing it as an early model of human/urban behavior simulation or how one views a blank space on a grid). Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

* Any live cell with fewer than two live neighbours dies, as if caused by under-population.
* Any live cell with two or three live neighbours lives on to the next generation.
* Any live cell with more than three live neighbours dies, as if by over-population.
* Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed—births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick (in other words, each generation is a pure function of the preceding one). The rules continue to be applied repeatedly to create further generations.

---

# Test Driven Development

https://en.wikipedia.org/wiki/Test-driven_development

* Add a test
* Run all tests and see if the new test fails
* Write the code
* Run tests
* Refactor code

Books:

https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530
https://www.manning.com/books/the-art-of-unit-testing-second-edition

Exercises:

http://osherove.com/tdd-kata-1/
https://github.com/garora/TDD-Katas

---

Some bits of BDD:
* introducing ubiquitous language
* specification vocabulary
* tools: Core Java, JUnit, Hamcrest