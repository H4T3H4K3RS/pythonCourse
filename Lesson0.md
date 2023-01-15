# Lesson 0

# Integers, Input/Output, application of arithmetic operations for integers. Simple operations with strings.

## theory

Themes:

- Python (about, etc…)
- PyCharm
- Colab
- Hello World
- Variables
- Primitive types
- (opt) Comments
- Arithmetic

## cheatsheet

### Variables:

`int` - integer

`float` - float (decimal numbers)

`str` - string

`bool` - boolean (true / false)

- `int(param)` - function to convert param variable of type str or float to type int
- `float(param)`- function to convert param variable of type str or int to type float
- `str(param)` - function to convert param variable of type int or float to type str
- `print(param1, param2, ….)` - function to show user values of param1, param2 …, split with spaces
- `input(param)` - get data from user, showing him message from param

### Operations:

```
+ - sum
— - sub
*  - multiply
/ - division
// - int division
** n - power to n degree
% - leftover from division
a = b - put value of variable b to variable a
```

String formatting:

```python
age = 10
balance = 0
name = "Pseudo"
```

* Solution 1: `answer = name + " has " + str(balance) + " and is " + str(age) + " years old"`
* Solution 2: `answer = f"{name} has {balance} and is {age} years old"`
* Solution 3: `answer = "{} has {} and is {} years old".format(name, balance, age)`

Solution 1 is not good at all.

Solution 2 is the most compact one.

## homework

### Easy Level

- Count perimeter and square of an isosceles triangle. Side and base of a triangle are float and typed in by user.

- Count the average of 4 float numbers, which are float and typed in by user.

- Draw a Christmas tree in console, using spaces and # sign, and multiplication of strings

### Hard Level

- User types in his name, surname, balance. You should count the balance of his bank account in 2 years, knowing, that
  he will not take out the money from a deposit during next 2 years, and the interest rate is 11% each year. Interest
  rate should be also put in variable Output should be in such format:
  Hello, Pseudo Acronym!

> Your current balance: 1000 RUB.
>
> Our interest rate is 11% per year
>
> In 2 years your balance will be 1232.1 RUB

Each line should be formatted using `Solution 2`.