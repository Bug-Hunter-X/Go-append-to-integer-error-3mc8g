# Go Append to Integer Error
This example demonstrates a common error in Go: attempting to use the append function on an integer variable. The append function is designed for slices and not for individual integers.

## Bug
The `bug.go` file contains the erroneous code that tries to append to an integer variable.  This results in a compile-time error because integers are not slice types.

## Solution
The `bugSolution.go` file shows the corrected approach. To add a value to an integer, simply use the assignment operator.