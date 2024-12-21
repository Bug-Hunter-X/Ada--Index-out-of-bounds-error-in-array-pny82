# Ada Array Indexing Bug
This repository demonstrates a common error in Ada programming: accessing an array element outside its defined bounds.  Ada arrays are 1-based, meaning the first element is at index 1, not 0 as in some other languages (like C or Python). This example shows how to correct the problem by ensuring proper bounds checking.

## Bug Description
The `bug.ada` file contains code that attempts to access array elements beyond the valid range. This results in a runtime `CONSTRAINT_ERROR`. 

## Solution
The `bugSolution.ada` file shows the corrected code using Ada's array indexing which starts from 1. 