# JavaScript Null Handling Bug

This repository demonstrates a common, yet subtle, bug in JavaScript related to null value handling within a simple addition function.

## The Bug
The `foo` function is intended to add two numbers. However, it incorrectly handles cases where one of the inputs is `null`.  Instead of throwing an error or returning a default value (such as 0), it simply returns `null` causing unexpected behavior.

## The Solution
The solution provides improved error handling and a more robust approach to handling potential `null` inputs.  It checks for null values and handles them appropriately returning 0 for null input and otherwise performing the addition.

## How to Reproduce
1. Clone this repository.
2. Navigate to the directory.
3. Run `node bug.js` to see the erroneous behavior.
4. Run `node bugSolution.js` to see the corrected behavior.