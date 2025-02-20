# Go Off-by-One Error

This repository demonstrates a common off-by-one error in Go when iterating over arrays.  The provided code attempts to access an array element outside its bounds, leading to a runtime panic.

The solution demonstrates how to correctly iterate within the array's bounds to avoid this error.

## Bug

The `bug.go` file contains the buggy code. The `for` loop in `main` attempts to iterate beyond the valid indices of the array, resulting in an index out of range error.

## Solution

The `bugSolution.go` file provides a corrected version of the code. The loop condition is modified to prevent accessing elements outside of the array's valid range. 
