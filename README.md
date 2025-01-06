# RecursionError in Python Factorial Function
This example demonstrates a common error in Python: the RecursionError.  It occurs when a recursive function calls itself infinitely, exceeding Python's maximum recursion depth.  The `factorial` function below correctly calculates factorials for non-negative integers, but it fails for negative input.

The solution involves adding a base case to handle the invalid negative input, gracefully handling the error instead of letting it crash the program.