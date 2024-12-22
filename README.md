# MongoDB $inc operator error: Incorrect usage with string value

This repository demonstrates an uncommon error when using the `$inc` operator in MongoDB update queries. The error occurs when providing a string value instead of a numerical value to the `$inc` operator.

## Bug
The `bug.js` file contains a MongoDB query that attempts to increment a field using a string value. This results in an unexpected error because the `$inc` operator expects a numerical value.

## Solution
The `bugSolution.js` file provides the correct usage of the `$inc` operator. It uses a numerical value to increment the field successfully.