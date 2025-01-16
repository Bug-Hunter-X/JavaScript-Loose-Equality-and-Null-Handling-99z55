# JavaScript Loose Equality and Null Handling

This example demonstrates a common issue in JavaScript related to loose equality (`==`) and null value handling.  Improper handling of null values can lead to unexpected behavior or runtime errors.

The `bug.js` file contains a function that attempts to add two numbers, but it doesn't correctly handle cases where one or both inputs are null.

The `bugSolution.js` file provides a corrected version of the function, using strict equality (`===`) to compare values and explicitly checking for null values before performing the addition.

This is a simple example, but it highlights an important best practice in JavaScript development: always explicitly handle null values to prevent unexpected results.