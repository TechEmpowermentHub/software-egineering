# Module 7 - Internet, HTTP, APIs, and JSON

## What are we doing this week

In previous modules, students learned how to write programs that receive input, process information, and produce output.

They have also learned how to structure programs, use functions, work with collections, handle files, and use Git.

This week, students will learn how programs communicate with other programs over a network.

They will learn the basic concepts behind the web and how applications communicate using HTTP. They will learn what clients and servers are, how URLs identify resources, how HTTP requests and responses work, and how different HTTP methods are used.

Students will also learn about JSON, a common format for exchanging structured data between applications.

They will then use Python to make requests to a real API, receive data, process that data, and build a small program around it.

The emphasis this week is on **understanding how software communicates**, not simply learning how to use a particular API library.

**## Objectives**

By the end of the week, students should be able to:

1. Explain the basic idea of how computers communicate over a network.

2. Explain the difference between a client and a server.

3. Explain what a URL is and identify its major components.

4. Explain what HTTP is and why it is used.

5. Describe the basic structure of an HTTP request and response.

6. Explain the purpose of common HTTP methods such as GET and POST.

7. Explain the meaning of common HTTP status codes.

8. Explain what JSON is and why it is useful for exchanging data.

9. Read and understand simple JSON data.

10. Convert between Python data structures and JSON.

11. Explain what an API is.

12. Make an HTTP request from Python.

13. Process data received from an API.

14. Handle common API errors.

15. Use documentation to understand how an API works.

16. Break an API-based problem into computational steps.

17. Build a small Python program that consumes an API.

**## Concepts**

1. Network Communication

   * Why programs need to communicate

   * Local programs vs networked programs

   * Computer networks

   * Clients

   * Servers

   * Request and response

   * The role of the internet

2. The Web

   * What the web is

   * Websites and web applications

   * Web browsers

   * Web servers

   * Resources

   * URLs

   * Domains

   * Paths

   * Query parameters

3. HTTP

   * What HTTP means

   * HTTP requests

   * HTTP responses

   * Request methods

   * GET

   * POST

   * PUT

   * PATCH

   * DELETE

   * Request headers

   * Request body

   * Response body

   * HTTP status codes

   * 2xx success

   * 3xx redirection

   * 4xx client errors

   * 5xx server errors

4. JSON

   * What JSON means

   * Objects

   * Arrays

   * Strings

   * Numbers

   * Boolean values

   * null

   * Nested JSON data

   * JSON vs Python dictionaries and lists

   * Converting JSON to Python data

   * Converting Python data to JSON

5. APIs

   * What an API is

   * Why APIs are useful

   * API endpoints

   * API requests

   * API responses

   * API documentation

   * Parameters

   * Query parameters

   * Authentication concepts

   * Public APIs

   * API limitations and errors

6. Using APIs with Python

   * HTTP client libraries

   * Making GET requests

   * Sending parameters

   * Reading response data

   * Converting JSON to Python objects

   * Checking status codes

   * Handling errors

   * Processing API data

7. Problem Solving with APIs

   * Identifying the information required

   * Finding the appropriate API endpoint

   * Reading API documentation

   * Identifying request parameters

   * Understanding the response structure

   * Extracting required information

   * Processing the data

   * Producing useful output

   * Testing different inputs

**## Activities**

1. Review of Previous Modules

   * Review variables and data types

   * Review conditions and loops

   * Review functions

   * Review collections

   * Review dictionaries

   * Review modules

   * Review error handling

   * Review Git and GitHub

2. Understanding Network Communication

   * Understand why programs need to communicate

   * Understand client and server roles

   * Observe how a browser communicates with a web server

   * Identify requests and responses

   * Understand the basic flow of a web request

3. Understanding URLs

   * Identify domains

   * Identify paths

   * Identify query parameters

   * Break URLs into their components

   * Construct simple URLs

4. Understanding HTTP

   * Examine HTTP requests

   * Examine HTTP responses

   * Identify HTTP methods

   * Identify request headers

   * Identify response headers

   * Examine response status codes

   * Predict what different requests will do

5. Guided JSON Exercises

   * Read JSON objects

   * Read JSON arrays

   * Access nested values

   * Convert JSON into Python data

   * Convert Python data into JSON

   * Process JSON using dictionaries and lists

6. Guided API Exercises

   * Read API documentation

   * Identify an API endpoint

   * Identify required parameters

   * Make a GET request

   * Inspect the response

   * Extract useful data

   * Handle unsuccessful requests

7. Program Tracing

   Students will be given small API-based programs and asked to determine what the programs are doing before running them.

   They will practice:

   * Following the request flow

   * Identifying the endpoint being called

   * Identifying parameters

   * Understanding the response

   * Following data through the program

   * Predicting program output

8. Problem-Solving Exercise

   Students will take a real-world problem that requires information from an external service and:

   * Identify the required information

   * Determine what API data is needed

   * Read the API documentation

   * Identify the endpoint

   * Identify required parameters

   * Describe the request

   * Describe the expected response

   * Extract the required data

   * Process the data

   * Display the result

9. Project Workshop

   * Understand the project requirements

   * Read the API documentation

   * Identify the required endpoint

   * Design the program flow

   * Implement the API request

   * Process the response

   * Handle errors

   * Test different situations

   * Improve the program

   * Commit the project to Git

10. Code Review

    * Students demonstrate their programs

    * Explain the API they used

    * Explain the request they made

    * Explain the response they received

    * Trace the important sections of code

    * Discuss error handling

    * Identify bugs

    * Discuss possible improvements

    * Explain why the program behaves the way it does

**## Exercises**

Do the exercises in the Exercises folder in order.

The exercises gradually introduce network communication, URLs, HTTP, JSON, APIs, and making requests from Python.

Students should complete them before beginning the module project.

**## Project**

**API Information Explorer**

Build a command-line program that retrieves information from a public API and allows the user to explore the returned data.

The program should:

* Make an HTTP request to a public API.

* Receive a response from the API.

* Check whether the request was successful.

* Convert the JSON response into Python data.

* Display useful information from the response.

* Allow the user to perform multiple searches or queries.

* Handle situations where the API request fails.

Students should first read the API documentation and describe the request and response before writing the Python code.

The project should require students to use:

* Variables

* User input

* Type conversion where appropriate

* Functions

* Lists

* Dictionaries

* Conditions

* Loops

* HTTP requests

* JSON

* API data

* Error handling

* Clear program output

The focus is not on building an API.

The focus is on understanding how an existing API works and building a useful program that communicates with it.

**## Progression**

```text
MODULE 6

Working with Data and Files

│
├── Files
├── CSV
├── JSON
├── Dictionaries
└── Data processing

        ↓

MODULE 7

Internet and APIs

│
├── Networks
├── Client / Server
├── URLs
├── HTTP
├── Requests / Responses
├── JSON
└── APIs

        ↓

MODULE 8

Databases

│
├── Relational databases
├── Tables
├── SQL
├── Relationships
└── Data persistence
```
