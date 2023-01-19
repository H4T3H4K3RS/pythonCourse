# Lesson 4

## Basic methods of working with strings.

## cheatsheet

Python provides several built-in methods for working with strings. Here is a Python cheat sheet for some common string
methods:

```python
# Assign a string to a variable
my_string = "Hello, world!"

# Get the length of a string
print(len(my_string))  # 12

# Concatenate strings
new_string = my_string + " How are you?"

# Replace a substring in a string
new_string = my_string.replace("world", "Python")

# Convert a string to uppercase
print(my_string.upper())  # "HELLO, WORLD!"

# Convert a string to lowercase
print(my_string.lower())  # "hello, world!"

# Check if a string starts with a certain substring
print(my_string.startswith("Hello"))  # True

# Check if a string ends with a certain substring
print(my_string.endswith("world!"))  # True

# Split a string into a list of substrings
words = my_string.split()

```

## homework

### Easy Level

- Create a program that accepts a string as input and then outputs the number of vowels in the string
- Create a program that takes a string as input and then outputs the string with the first letter of each word
  capitalized
- Create a program that takes a string as input and then outputs the string with all punctuation removed

### Hard Level

- Create a program that takes a string as input and then outputs the string with all spaces removed
- Create a program that takes a string as input and then outputs the string with all letters reversed
