# 9. Trace the Program

**Goal:** Learn to follow program execution and understand how conditions and loops affect a program.

Consider the following program:

```python
number = 1

while number <= 5:
    if number % 2 == 0:
        print(number, "is even")
    else:
        print(number, "is odd")

    number = number + 1
```

Before running the program, answer:

1. What is the value of `number` when the program starts?
2. How many times will the loop run?
3. What will the program print?
4. Why does the loop eventually stop?
5. What would happen if `number = number + 1` were removed?

Then run the program and compare your prediction with the actual output.

## Requirements

* Folder: `teh-software-engineering/module-2`
* File: `9-trace-the-program.py`
* Write your answers as comments in the Python file.
* Run the program after making your predictions.
* Explain any difference between your prediction and the actual output.
