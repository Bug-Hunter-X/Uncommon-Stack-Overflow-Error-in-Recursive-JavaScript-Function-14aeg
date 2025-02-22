# Uncommon Stack Overflow Error in Recursive JavaScript Function

This repository demonstrates a subtle stack overflow error in a seemingly simple recursive JavaScript function.  The function `foo` calculates a result based on its input parameters `a` and `b`.  The issue arises when negative numbers are passed as arguments because the recursion condition is never met, resulting in continuous function calls that eventually exceed the call stack limit.

**Key Point:** The error is not immediately obvious because the function works correctly for non-negative inputs.

The `bug.js` file contains the buggy code. The solution, `bugSolution.js`, addresses this issue with proper input validation and handling of negative values.