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

## classwork

1. Create a list of prices for a product catalog, sort the list by ascending order and print the 3 lowest prices.

2. Create a list of employee names, remove an employee who left the company from the list.

3. Create a list of customer IDs, find the index of a specific customer ID in the list.

4. Create a list of product IDs and count the number of occurrences of a specific product ID in the list.

5. Create a string that represents a document with multiple versions, replace all occurrences of the word "version" with
   the word "edition" and print the modified document.

6. Create a list of email addresses and check if any of them is from a specific domain.

7. Create a string that represents a customer's address, split it into individual components (street name, city, state,
   zip code) and print the city.

8. Create a string that represents a password, check if it contains at least one special character and one number.

9. Create a string that represents a website url, check if it starts with "https" or "www"

10. Create a string that represents a CSV file and join all the elements of a list of strings with a comma as a
    separator.