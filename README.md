# Subtle Pointer Arithmetic Bug in C

This repository demonstrates a common, yet subtle, bug related to pointer arithmetic in C. The code appears simple, but contains a potential issue that can be easily missed.

## Bug Description

The core issue lies in the understanding and proper use of pointers, specifically how they interact with memory addresses and data manipulation. The example might seem straightforward, but the hidden potential for error exists, particularly for developers new to C or those who are not fully versed in memory management.

## How to Reproduce

1. Clone this repository.
2. Compile the `bug.c` file using a C compiler (like GCC).
3. Run the executable.
4. Observe the output and compare it to the expected behavior.

## Solution

The `bugSolution.c` file provides a corrected version of the code, demonstrating the proper use of pointer arithmetic.  The solution highlights the importance of paying close attention to memory addresses and data types when using pointers.

## Learning Points

This simple example serves as a valuable learning opportunity. It emphasizes the necessity of:

*   A thorough understanding of C's memory model.
*   Careful consideration of pointer arithmetic and its potential pitfalls.
*   Thorough testing to uncover unexpected behavior.