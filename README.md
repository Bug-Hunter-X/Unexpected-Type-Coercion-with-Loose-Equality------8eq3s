# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug caused by the loose equality operator (`==`).  Loose equality performs type coercion before comparison, which can lead to unexpected results and difficult-to-find bugs.

## The Bug
The `bug.js` file contains a function that uses loose equality to compare values.  This can lead to unexpected behavior when comparing values of different types.

## The Solution
The `bugSolution.js` file shows how to fix the bug by using strict equality (`===`). Strict equality does not perform type coercion, resulting in more predictable behavior.  Alternatively, explicit type checking can be used to handle potential null values. 