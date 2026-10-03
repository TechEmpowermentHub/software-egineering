# 5. Reading JSON

**Goal:** Understand JSON and access data stored inside it.

Consider the following JSON:

```json
{
    "name": "Ada",
    "age": 25,
    "is_student": true,
    "skills": [
        "Python",
        "SQL",
        "Git"
    ]
}
```

Create a Python program that stores this information in an appropriate Python data structure.

Print:

```text
Name: Ada
Age: 25
Student: True
```

Then print each skill.

Expected output:

```text
Skill: Python
Skill: SQL
Skill: Git
```

**## Requirements**

* Folder: `teh-software-engineering/module-7`

* File: `5-reading-json.py`

* Store the data using a Python dictionary.

* Access values using dictionary keys.

* Use a loop to display the skills.

* Do not hard-code the individual skill output.

Think about how the JSON structure maps to Python dictionaries and lists.
