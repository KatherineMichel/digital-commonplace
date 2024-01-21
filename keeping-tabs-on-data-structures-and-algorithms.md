# Data Structures and Algorithms

## Algorithmic Paradigms

List of Algorithmic Paradigms
* [Algorithmic Paradigms Wikipedia](https://en.wikipedia.org/wiki/Algorithmic_paradigm#General)

Algorithmic Paradigms (Greedy versus Dynamic, Dynamic versus Divide and Conquer)
* [Greedy Algorithm Wikipedia](https://en.wikipedia.org/wiki/Greedy_algorithm)
* [Dynamic Programming Wikipedia](https://en.wikipedia.org/wiki/Dynamic_programming)
* [Divide and Conquer Wikipedia](https://en.wikipedia.org/wiki/Divide-and-conquer_algorithm)

Algorithmic Paradigms
* [Prune and Search Wikipedia](https://en.wikipedia.org/wiki/Prune_and_search)
* [Brute Force Search Wikipedia](https://en.wikipedia.org/wiki/Brute-force_search)
* [Backtracking Wikipedia](https://en.wikipedia.org/wiki/Backtracking)
* [Branch and Bound Wikipedia](https://en.wikipedia.org/wiki/Branch_and_bound)

Three Types of Problems in Backtracking
* [Decision Problem Wikipedia](https://en.wikipedia.org/wiki/Decision_problem)
* [Optimization Problem Wikipedia](https://en.wikipedia.org/wiki/Optimization_problem)
* Enumeration Problem

Strings
* [String Algorithm Wikipedia](https://en.wikipedia.org/wiki/String_algorithm)
* [String Searching Algorithm Wikipedia](https://en.wikipedia.org/wiki/String-searching_algorithm)

## Algorithmic Paradigms- Dynamic Programming

* [Optimal Substructure Wikipedia](https://en.wikipedia.org/wiki/Optimal_substructure)
* [Overlapping Subproblems Wikipedia](https://en.wikipedia.org/wiki/Overlapping_subproblems)

## Algorithmic Paradigms- Recursion

See also: Al Sweigart's book The Recursive Book of Recursion

Recursion and Base Case
* [Recursion Wikipedia](https://en.wikipedia.org/wiki/Recursion_(computer_science))
* [Base Case Wikipedia](https://en.wikipedia.org/wiki/Recursion#base_case)

Top-Down and Bottom-Up Design
* Top-down: takes a large problem and divides it into smaller overlapping subproblems
* Bottom-up: starts with the smaller subproblems (often related to the base case) and “builds up” to the solution of the original, large problem
* All recursion is top-down (the term top-down recursion is redundant), and no bottom-up approach uses recursion
* [Top-Down and Bottom-Up Design Wikipedia](https://en.wikipedia.org/wiki/Top-down_and_bottom-up_design)

Dynamic Programming (break a large program into overlapping subproblems, dynamic programming uses recursion with repeated recursive cases; these are the overlapping subproblems)
* [Dynamic Programming Wikipedia](https://en.wikipedia.org/wiki/Dynamic_programming)

Memoization (a common strategy in dynamic programming, using recursion with memoization is top-down dynamic programming)
* Only pure functions (functional programming) should be memoized
* [Memoization Wikipedia](https://en.wikipedia.org/wiki/Memoization)

Functional Programming
* [Functional Programming Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)
* [Side Effect Wikipedia](https://en.wikipedia.org/wiki/Side_effect_(computer_science))

<!--
The iterative Fibonacci algorithm is an example of bottom-up dynamic programming. 

bottom-up- a benefit is code reuse
https://en.wikipedia.org/wiki/Code_reuse

https://docs.python.org/3/library/functools.html#functools.cache
-->

## Recursive, Divide-and-Conquer Algorithms

Dynamic programming techniques aren’t applied to these sorting algorithms, because they are unique: their subproblems do not overlap
* [Merge Sort Wikipedia](http://en.wikipedia.org/wiki/Merge_sort)
* [Quicksort Wikipedia](http://en.wikipedia.org/wiki/Quicksort)
