# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB to increment a counter.  The error occurs when providing a string value instead of a number to the `$inc` operator in `updateOne` operation.

## Bug

The `bug.js` file shows incorrect usage resulting in an error.  The `$inc` operator is provided with a string value instead of a number.

## Solution

The `bugSolution.js` file provides the corrected implementation. The correct usage involves providing a numeric value to increment the counter field.
