```
CL-USER> (push "~/advent_of_code_2017/nja-commonlisp/" asdf:*central-registry*)
("~/advent_of_code_2017/nja-commonlisp/"
 #P"C:/Users/Johan/quicklisp/quicklisp/")
CL-USER> (ql:quickload :advent-of-code)
To load "advent-of-code":
  Load 1 ASDF system:
    advent-of-code
; Loading "advent-of-code"
..................................................
[package aoc].....................................
[package aoc2017.day01]...........................
[package aoc2017.day02]...........................
[package aoc2017.day03]...........................
[package aoc2017.day04]...........................
[package aoc2017.day05]...........................
[package aoc2017.day06]...........................
[package aoc2017.day07]...........................
[package aoc2017.day08]...........................
[package aoc2017.day09]...........................
[package aoc2017.day10]...........................
[package aoc2017.day11]...........................
[package aoc2017.day12]...........................
[package aoc2017.day13]...........................
[package aoc2017.day14]...........................
[package aoc2017.day15]...........................
[package aoc2017.day15.alt].......................
[package aoc2017.day16]...........................
[package aoc2017.day17]...........................
[package aoc2017.day18]...........................
[package aoc2017.day19]...........................
[package aoc2017.day20]...........................
[package aoc2017.day21]...........................
[package aoc2017.tests]........
(:ADVENT-OF-CODE)
CL-USER> (fiasco:all-tests)
ALL-TESTS (Suite)
  AOC2017.TESTS (Suite)
    DAY01                                                                 [ OK ]
    DAY02                                                                 [ OK ]
    DAY03                                                                 [ OK ]
    DAY04                                                                 [ OK ]
    DAY05                                                                 [ OK ]
    DAY06                                                                 [ OK ]
    DAY07                                                                 [ OK ]
    DAY08                                                                 [ OK ]
    DAY09                                                                 [ OK ]
    DAY10                                                                 [ OK ]
    DAY11                                                                 [ OK ]
    DAY12                                                                 [ OK ]
    DAY13                                                                 [ OK ]
    DAY14                                                                 [ OK ]
    DAY15                                                                 [ OK ]
    DAY15.ALT                                                             [ OK ]
    DAY16                                                                 [ OK ]
    DAY17                                                                 [ OK ]
    DAY18                                                                 [ OK ]
    DAY19                                                                 [ OK ]
    DAY20                                                                 [ OK ]
    DAY21                                                                 [ OK ]

T
(#<test-run of ALL-TESTS: 24 tests, 44 assertions, 0 failures in 7.359 sec>)
CL-USER>
```
