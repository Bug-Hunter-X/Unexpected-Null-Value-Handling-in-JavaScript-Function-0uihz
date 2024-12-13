# Unexpected Null Value Handling in JavaScript Function

This repository demonstrates a common issue in JavaScript functions when dealing with null values. The `foo` function is designed to add two numbers, but it might produce unexpected results if null is passed as an argument.  This example highlights the importance of explicit null checks for robust code.

## Bug

The `bug.js` file contains the function that exhibits unexpected behavior.  When null is passed as an argument, it might cause unexpected behavior or errors in some situations.

## Solution

The `bugSolution.js` file provides a corrected version of the function, incorporating robust null checks to handle null values gracefully.  The improved function returns 0 when null values are encountered, ensuring consistent behavior.

## How to reproduce

1. Clone this repository.
2. Navigate to the repository directory.
3. Run `node bug.js` to see the unexpected behavior.
4. Run `node bugSolution.js` to see the solution.