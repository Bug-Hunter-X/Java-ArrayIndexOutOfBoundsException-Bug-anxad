# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java programming error: an `ArrayIndexOutOfBoundsException`. The code attempts to access an array element beyond its valid index range, leading to a runtime exception.

## Bug Description

The `bug.java` file contains a `for` loop that iterates one element beyond the array's length, causing an `ArrayIndexOutOfBoundsException` when trying to access `arr[5]` which is outside of the bounds of the array with size 5 (valid indices are 0-4).

## Solution

The `bugSolution.java` file provides a corrected version of the code. The loop condition is changed to `i < arr.length` to prevent accessing the out-of-bounds element. This ensures that the loop iterates only within the valid index range of the array.
