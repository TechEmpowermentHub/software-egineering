# 2 - Fix the Runtime Error

**Goal:** Understand runtime errors.

The following program contains a runtime error:

```python
age = int(input("Enter your age: "))

print("Next year you will be", age + 1)
```

Run the program using:

```text
20
```

Then run it using:

```text
twenty
```

## Questions
1. What happens with 20?
2. What happens with twenty?
3. What type of error occurs?
4. Why does the error occur?
5. What could the program do to handle the invalid input?

Modify the program so that invalid input does not cause the program to crash.

## Requirements
* File: 2-runtime-error.py
* Test valid input.
* Test invalid input.
* Explain the cause of the original error.
* Handle the invalid input appropriately.
