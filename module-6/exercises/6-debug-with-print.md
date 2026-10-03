# 6 - Debug with print()

**Goal:** Use program output to inspect the state of a program.

The following program is supposed to calculate the total cost of several items:

```python
prices = [2500, 1500, 3000]

total = 0

for price in prices:
    total = price

print("Total:", total)
```

The program runs, but the answer is incorrect.

Use `print()` statements to inspect:

```text
price
total
```

during each loop iteration.

Determine what is happening.

Fix the program.

## Requirements
* File: 6-debug-with-print.py
* Add debugging output.
* Use the output to identify the problem.
* Fix the logical error.
* Remove unnecessary debugging output after fixing the program.

## Questions
1. What value did you expect total to have?
2. What value did it actually have after each iteration?
3. Why was the value being lost?
4. What change fixed the problem?
