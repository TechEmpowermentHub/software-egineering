# 3 - Read a Traceback

**Goal:** Learn how to extract useful information from an error message.

Consider:

```python
numbers = [10, 20, 30]

position = int(input("Enter a position: "))

print(numbers[position])
```

Run the program with:

```text
5
```

Read the traceback.

## Answer:

1. What exception occurred?
2. Which line caused the error?
3. What does the exception mean?
4. Why is position 5 invalid?
5. What inputs would be valid?

Then modify the program so invalid positions are handled appropriately.

## Requirements
* File: 3-read-traceback.py
* Record the original error.
* Explain the cause.
* Fix the problem.
* Test valid and invalid positions.
