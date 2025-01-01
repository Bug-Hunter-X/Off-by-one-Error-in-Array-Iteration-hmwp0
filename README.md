# Off-by-one Error in TypeScript Array Iteration

This repository demonstrates a common off-by-one error in TypeScript when iterating over arrays.  The error occurs because the loop condition `i <= arr.length` accesses an index beyond the valid range of the array, resulting in `undefined` being logged or, potentially, a runtime error depending on how the code handles undefined values.

The `bug.ts` file shows the erroneous code.  The corrected code is provided in `bugSolution.ts`, demonstrating the correct use of `<` rather than `<=` in the loop condition.