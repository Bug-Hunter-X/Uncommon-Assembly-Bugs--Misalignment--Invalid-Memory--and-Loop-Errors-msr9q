# Uncommon Assembly Language Bugs

This repository demonstrates three uncommon errors that can occur in assembly language programming. These errors are often subtle and difficult to debug. 

The code examples highlight potential issues with memory alignment, invalid memory access, and loop counter initialization.  Understanding these potential pitfalls is vital for writing robust and reliable assembly code.

## Bugs Demonstrated

1. **Misaligned Memory Access:** Accessing memory that is not properly aligned to the data type's size (e.g., trying to access a 4-byte integer at an odd address) can lead to segmentation faults or unpredictable behavior.

2. **Invalid Memory Address:** Dereferencing a pointer that points to an invalid memory location (e.g., a null pointer or an address outside the program's allocated memory space) is a frequent cause of crashes.

3. **Incorrect Loop Counter Initialization:**  A problem with initializing or updating the loop counter can cause unexpected loop behavior, such as infinite loops or premature termination.

## Solutions

The `bugSolution.asm` file provides corrected versions of the code, addressing the issues identified in `bug.asm`.