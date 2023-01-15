# Lesson 2

## The while loop. Intro to the concept of cycles.

## theory

A while loop in Python is a type of loop that allows you to execute a block of code repeatedly as long as a certain
condition is met. The basic syntax of a while loop is as follows:

```python
while condition:
    # code to be executed
```

A cycle is a sequence of instructions that is repeated a certain number of times or until a certain condition is met.
Loops such as while loops are used to create cycles in code.

## cheatsheet

```python
# Initialize a variable
i = 0

# While loop
while i < 5:
    print(i)
    i += 1

# While loop with else statement
while i < 10:
    print(i)
    i += 1
else:
    print("i is no longer less than 10")

# While loop with break statement
while True:
    print(i)
    i += 1
    if i > 15:
        break

# While loop with continue statement
while i < 20:
    i += 1
    if i % 2 == 0:
        continue
    print(i)

```

## homework

### Easy Level

- Print the numbers from 1 to 10
- Print the even numbers from 1 to 20
- Print the numbers from 10 to 1 in descending order

### Hard Level

- Print the Fibonacci sequence up to a certain number
- Create a guessing game where the user has to guess a number between 1 and 100
- Create a program that simulates a vending machine with a menu of items and prices