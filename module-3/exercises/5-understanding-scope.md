# 5. Understanding Scope

**Goal:** Understand where variables exist and how information is passed into functions.

Consider the following program:

```python
name = "Kelechi"

def greet():
    message = "Hello"
    print(message)
    print(name)

greet()
```

Before running the program, answer:

1. What is name?
2. What is message?
3. Where is message created?
4. Can message be accessed outside greet()?
5. Why can greet() access name?

Then modify the program so that the name is passed into the function as a parameter instead.

## Requirements
* File: 5-understanding-scope.py
* Answer the questions as comments in the file.
* Run the original program.
* Rewrite the function using a parameter.
* Explain why passing information through parameters is useful.
