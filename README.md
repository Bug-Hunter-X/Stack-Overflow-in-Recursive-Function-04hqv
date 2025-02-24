# Hack Recursion Bug

This repository contains a simple Hack program that demonstrates a common error: stack overflow due to unbounded recursion.  The `foo` function calculates the factorial, but lacks proper handling for negative inputs or a termination condition, leading to a stack overflow for larger input values.

The `bug.hack` file contains the buggy code. The `bugSolution.hack` file provides a corrected version that handles both negative input and the termination condition for the recursion.

This example highlights the importance of carefully considering base cases and potential infinite recursion when writing recursive functions.