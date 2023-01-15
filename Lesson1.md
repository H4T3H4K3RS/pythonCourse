# Lesson 1

# Basics of working with real numbers, rounding. Logical type of variables, conditional operator. If, else.

## cheatsheet

### if / elif / else

Construction

```python
if test1:  # checked every time interpreter reaches this line
    state1  # executed if test1 is True
elif test2:  # checked if test1 is False, and
    state2  # executed if test2 is True
else:  # executed if test1 and test2 are False
    state3
```

### Turnary Operator

```python
if test1:
    x = state1
else:
    x = state2
```

can be optimised into one line:

```python
x = state1 if test1 else state2
```

### Logical Operators

```state1 and state2``` - binary logical operation, that returns True only if both statements are True

```state1 or state2``` - binary logical operation, that returns False only if both statements are False

```not state1``` - unary logical operation, that returns the opposite of state1 (False => True; True => False)

### Comparation operators

- a > b - a more than b

- a < b - a less than b

- a == b - a equal to b

- a != b - a not equal to b

- a >= b - a more or equal than b

- a <= b - a less or equal than b

### Lifehacks

`if 1` - always `True`

`if 0` - always `False`

### None

When checking in `if` condition, variable, which value is `None`, always returns `False`

`None` value is actually nothing and it is `NoneType`

## homework

### Easy Level

- Users inputs one of three colors of the traffic light (“red”, “yellow”, “green”), you should display message for the
  drivers, whether they should stop, prepare or ride respectively.
- User inputs the number, you should print in one line, whether this number’s last digit is 7 or 9, or not.