# Module 6 - Debugging and Testing

## What are we doing this week

In the previous modules, students learned how to write programs, structure them, work with data, handle files and errors, and manage changes using Git.

However, programs do not always behave the way we expect.

A program may crash with an error. It may run successfully but produce the wrong result. It may work for one input and fail for another. It may also appear to work while containing problems that have not yet been discovered.

This week, students will learn how to **systematically investigate and fix problems in programs**.

They will learn how to read error messages, identify different types of bugs, reproduce problems, inspect program state, trace execution, use debugging techniques, and test programs with different inputs.

Students will also learn why testing should not happen only after a program has been completed.

The emphasis this week is on **debugging as a problem-solving process**, not simply fixing syntax errors.

Students should begin to develop the habit of asking:

> What did I expect the program to do?

> What did the program actually do?

> Where did the behavior first become different from what I expected?

> What evidence can I collect to find the cause?

## Objectives

By the end of the week, students should be able to:

1. Explain what debugging is and why it is necessary.

2. Distinguish between syntax errors, runtime errors, and logical errors.

3. Read and interpret common Python error messages.

4. Use a traceback to identify where an error occurred.

5. Reproduce a bug consistently.

6. Trace program execution to locate a problem.

7. Use `print()` statements to inspect program state.

8. Use a debugger to pause program execution and inspect variables.

9. Identify incorrect assumptions in a program.

10. Explain the difference between an error and a bug.

11. Write test cases for a program.

12. Test normal, boundary, and invalid inputs.

13. Identify cases that a program should handle.

14. Fix bugs without unnecessarily changing unrelated parts of a program.

15. Verify that a bug has actually been fixed.

16. Explain why testing existing functionality after making a change is important.

17. Use Git to record a bug fix.

18. Explain the relationship between debugging, testing, and software development.

## Concepts

### 1. Bugs and Errors

* What a bug is
* What an error is
* Why programs contain bugs
* Expected behavior
* Actual behavior
* Reproducible vs intermittent problems

### 2. Types of Errors

#### Syntax Errors

* Invalid Python syntax
* Missing punctuation
* Incorrect indentation
* Invalid keywords
* Reading syntax error messages

#### Runtime Errors

* Errors that occur while a program is running
* `ValueError`
* `TypeError`
* `NameError`
* `IndexError`
* `KeyError`
* `ZeroDivisionError`
* `FileNotFoundError`

#### Logical Errors

* Program runs successfully
* Program produces incorrect results
* Incorrect condition
* Incorrect calculation
* Incorrect loop condition
* Incorrect assumptions

### 3. Tracebacks

* What a traceback is
* Reading a traceback
* Identifying the exception type
* Identifying the line that caused the error
* Following the traceback
* Using the error message as information

### 4. Debugging

* Reproducing a problem
* Isolating a problem
* Forming a hypothesis
* Collecting evidence
* Inspecting program state
* Changing one thing at a time
* Verifying a fix

### 5. Program State

* Variable values
* Function arguments
* Return values
* Loop variables
* Conditions
* Collections
* Program state at different points in execution

### 6. Debugging Techniques

* Reading error messages
* Program tracing
* `print()` debugging
* Inspecting variables
* Using breakpoints
* Stepping through code
* Debugger
* Watching variable values
* Reproducing bugs with specific inputs

### 7. Testing

* What software testing means
* Why testing is necessary
* Test cases
* Expected result
* Actual result
* Pass/fail
* Normal inputs
* Boundary inputs
* Invalid inputs

### 8. Testing Strategies

* Testing typical inputs
* Testing minimum values
* Testing maximum values
* Testing values just inside a boundary
* Testing values just outside a boundary
* Testing invalid input
* Testing empty input
* Testing repeated operations

### 9. Regression Testing

* What regression means
* Why fixing one feature can break another
* Retesting existing functionality
* Testing after making changes
* Using previous test cases

### 10. Debugging and Version Control

* Creating a branch for a bug fix
* Making a focused change
* Testing the fix
* Committing the fix
* Writing useful bug-fix commit messages

## Activities

### 1. Review of Previous Modules

Students will review an existing program from previous modules.

They will identify:

* Inputs
* Processing
* Outputs
* Functions
* Conditions
* Loops
* Files
* Possible failure points

Students will deliberately introduce a small error and observe what happens.

### 2. Understanding Error Messages

Students will run programs containing common errors.

They will identify:

* The error type
* The line where the error occurred
* The operation that caused the problem
* What the error message is telling them

Students should learn to treat error messages as **information**, not something to immediately ignore or copy into a search engine.

### 3. Debugging Syntax Errors

Students will be given programs containing syntax errors.

They will:

* Run the program
* Read the error
* Identify the location
* Correct the problem
* Run the program again

### 4. Debugging Runtime Errors

Students will investigate programs that crash while running.

Examples may include:

* Converting invalid input to an integer
* Accessing a missing dictionary key
* accessing an invalid list index
* dividing by zero
* opening a file that does not exist

Students will identify what caused each error.

### 5. Debugging Logical Errors

Students will be given programs that run successfully but produce incorrect results.

For example:

```python
price = 100
quantity = 5

total = price + quantity

print(total)
```

The program runs.

There is no syntax error.

There is no runtime error.

But the result is incorrect.

Students must determine why.

### 6. Program Tracing

Students will trace programs manually.

They will track:

* variable values
* loop iterations
* conditions
* function calls
* return values

They should predict the output before running the program.

### 7. Debugging with `print()`

Students will add temporary debugging output to a program.

For example:

```python
print("price:", price)
print("quantity:", quantity)
print("total:", total)
```

They will use the output to determine where the program begins behaving incorrectly.

### 8. Using the Debugger

Students will use the Python debugger available in their development environment.

They will practice:

* setting a breakpoint
* starting a debugging session
* stepping over a line
* inspecting variables
* continuing execution
* identifying where a value changes unexpectedly

### 9. Designing Test Cases

Students will be given a program and asked to determine what should be tested.

They will identify:

* normal inputs
* minimum values
* maximum values
* boundary values
* invalid values
* unexpected values

For each test case, students should record:

```text
Input
Expected result
Actual result
Pass/Fail
```

### 10. Debugging Workshop

Students will receive a program containing several bugs.

The bugs may include:

* syntax errors
* runtime errors
* incorrect conditions
* incorrect calculations
* incorrect loop conditions
* incorrect data handling

Students must identify and fix the bugs without being told where they are.

### 11. Project Workshop

Students will:

* identify bugs in the project
* reproduce each bug
* investigate the cause
* create a test case
* fix the bug
* retest the program
* test related functionality
* commit the fix using Git

### 12. Code Review

Students will demonstrate one bug they fixed.

They should explain:

1. What the program was supposed to do.
2. What the program actually did.
3. How they reproduced the problem.
4. What caused the problem.
5. How they fixed it.
6. How they tested the fix.
7. How they know the fix did not break existing functionality.

## Exercises

Do the exercises in the `Exercises` folder in order.

The exercises progressively introduce error identification, traceback interpretation, program tracing, debugging techniques, test cases, boundary testing, and regression testing.

Students should complete the exercises before beginning the module project.

## Project

# Bug Hunt - Repair a Broken Student Management System

The students will be given a deliberately broken version of the Student Management System developed in previous modules.

The program should be designed to appear mostly functional while containing several different types of bugs.

Students must investigate the program and repair it.

The bugs should not simply be syntax errors.

The project should contain a mixture of:

* syntax errors
* runtime errors
* logical errors
* incorrect input handling
* incorrect calculations
* incorrect conditions
* incorrect collection access
* incorrect file handling where appropriate

The exact bugs should not be identified for the students.

## Problem

The Student Management System is supposed to allow a user to:

1. Add a student.
2. View students.
3. Search for a student.
4. Record scores.
5. Calculate results.
6. Save student information.
7. Load existing student information.
8. Exit the program.

However, the supplied version contains bugs.

Some features may crash.

Some may produce incorrect results.

Some may appear to work but fail under certain inputs.

Your task is to investigate the program, identify the problems, fix them, and demonstrate that the repaired program works correctly.

## Before You Code

Do not immediately start changing code.

First:

### Understand the Program

Identify:

* What does the program do?
* What are its inputs?
* What are its outputs?
* What data does it store?
* What functions does it contain?
* What files does it use?

### Run the Program

Run the program before making changes.

Record:

* What works?
* What crashes?
* What produces incorrect results?
* What behavior seems suspicious?

### Reproduce the Problems

For every bug you find, record:

```text
Problem:
How to reproduce it:
Expected behavior:
Actual behavior:
Likely cause:
```

Only after reproducing a problem should you begin fixing it.

## Requirements

Your repaired program must:

* run without unintended exceptions
* correctly handle valid input
* correctly handle invalid input where appropriate
* correctly calculate student results
* correctly search for students
* correctly save data
* correctly load data
* preserve existing functionality
* contain readable code
* contain no unnecessary debugging statements
* be tested using multiple test cases

## Bug Report

Create a `BUGS.md` file.

For each bug discovered, document:

```text
## Bug 1

### Problem

...

### How to Reproduce

...

### Expected Behavior

...

### Actual Behavior

...

### Cause

...

### Fix

...
```

Do this for each significant bug.

## Testing

Create a test plan containing at least:

### Normal Cases

Examples:

* Add a valid student.
* Search for an existing student.
* Record a valid score.
* Calculate a valid result.

### Boundary Cases

Examples:

* Score of 0.
* Score of 100.
* Empty student list.
* First student.
* Last student.

### Invalid Cases

Examples:

* Invalid score.
* Nonexistent student.
* Invalid menu option.
* Missing file where appropriate.

### Repeated Operations

Examples:

* Add several students.
* Search several times.
* Record several scores.
* Save and load multiple times.

For each test:

```text
Test
Input
Expected Result
Actual Result
Status
```

## Git Workflow

Do not make all changes directly on `main`.

Create a branch for the bug-fixing work.

For example:

```text
main
  ↓
fix/student-management-bugs
```

As bugs are fixed, make meaningful commits.

For example:

```text
Fix student search logic
Fix score calculation
Handle missing student data
Fix student file loading
```

After all fixes have been tested:

1. Merge the branch into `main`.
2. Run the complete test plan again.
3. Push the final project to GitHub.

## Bonus

Add automated tests for some of the program's functionality using Python's built-in `unittest` framework.

The tests should verify at least three pieces of program logic.

For example:

```text
calculate_average()
find_student()
calculate_grade()
```

The objective is to demonstrate that tests can automatically verify whether part of a program behaves as expected.

## Progression

```text
WEEK 5

Version Control
      ↓
Git
      ↓
Branches
      ↓
Commits
      ↓
GitHub

        ↓

WEEK 6

Bugs
      ↓
Errors
      ↓
Tracebacks
      ↓
Debugging
      ↓
Program Tracing
      ↓
Testing
      ↓
Test Cases
      ↓
Regression Testing
      ↓
Bug Fixing
      ↓
PROJECT
```
