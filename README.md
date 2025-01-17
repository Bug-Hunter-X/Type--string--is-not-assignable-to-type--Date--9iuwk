# Type 'string' is not assignable to type 'Date'

This repository demonstrates a common TypeScript error: Type 'string' is not assignable to type 'Date'.  The error arises when a function expects a Date object as an argument, but a string is provided instead.

## Bug
The `bug.ts` file contains a function `greet` that takes a string and a Date object as arguments. However, the function call passes a string where a Date object is expected, causing a type error.

## Solution
The `bugSolution.ts` file corrects the error by passing a Date object to the `greet` function.

## How to reproduce
1. Clone this repository.
2. Open `bug.ts` in a TypeScript compiler.
3. Attempt to compile. You should see the type error.
4. Open `bugSolution.ts` and observe how the error is resolved.