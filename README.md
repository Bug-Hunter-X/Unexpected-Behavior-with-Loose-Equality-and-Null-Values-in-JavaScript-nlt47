# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug involving loose equality (==) and null values.  The `foo` function adds two numbers, but unexpected results occur if either input is null.  The solution explicitly checks for null values before performing the addition.

## Bug
The original `foo` function uses loose equality, which can lead to unexpected comparisons.  See `bug.js` for the buggy code.

## Solution
The solution involves explicitly checking for null values before performing the addition. This approach ensures that null values are handled gracefully and that the expected result is returned.  See `bugSolution.js` for the corrected code.