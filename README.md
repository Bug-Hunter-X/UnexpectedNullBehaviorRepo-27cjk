# JavaScript Bug: Loose Equality in Null Check

This repository demonstrates a common JavaScript bug involving loose equality (==) when checking for null values.  The bug can cause unexpected results if input values are loosely equal to null, but not strictly null.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file shows the corrected version using strict equality (===).

## Bug Description
The original code uses loose equality (==) to check for null values. This can lead to incorrect results if the inputs are not strictly null but are loosely equal to null (e.g., 0 == false). The corrected code uses strict equality (===) to avoid this issue.