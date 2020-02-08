# Lesson 2: More on Complexity and Recursions

## Run Time Notations

### Ω Notation
- asymptotic lower bound
- ex
    - f(n) = 3 | f(n) = 4n+2 | f(n) = 2n + 100000000000 *sqrt(n)
        - Ω(1)

### Big O notation
- asymptotically upper bound
- ex
    - f(n) = 3 | f(n) = 4n+2 | f(n) = 2n + 100000000000 *sqrt(n)
        - O(n)

### θ notation
- asymptotically tight bound
    - how it behaves like asymptotically
- ex
    - f(n) = 3 | f(n) = 4n+2 | f(n) = 2n + 100000000000 *sqrt(n)
        - θ(n)

### All 3
- They are used to test a test case
- They do not corrolate to best case/ worst case
    - All of them can be used to determine run time analysis on the best case and worst case

## Recursion
- When a function calls itself over again
- Can be achived by looping and vise versa
