# Time Complexity

- A measure of the amount of time an algorithm takes to run, depending on the amount of data the algorithm is working on.

- T.C != time taken

## Asymptotic Notation

- Asymptotic notation is used to describe the time complexity of an algorithm when the input size grows very large.

- **Big O Notation (O)** : Describes the worst-case scenario. It tells you the maximum amount of time an algorithm will take as the input size grows. It focuses on the upper bound of performance.

- **Big Omega Notation (Ω)** : Describes the best-case scenario. It tells you the minimum amount of time an algorithm will take, giving the lower bound of performance.

- **Big Theta Notation (Θ)** : Describes the average-case scenario or the tight bound. It shows that the algorithm will always take time that grows at a specific rate, no matter the input. It provides both the upper and lower bounds.

## Type of T.C.

- **O(1) – Constant Time** : The algorithm takes the same amount of time to execute, regardless of the input size. 
  - Example : Accessing an element in an array by its index.

- **O(log n) – Logarithmic Time** : The algorithm reduces the size of the problem with each step, usually by half, so the time grows slowly as the input grows.
  
  - Example : Binary Search

- **O(n) – Linear Time** : The time it takes grows directly in proportion to the size of the input. If the input doubles, the time doubles.

  - Example : Linear Search 

- **O(n log n) – Log-linear Time** : This complexity comes from algorithms that involve sorting or dividing the problem into smaller parts, then processing each part.

  - Example : Merge Sort

- **O(n²) – Quadratic Time** :  The time grows as the square of the input size. If the input doubles, the time grows four times.

  - Example : Bubble Sort

- **O(n³) – Cubic Time** : The time grows as the cube of the input size. If the input doubles, the time increases eight times.

- **O(2ⁿ) – Exponential Time** : The time doubles with each additional element in the input. If the input increases by 1, the time required doubles.

  - Example : Fibonacci Sequence (Recursive)

- **O(n!) – Factorial Time** : The time grows very quickly as the input size increases. It involves generating all possible permutations or combinations.

  - Example : Traveling Salesman Problem (Brute Force)

## T.C for Problem Solving

- 1 second time of machine = 10^8 Iteration of code

- n > 10^8 : O(logn), O(1)

- n <= 10^8 : O(n)

- n <= 10^6 : O(n*logn)

- n <= 10^4 : O(n^2)

- n <= 500 : O(n^3)

- n <= 25 : O(2^n)

- n <= 12 : O(n!)