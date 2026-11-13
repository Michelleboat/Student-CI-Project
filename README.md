# Student-CI-Project
CMSC 426 BUILDING AN AUTOMATED CI PIPELINE USING JENKINS AND GITHUB
## Application

The application contains a function that adds two numbers and displays the result. An automated test is included to check whether the function returns the correct value.

## Running the Application

run the program:

python app.py

## Running the Tests

To run the automated test:

python -m unittest discover -s test

## Jenkins Integration

Jenkins is used to retrieve the project files from GitHub, run automated tests, and display the build results. This helps identify errors when changes are made to the code.

The automated tests use Python's test framework to check that the application produces the expected result.
