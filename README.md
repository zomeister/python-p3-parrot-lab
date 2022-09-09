# Email Parser Lab

## Learning Goals

- Define a function that accepts arguments.
- Create a default argument.
- Practice returning a value.

***

## Key Vocab

- **Interpreter**: a program that executes other programs. Python programs
require the Python interpreter to be installed on your computer so that they
can be run.
- **Python Shell**: an interactive interpreter that can be accessed from the
command line.
- **Data Type**: a specific kind of data. The Python interpreter uses these
types to determine which actions can be performed on different data items.
- **Exception**: a type of error that can be predicted and handled without
causing a program to crash.
- **Code Block**: a collection of code that is interpreted together. Python
groups code blocks by indentation level.
- **Function**: a named code block that performs a sequence of actions when it
is called.
- **Scope**: the area in your program where a specific variable can be called.

***

## Instructions

This is a **test-driven lab**. Run `pipenv install` to create your virtual
environment and `pipenv shell` to enter the virtual environment. Then run
`pytest -x` to run your tests. Use these instructions and `pytest`'s error
messages to complete your work in the `lib/` folder.

In this lab, you'll be defining a function called `parrot()`.

The `parrot()` function should accept an argument of a string and both `print()`
and `return` the string at the end of the function.

The `parrot()` function should have a default argument of `"Squawk!"`

> **NOTE: _This lab is explicitly testing your ability to control the return
> value of a function: not just what it does, but what it returns. Remember,
> return values are important. What's the return value of `print()`?_**

***

## Resources

- [Default arguments in Python - GeeksforGeeks](https://www.geeksforgeeks.org/default-arguments-in-python/)
