# Missing Curly Braces in Tcl if Statement

This repository demonstrates a common error in Tcl programming: forgetting to enclose the conditional expression in curly braces within an `if` statement.  This seemingly minor omission leads to a syntax error that can be difficult to track down for beginners.

The `bug.tcl` file contains the erroneous code. The `bugSolution.tcl` file shows the corrected version.

## Bug

The problem lies in the `badproc` procedure.  The `if` statement lacks the necessary curly braces around the comparison `$x == 0`.

## Solution

Simply adding curly braces around the comparison fixes the issue.