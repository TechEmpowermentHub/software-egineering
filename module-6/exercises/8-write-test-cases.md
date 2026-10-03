# 8 - Write Test Cases

**Goal:** Learn how to design test cases.

Consider a function that determines whether a person is eligible for an adult category:

```python
def is_adult(age):
    return age >= 18
```

Create test cases for the function.

At minimum, test:

```text
a typical adult age
a typical non-adult age
exactly 18
exactly 17
age 0
a negative age
```

Create a table:

```text
Input    Expected Result
-----    ---------------
20       True
15       False
18       True
17       False
0        False
-1       ?
```

## Questions
* Why is 18 important?
* Why is 17 important?
* Why should boundary values be tested?
* What should happen with a negative age?
