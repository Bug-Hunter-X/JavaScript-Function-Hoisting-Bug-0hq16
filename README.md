# JavaScript Function Hoisting Bug

This repository demonstrates a common JavaScript bug related to function hoisting. Function hoisting is a JavaScript mechanism where declarations are moved to the top of their scope before code execution. While this can be useful, it can also lead to unexpected results if not carefully managed.

## Bug Description

The `bug.js` file shows how re-declaring a function with the same name can change the function's behavior unexpectedly due to hoisting. The first declaration is effectively overridden.

## Solution

The `bugSolution.js` file provides a solution to mitigate this issue. By using function expressions instead of declarations, hoisting is avoided, leading to predictable behavior.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and run the code in a JavaScript environment (browser console, Node.js, etc.).
3. Observe the unexpected output.
4. Open `bugSolution.js` and run the code. Note the correct output.
