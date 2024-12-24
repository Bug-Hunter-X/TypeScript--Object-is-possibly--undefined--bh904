# TypeScript: Object is possibly 'undefined' Bug

This repository demonstrates a common TypeScript error: 'Object is possibly 'undefined''.  The bug arises when attempting to access a property of a variable that may be undefined or null without proper null or undefined checks.

The `bug.ts` file contains the erroneous code.  The `bugSolution.ts` file provides a corrected version demonstrating how to avoid the error.

This is a frequent issue encountered when working with optional parameters, API responses, or variables that might not always be assigned a value.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository's directory.
3. Compile and run `bug.ts`. You'll observe the TypeScript compiler error.
4. Examine `bugSolution.ts` for the solution and try to compile it.