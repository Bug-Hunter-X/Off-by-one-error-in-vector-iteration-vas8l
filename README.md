# Off-by-One Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`. The error occurs because the loop condition `i <= v.size()` attempts to access an element beyond the valid range of the vector, leading to undefined behavior.

The solution shows how to correctly iterate using `i < v.size()`.

## Bug

The `bug.cpp` file contains the code with the off-by-one error.  Running this code will result in undefined behavior, likely a crash or incorrect output. 

## Solution

The `bugSolution.cpp` file provides a corrected version of the code.