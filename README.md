# Tcl Recursive Function Stack Overflow Bug

This repository demonstrates a common error in Tcl: a stack overflow caused by an incorrectly implemented recursive function. The `bug.tcl` file contains the buggy code, while `bugSolution.tcl` provides the corrected version.

The bug is a missing base case, leading to infinite recursion.  The solution adds a proper base case to stop the recursion appropriately. 

## How to Reproduce

1. Clone this repository.
2. Run `tclsh bug.tcl`. You should observe a stack overflow error.
3. Run `tclsh bugSolution.tcl`. This should execute without error and print the correct result.