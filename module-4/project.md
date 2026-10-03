# Project - Persistent Student Management System

In Module 3, you built a Student Management System that stored students while the program was running.

There is one major problem:

**When the program stops, all the students disappear.**

In this project, you will modify the system so that student data is stored in a file and loaded again when the program starts.

You will also organize the program into multiple modules and add error handling.

## Problem

Upgrade the Student Management System so that student data persists between program runs.

Each student should have:

* Name
* Age
* Score

The program should display a menu:

```text
1. Add student
2. View students
3. Find student
4. Calculate average score
5. Save students
6. Exit
```

You may automatically save changes rather than requiring a separate Save option if you prefer, but the program must ensure that changes are persisted before the program exits.

## Persistent Data

Store the students in a JSON file.

For example:

```text
students.json
```

When the program starts, it should attempt to load the existing students.

If the file does not exist, the program should start with an empty student list.

For example:

```text
No existing student data found.
Starting with an empty student list.
```

The program should not crash simply because the file does not exist.

## Add Student

Ask for:

* Name
* Age
* Score

Validate the input before adding the student.

For example, age and score should be valid numbers.

## View Students

Display all students currently stored.

Example:

```text
Students:

1. Kelechi - Age: 20 - Score: 75
2. Ada - Age: 19 - Score: 82
3. Emeka - Age: 21 - Score: 68
```

## Find Student

Ask for a student's name.

Display the student's information if they exist.

Otherwise display an appropriate message.

## Calculate Average

Calculate and display the average score of all students.

Handle the situation where there are no students.

For example:

```text
No students have been added yet.
```

## Save Data

Save the current student collection to the JSON file.

The saved data should be available the next time the program runs.

## Errors

Your program should handle reasonable errors rather than crashing.

At minimum, consider:

* Invalid age
* Invalid score
* Invalid menu selection
* Missing JSON file
* Invalid JSON data
* Empty student list

You do not need to handle every possible error in existence. Focus on errors that are reasonably expected during normal use.

## Program Structure

The program should be separated into logical modules.

For example:

```text
module-4/
└── project/
    ├── main.py
    ├── student_manager.py
    ├── storage.py
    ├── students.json
    └── README.md
```

The exact structure is up to you.

The important requirement is that the program should not contain all of its logic in one enormous file.

You should decide which responsibilities belong in which module.

## Before You Code

First identify:

### Data

What information does the program store?

### Storage

Where will the information be stored?

How will it be represented in the JSON file?

### Functions

What operations does the program need?

### Modules

Which responsibilities should be separated into different files?

### Errors

What can go wrong?

How should the program respond?

### Inputs

What information does the program receive?

### Processing

What operations need to happen?

### Outputs

What should the user see?

### Algorithm

Write the steps of the solution in plain English or pseudocode.

### Program Structure

Sketch the major modules and functions before writing the implementation.

Only after completing this planning should you begin writing the Python code.

## Requirements

Your program must use:

* Variables
* User input
* Type conversion
* Conditional statements
* Loops
* Functions
* Parameters
* Return values where appropriate
* Lists
* Dictionaries
* Modules
* Imports
* File handling
* JSON
* Exception handling

The program should:

* Add students.
* Store multiple students.
* Save students to a file.
* Load students when the program starts.
* Display students.
* Find students.
* Calculate the average score.
* Handle reasonable invalid input.
* Handle a missing data file.
* Use multiple modules.
* Continue operating until the user chooses to exit.

## Testing

Test your program with at least the following situations:

1. Start the program when no data file exists.
2. Add one student.
3. Add multiple students.
4. Exit the program.
5. Start the program again and confirm that the students are still there.
6. Find an existing student.
7. Search for a student that does not exist.
8. Enter an invalid age.
9. Enter an invalid score.
10. Enter an invalid menu option.
11. Calculate the average with multiple students.
12. Calculate the average when there are no students.

## Bonus

Add one or more features:

* Update a student's information.
* Delete a student.
* Find the highest-scoring student.
* Find the lowest-scoring student.
* Search students by score.
* Export students to CSV.
* Add multiple scores for each student and calculate individual averages.

Do not add bonus features until the required functionality works correctly.
