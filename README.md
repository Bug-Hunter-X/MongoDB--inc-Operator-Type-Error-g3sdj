# MongoDB $inc Operator Type Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The error arises from providing a string value to the `$inc` operator instead of a number. This will prevent the correct increment operation.

The `bug.js` file shows the incorrect code and the `bugSolution.js` provides the corrected solution.  Understanding the expected data type is crucial for avoiding this type of error.
