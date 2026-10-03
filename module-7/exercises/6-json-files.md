# 6. Working with JSON Files

**Goal:** Read structured data from a JSON file.

Create a file called:

```text
students.json
```

Use the following data:

```json
[
    {
        "name": "Ada",
        "score": 85
    },
    {
        "name": "Grace",
        "score": 72
    },
    {
        "name": "Alan",
        "score": 91
    }
]
```

Write a Python program that:

1. Opens the JSON file.

2. Loads the data into Python.

3. Loops through the students.

4. Prints each student's name and score.

Example:

```text
Ada: 85
Grace: 72
Alan: 91
```

Then modify the program so that it prints only students whose score is 80 or higher.

**## Requirements**

* Folder: `teh-software-engineering/module-7`

* File: `6-json-files.py`

* File: `students.json`

* Use Python's `json` module.

* Read the JSON file rather than hard-coding the data.

* Use a loop.

* Use a condition to filter the students.
