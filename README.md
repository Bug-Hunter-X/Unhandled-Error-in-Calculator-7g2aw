# Unhandled Error in Calculator

This repository demonstrates an example of an unhandled error in a simple calculator program written in JavaScript.

## Bug Description

The `divide` function in `calculator.js` throws an error if the divisor is zero.  However, there is no error handling implemented, leading to a potential crash if the function is called with a divisor of zero.

## Bug Solution

The `calculatorSolution.js` file shows a corrected version that handles the division by zero error using a `try...catch` block.

## How to run the code

1. Clone the repository.
2. Navigate to the repository directory.
3. Run `node calculator.js` and `node calculatorSolution.js` to see the error and solution respectively.

This example highlights the importance of proper error handling to ensure application robustness and prevent unexpected crashes.