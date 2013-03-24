
Sudoku solver 1.0 (11-10-11 — it's not a binary value :O)

Requirements
============

- Minisat
- Python 2


Usage
=====

cat input.file | python2 ./sudoku.py


Input
=====

Input is a text matrix 9x9; every char is 1-9 char or space ' ' (unknown values).

See input.sample


Note
====

During execution *problem.minisat* and *solution.minisat* files are created; you can find there the SAT equivalent problem and solution.
At the end of *problem.minisat* there is a table with the meaning of variables.

Happy Cheating ^.^

Martiño
