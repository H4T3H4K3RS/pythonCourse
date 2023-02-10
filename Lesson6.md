# Lesson 6

## Basic methods of working with functions

## cheatsheet

```python
# Define a function
def greet(name):
    print("Hello, " + name + "!")


# Call a function
greet("John")  # Hello, John!


# Pass arguments to a function
def greet(name, message):
    print(message + ", " + name + "!")


greet("John", "Good morning")  # Good morning, John!


# Return a value from a function
def add(a, b):
    return a + b


result = add(3, 5)
print(result)  # 8


# Use default argument values in a function
def greet(name, message="Hello"):
    print(message + ", " + name + "!")


greet("John")  # Hello, John!
greet("John", "Good morning")  # Good morning, John!


# Use the *args and **kwargs syntax to accept a variable number of arguments
def print_args(*args, **kwargs):
    print(args)
    print(kwargs)


print_args(1, 2, 3, name="John", age=30)
# (1, 2, 3)
# {'name': 'John', 'age': 30}

```

## homework

### Easy Level

- Create a program that calculates the area of a rectangle given its length and width. The program should use a function
  to perform the calculation.
- Create a program that takes a list of numbers as input and then outputs the sum of all the numbers in the list using a
  function.
- Create a program that takes two strings as input and then outputs a new string that is the concatenation of the two
  strings using a function.
- Create a program that converts temperatures between Celsius and Fahrenheit using two functions, one to convert from
  Celsius to Fahrenheit and another to convert from Fahrenheit to Celsius.
- Create a program that takes a number as input and then outputs the sum of the numbers from 1 to that number using a
  function.

### Hard Level

- 