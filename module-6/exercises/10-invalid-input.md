# 10 - Test Invalid Input

**Goal:** Identify inputs that can cause a program to fail.

Consider:

```python
age = int(input("Enter your age: "))

print("Your age is", age)
```

Identify inputs that may cause the program to fail.

```text
Test:

20
0
-5
twenty
20.5
""
```

Decide which inputs should be accepted and which should be rejected.

Modify the program so that invalid input is handled appropriately.

## Requirements

* File: 10-invalid-input.py
* Test multiple inputs.
* Identify which inputs cause problems.
* Modify the program to handle invalid input.
* Explain your decisions.
