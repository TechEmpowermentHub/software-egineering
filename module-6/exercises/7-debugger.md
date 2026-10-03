# 7 - Debug Using the Debugger

**Goal:** Learn to inspect program execution using a debugger.

Use the following program:

```python
balance = 100000

withdrawal = int(input("Amount to withdraw: "))

if withdrawal <= balance:
    balance = balance - withdrawal
    print("Withdrawal successful.")
else:
    print("Insufficient funds.")

print("Balance:", balance)
```

Set a `breakpoint` before the withdrawal calculation.

Run the program using:

```text
25000
```

Use the debugger to inspect:

```text
balance
withdrawal
```

Step through the program line by line.

Then repeat with:

```text
150000
```

## Requirements
* File: 7-debugger.py
* Set a breakpoint.
* Run the program using the debugger.
* Inspect variable values.
* Step through the program.
* Explain how the program behaves in both cases.
