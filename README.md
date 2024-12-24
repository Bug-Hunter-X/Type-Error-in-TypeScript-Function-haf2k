# Type Error in TypeScript Function
This example demonstrates a common type error in TypeScript that arises from attempting to add a number and a string directly.  The function `combine` is intended to add two numbers but accepts a string as a parameter, causing a type error.

## How to Reproduce
1. Compile the TypeScript code in `bug.ts`.
2. Observe the type error indicating an incompatible addition operation. 

## Solution
The solution involves explicit type conversion to ensure both operands are of the same type before performing the addition, as shown in `bugSolution.ts`.