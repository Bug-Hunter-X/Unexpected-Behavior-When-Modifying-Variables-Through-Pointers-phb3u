# Unexpected Behavior When Modifying Variables Through Pointers
This repository demonstrates a potential issue when modifying variables in C using pointers. While the example is simple, it highlights a common source of errors that can be difficult to debug in larger projects.

## The Problem
The `bug.c` file contains a seemingly simple program that modifies a variable using a pointer.  This approach, while valid, can become problematic when dealing with more complex data structures or memory management.

## The Solution
The `bugSolution.c` file illustrates improved practices to avoid unexpected behavior while working with pointers.  This might involve careful checks to ensure that pointer operations are performed within valid memory boundaries and utilizing const pointers where appropriate to prevent accidental modification.

## How to Reproduce
1. Clone the repository.
2. Compile the `bug.c` file using a C compiler (e.g., GCC). 
3. Run the executable. Observe the output. 
4. Repeat steps 2-3 for `bugSolution.c`.  Compare the outputs to understand the difference.

## Lessons Learned
This simple example helps illustrate the importance of understanding how pointers work in C and potential problems if they are not handled carefully.