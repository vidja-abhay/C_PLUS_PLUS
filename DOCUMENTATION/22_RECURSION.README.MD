# Recursion

- Recursion is a problem solving technique in which function calls itself untill specified condition is met.

```bash
return_type recursive_func {
    ....
       // Base Condition
       // Recursive Case
       ....
}
```

- Base Condition : The base condition is the condition that is used to terminate the recursion.

- Recursive Case : Recursive case is the way in which the recursive call is present in the function. 

## What is Stack Overflow?

Stack overflow is one of the most common errors associated with the recursion which occurs when a function calls itself too many times. As we know that each recursive call requires separate space in the limited stack memory. When there is a large number of recursive calls or recursion goes on infinite times, this stack memory may get exhausted and may not be able to store more data leading to programs’ termination.

## Applications of Recursion

- Solving: Fibonacci sequences, Factorial Function, Reversing an array, Tower of Hanoi.

- Backtracking: It is a technique for solving problems by trying out different solutions and undoing them if they do not work. Recursive algorithms are often used in backtracking.

- Searching and Sorting Algorithms: Many searching and sorting algorithms, such as binary search and quicksort, use recursion to divide the problem into smaller sub-problems.

- Tree and Graph Traversal: Recursive algorithms are often used to traverse trees and graphs, such as depth-first search and breadth-first search.

- Mathematical Computations: Recursion is also used in many mathematical computations, such as the factorial function and the Fibonacci sequence.

- Dynamic Programming: It is a technique for solving optimization problems by breaking them down into smaller sub-problems. Recursive algorithms are often used in dynamic programming.

## Drawbacks of Recursion

- Performance: Recursive algorithms can be less efficient than iterative algorithms in some cases, particularly if the data structure is large or if the recursion goes too deep.

- Memory usage: Recursive algorithms can use a lot of memory, particularly if the recursion goes too deep or if the data structure is large. Each recursive call creates a new stack frame on the call stack, which can quickly add up to a significant amount of memory usage.
Code complexity: Recursive algorithms can be more complex than iterative algorithms.

- Debugging: Recursive algorithms can be more difficult to debug than iterative algorithms, particularly if the recursion goes too deep or if the program is using multiple recursive calls.

- Stack Overflow: If the recursion goes too deep, it can cause a stack overflow error, which can crash the program.

## Summary 

- There are two types of cases in recursion i.e. recursive case and a base case.
- Infinite recursion may lead to running out of stack memory.
- Each recursive call makes a new copy of that method in the stack memory.
- The base case is used to terminate the recursive function when the case turns out to be true.
- Examples of Recursive algorithms: Merge Sort, Quick Sort, Tower of Hanoi, Fibonacci Series, Factorial Problem, etc.