# 10. API Error Handling

**Goal:** Handle failures when communicating with an external service.

Modify an API program so that it does not assume every request succeeds.

Your program should:

1. Make an API request.

2. Check the status code.

3. Process the response when successful.

4. Display an appropriate message when the request fails.

Test the program using:

* a valid request

* an invalid request

* an invalid parameter

* an unavailable endpoint if your instructor provides one

The program should not simply crash when the server returns an error.

**## Requirements**

* Folder: `teh-software-engineering/module-7`

* File: `10-api-error-handling.py`

* Check the response status.

* Handle successful requests.

* Handle unsuccessful requests.

* Display useful error messages.

* Test more than one failure situation.

Think about the difference between:

```text
My program has a bug.
```

and:

```text
The external service returned an error.
```

These are different problems and should be handled differently.
