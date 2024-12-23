# Uninitialized Map Access in Go

This repository demonstrates a common runtime error in Go: accessing a map before it's initialized.  This simple example showcases the issue and provides a solution.  Uninitialized map access leads to a runtime panic, halting the program's execution.

## Bug
The `bug.go` file contains the erroneous code.  The `main` function attempts to assign a value to a map literal without first initializing it. 

## Solution
The `bugSolution.go` file presents a corrected version.  It initializes the map before use, preventing the runtime panic.