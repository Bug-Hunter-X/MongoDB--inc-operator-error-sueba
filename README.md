# MongoDB $inc Operator Error

This repository demonstrates an example of an incorrect usage of the `$inc` operator in MongoDB and shows the correct way to fix it.

## Bug Description
The issue lies in the usage of the `$inc` operator within a MongoDB update operation. In the original code, a string value is used for the increment, leading to an error. The `$inc` operator requires a numeric value to successfully increment a field.

## Bug Solution
The bug is fixed by replacing the string value ("1") with a numeric value (1). This corrects the usage of the `$inc` operator, allowing for a successful update operation.

## How to Reproduce
1. Clone the repository
2. Set up a MongoDB connection.
3. Run the `bug.js` script to trigger the error.
4. Run the `bugSolution.js` script to see the correct implementation.
