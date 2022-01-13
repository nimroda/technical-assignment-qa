# Technical Assignment for Automation Engineers
This is the technical assignment for Quality Engineers. You'll find two main automation tasks: 1) Webdriver and 2) API functional testing. These two tasks is required as part of this assignment.

The tasks below are simple and therefore we'd like simple solutions where you show good coding practices (maintainable code) such as the clear folder structure, intuitive method names, Page Object Pattern and Object Oriented Principles as a starting point. We recommend you follow the coding guidelines below and read the tasks carefully.

## Quality Engineer Assignment  
## Task 1: Functional E2E Automation
Functional automation for web UI testing using Selenium Web Driver.
* Open Google and perform a search for ‘Cars in London’.
* Get all search results displayed and validate how many Gumtree links there are available (you may only focus on the first page of the search results for the purpose of this task).
* Navigate to each Gumtree link and confirm the title is displayed and the number of the results is greater than 0.

Requirements:
* Use Pyhton / Pytest
* Develop the automation framework for the above feature file / spec.

On average, this task can be completed in 2-3 hours, but you are welcome to spend more time on it to submit a better quality code.

## Task 2: Functional API Testing
Functional automation for API testing.
Write a test Pytohn for the following REST API:

https://jsonplaceholder.typicode.com/

Requirements:

* Get a random user (userID), print out its email address to console.
* Using this userID, get this user’s associated posts and verify they contains a valid Post IDs (an Integer  between 1 and 100).
* Do a post using same userID with a non-empty title and body, verify the correct response is returned (since this is a mock API, it might not return Response code 200, so check the documentation).

On average, this task can be completed in 2-3 hours, but you are welcome to spend more time on it to submit a better quality code.
Thanks for taking part in our selection process and good luck!
