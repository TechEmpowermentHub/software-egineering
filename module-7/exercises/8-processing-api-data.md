# 8. Processing API Data

**Goal:** Extract useful information from an API response.

Use the API from the previous exercise.

Instead of printing the entire response, inspect its JSON structure and identify useful fields.

Write a program that:

1. Makes the API request.

2. Converts the response to Python data.

3. Accesses specific values.

4. Displays only the information that is useful to the user.

For example, if the API returns information about several items, your program should display a useful summary rather than printing the entire JSON response.

**## Requirements**

* Folder: `teh-software-engineering/module-7`

* File: `8-processing-api-data.py`

* Make an API request.

* Check whether the request succeeded.

* Convert the response to JSON.

* Access values from dictionaries and/or lists.

* Display selected information.

* Do not simply print the entire response.

The important skill here is learning to move from:

```text
API response
      ↓
Python data
      ↓
Useful information
      ↓
User output
```
