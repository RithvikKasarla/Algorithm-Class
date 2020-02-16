# Lesson 3: Recursion and Divide & Conque

## Recursion
- when a function calls itself
- can be solved thouigh 
    - recursion trees
    - guessing
    - induction
        - A mathical proof technique that can help prove a statement about an equation or set of items.
### Recursion Tree
- A type of tree where each node is when the function call itself
- Has a height and nodes
- Can be used in order to "solve" or analyze a recursive function

### induction
- Step 1:
    - Check your Base case (the smallest value in teh statement)
- Step 2:
    - Create an Induction hypothesis
        - assume the statement works if a value n (input value) is less than k(some number)
- Step 3:
    - Induction Step
        - Check if the statement works if n is equal to k+1.
 - n & k stay as variables dont make them acutall numbers


 ## Divide and Conquer
 - Divide 
    - break up the problem into smalled subproblems
 - Conque
    - solve the subproblems recursivly
    - can be small enough where they are the base case(smalled possible input)
- Combine
    - combine the solutions of all the individual smalled sub problems