# 5 - Trace the Program

**Goal:** Use manual tracing to find where program behavior changes from expected behavior.

Consider:

```python
total = 0

for number in range(1, 6):
    total = total + number

print("Total:", total)
```

Before running the program, create a table:

```text
number    total
------    -----
1         ?
2         ?
3         ?
4         ?
5         ?
```

Fill in the values.

Then predict the output.

Run the program and compare your prediction.

## Extension

Change the program to calculate the total of numbers from 1 to 10.

Trace the program again.

## Requirements
* File: 5-trace-the-program.py
* Write the trace as comments.
* Predict the output before running the program.
* Compare the prediction with the actual output.
