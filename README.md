# SAT Nonograms

A SAT-based solver for [nonograms](https://en.wikipedia.org/wiki/Nonogram), for
the Advanced Algorithms course at Olin College of Engineering.

Usage:
```shell
python3 -m pip install -r requirements.txt
./nonogram.py nonogram_problems.txt
```

An example solved nonogram:
```
. . . . . . . . . . . . . . . . . . . . # # # # #  5
. . # # . . . . . . . . . . . . . . # # # . . # #  2 3 2
. # # . . . . . . . . . . . . . . # # # # # . . #  2 5 1
# # . . . . . . . . . . . . . # # # # # # # # . .  2 8
# # . . . . # # # # # . # # # # # # # # # # # . .  2 5 11
# . # . . # # . . . . # . . . . # # # # # # . . .  1 1 2 1 6
# . . # # . . . . . # . . . . . . . # # # . . . .  1 2 1 3
# # . . . . . . . . # . . . . . . . . . . . . . #  2 1 1
. # # . . . . . # # # # # # . . . . . . . . . # #  2 6 2
. . # # # # # # # # # # # # # # # . . . . # # # #  15 4
. . . . . # # # # # # # # # # . . # # # # # # # #  10 8
. . . . # # . # . # # # # . # # # . . # # # # # #  2 1 4 3 6
. . . . . . . . # # # # # # # # # # # # # # # # #  17
. . . . . . . . # # # # # # # # # # # # # # # # #  17
. . . . . . . # # # # # # # # # # # # # # # # # #  18
. . . . . . . # . . . # # # # # # # # # # # # # #  1 14
. . . . . . . # . # . # # # # # # # # # # # # # #  1 1 14
. . . . . . . . # # # # # . . . # # # # # # # # #  5 9
. . . . . . . . . . . . . . . . . # # # # # # # #  8
. . . . . . . . . . . . . . . . . . # # # # # # #  7
5 3 2 1 1 1 2 1 1 1 1 1 1 1 1 2 3 4 6 6 7 1 1 2 3
  2 1 1 1 3 2 3 3 7 9 10 10 3 8 1 1 1 1 10 10 4 2 12 13
    2 1 1     3 3 2 1     5   6 7 7 8     11 11
                1
```