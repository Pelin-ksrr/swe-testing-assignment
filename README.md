# swe-testing-assignment

# Quick-Calc

Quick-Calc is a simple calculator application developed as part of the Advanced Software Engineering course assignment. The application performs basic arithmetic operations including addition, subtraction, multiplication, and division. The project demonstrates software testing techniques and version control practices using Git and GitHub.

## Features

- Addition
- Subtraction
- Multiplication
- Division
- Clear function
- Error handling for division by zero

## Setup Instructions

1. Clone the repository

git clone https://github.com/yourusername/swe-testing-assignment.git

2. Navigate to the project directory

cd swe-testing-assignment

3. Install dependencies

pip install -r requirements.txt

## Running Tests

To execute all tests run:

pytest

## Testing Framework Comparison

Two popular Python testing frameworks are Pytest and Unittest.

Unittest is the built-in testing framework included with Python. It provides a structured approach similar to Java's JUnit and is widely used in enterprise environments. However, it often requires more boilerplate code.

Pytest is a more modern and flexible testing framework. It allows developers to write simpler tests with less code and provides powerful features such as fixtures, plugins, and better error reporting.

For this project, Pytest was chosen because it is easier to use, requires less code, and provides clearer test outputs.