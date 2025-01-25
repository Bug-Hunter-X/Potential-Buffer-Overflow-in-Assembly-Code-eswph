# Assembly Buffer Overflow Bug

This repository demonstrates a potential buffer overflow bug in a small piece of assembly code. The code attempts to increment a value stored in memory, but fails to check for potential overflow, which can lead to unexpected behavior or crashes.  The solution provides a safer version with bounds checking.

## Bug Description:
The original code, in `bug.asm`, attempts to increment a value pointed to by a memory address.  However, this fails to check whether the incrementation causes an overflow beyond the allocated buffer.  This is a common vulnerability leading to security issues and program crashes.

## Solution:
The solution, in `bugSolution.asm`, adds necessary checks to avoid such issues. This is crucial for robust and secure code.