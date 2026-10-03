# 7 — Handling Errors

**Goal:** Understand why programs can fail and how exceptions work.

Write a program that asks the user for two numbers and divides the first number by the second.

For example:

```text
Enter first number: 20
Enter second number: 5

Result: 4
```

Test the program by entering 0 as the second number.

Observe what happens.

Then modify the program so that it handles the error using try and except.

Instead of crashing, it should display:

`You cannot divide by zero.`

## Requirements
* File: 7-handling-errors.py
* Ask the user for two numbers.
* Convert the input to numbers.
* Perform division.
* Use try and except.
* Handle division by zero.
* Test both valid and invalid input.
