# Project - API Information Explorer

The exercises in this module have progressively introduced the capabilities required for this project.

You have learned how applications communicate over networks, how HTTP requests and responses work, how JSON represents structured data, and how Python can communicate with external APIs.

You will now combine these concepts into a single program.

## Problem

Build a command-line API Information Explorer.

Your program should communicate with a public API and allow a user to retrieve and explore information.

The exact API will be selected or approved by the instructor.

The API should provide data that can be meaningfully searched, retrieved, or explored.

Examples of suitable API categories include:

* books
* countries
* public information
* movies
* weather
* products
* geographical information
* other publicly available datasets

The purpose of the project is not to build a sophisticated application.

The purpose is to demonstrate that you understand how one program can communicate with another program over HTTP and process the data it receives.

## Program Requirements

The program should:

* Ask the user for a search term, identifier, or other appropriate input.
* Make an HTTP request to the API.
* Send the appropriate parameters.
* Check whether the request was successful.
* Convert the JSON response into Python data.
* Extract useful information.
* Display the information clearly.
* Handle unsuccessful requests.
* Allow the user to perform multiple queries.
* Provide an option to exit.

The exact interaction will depend on the API selected.

## Example

The following is an example of the type of interaction expected.

Your actual project may look different depending on the API.

API Information Explorer

Enter a search term: python

Searching...

Results:

1. Python Programming
   Description: ...

2. Python Basics
   Description: ...

Search again? yes

Enter a search term: databases

Searching...

Results:

1. Introduction to Databases
   Description: ...

Search again? no

Goodbye.

## Before You Code

Do not begin by writing Python.

First understand the API.

Read its documentation and identify:

### API

What service are you communicating with?

### Endpoint

What URL should your program request?

### HTTP Method

What HTTP method should be used?

### Parameters

What information must be sent?

### Response

What JSON structure does the API return?

### Data

Which fields contain the information you need?

### Errors

What can cause the request to fail?

Then identify:

### Inputs

What information does the user provide?

### Processing

What does the program do with the input and API response?

### Outputs

What information does the program display?

### Conditions

What decisions does the program need to make?

For example:

* Was the request successful?
* Did the API return any results?
* Is the user's input valid?
* Should another search be performed?

## Repetition

What actions need to happen repeatedly?

## Algorithm

Write the steps of the solution in plain English or pseudocode.

Only after completing this analysis should you begin writing the Python code.

## Requirements

Your program must use:

* Variables
* User input
* Functions
* Lists and/or dictionaries
* Conditions
* Loops
* HTTP requests
* JSON
* At least one query parameter or other user-controlled API input
* Error handling
* Clear program output

The program should:

* Communicate with a real public API.
* Make an HTTP request.
* Check the response status.
* Process the JSON response.
* Extract useful information.
* Display useful information rather than simply printing the entire response.
* Handle cases where the request fails.
* Handle cases where no useful result is returned.
* Allow multiple queries.
* Allow the user to exit.

## Testing

Test your program with different situations.

At minimum, test:

1. A normal valid request.
2. A different valid request.
3. An empty or invalid user input where appropriate.
4. A request that produces no results.
5. An unsuccessful API request or error response.
6. Multiple searches.
7. Exiting the program.

Record the tests you performed.

## Documentation

Your project README must explain:

1. What the program does.
2. Which API you used.
3. Why you selected that API.
4. The API documentation.
5. How to install any required dependencies.
6. How to run the program.
7. The endpoint used.
8. The HTTP method used.
9. The parameters used.
10. The structure of the API response.
11. The inputs.
12. The processing.
13. The outputs.
14. The algorithm/pseudocode.
15. How errors are handled.
16. Example input and output.

## Git

Your project should be committed to Git.

Use meaningful commits while building the project.

For example:

Add initial project structure

Implement API request

Process API response

Add error handling

Improve output formatting

Add project documentation

Push the completed project to GitHub.

## Bonus

Add one or more useful features.

For example:

* Allow the user to limit the number of results.
* Add result numbering.
* Allow the user to view more details about a selected result.
* Add input validation.
* Add a retry option after a failed request.
* Save selected results to a JSON file.
* Add a search history.
* Allow the user to export results.

The bonus features are optional.

Do not sacrifice the core requirements in order to implement bonus features.

The goal is to build a program that is understandable, reliable, and useful.
