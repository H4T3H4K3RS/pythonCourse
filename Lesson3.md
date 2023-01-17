# Lesson 3

## Structured data types: lists, tuples. Range function, for loop.

## cheatsheet

Python has several built-in data types for storing structured data, including lists and tuples.

Here is a Python cheat sheet for lists and tuples:

```python
# Create a list
my_list = [1, 2, 3, 4]

# Access an element in a list
print(my_list[1])  # 2

# Modify an element in a list
my_list[2] = 5

# Add an element to a list
my_list.append(6)

# Create a tuple
my_tuple = (1, 2, 3)

# Access an element in a tuple
print(my_tuple[1])  # 2

# Tuples are immutable, so you cannot modify an element in a tuple

```

The range function is used to generate a sequence of numbers. The basic syntax for the range function is:

```python
range(start, stop, step)
```

where start, stop, and step are integers. The range function generates a sequence of numbers starting from start, up to
but not including stop, and incrementing by step.

Here is a Python cheat sheet for the for loop and the range function:

```python
# Use a for loop to iterate through a list
for item in [1, 2, 3]:
    print(item)

# Use a for loop with the range function
for i in range(1, 5):
    print(i)

# Use a for loop with the range function and a step of 2
for i in range(1, 10, 2):
    print(i)

```

## homework

### Easy Level

- Create a program that calculates the factorial of a number using a for loop
- Create a program that takes a list of numbers as input, and then outputs the largest and smallest numbers in the list
- Create a program that takes a list of words as input, and then outputs the frequency of each word

### Hard Level

- Create a program that generates the multiplication table for a given number
- Create a program that accepts a string as input and then outputs the string in reverse order
