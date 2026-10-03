# 9 — Combining Modules, Files and Errors

**Goal:** Combine the concepts introduced throughout the module.

Create a small contact management program.

The program should store contacts containing:

```text
name
phone
email
```

Create a separate module containing functions for:

* adding a contact
* displaying contacts
* saving contacts
* loading contacts

Store the contacts in a JSON file.

The program should handle the situation where the JSON file does not exist yet.

For example, when the program starts for the first time:

```text
No contacts found. Starting with an empty contact list.
```

The program should then allow contacts to be added and saved.

## Requirements
* File: 9-contact-manager.py
* Use functions.
* Use a separate module.
* Use a list of dictionaries.
* Save data as JSON.
* Load data from JSON.
* Handle a missing file.
* Use try and except where appropriate.
* Keep the responsibilities of the functions clear.
