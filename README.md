# Python Part 1

## **Typeof Comments**
Single Line Comments
``` python
`# This is a single-line comment`
```

Multi-Line Comments
``` python
"""
This is another way to create a multi-line comment.
It spans multiple lines.
It's enclosed in triple quotes.
"""
x = 10;
```




## **Variables**
Cell 1
``` python
my_number1 = 10
print(my_number1)
```
Cell 2
``` python
x-2 = 10  # This will throw an error
#2_b = 10 # This will throw an error
```
Cell 3
``` python
True = 5 # This will throw an error
```




## **Data Types**
Numeric Types
``` python
integer_number = 5
negative_int = -20
print(integer_number)
print(negative_int)
```
Checking Data Type
``` python
print('Type of integer_number:' , type(integer_number))
```



Float 
``` python
float_number = 2.14
negative_float = -20.55
print(float_number)
print(negative_float)
```
Checking Data Type
``` python
print(type(float_number))
```

String 
``` python
str1 = 'Hello World!'
str2 = "Hello to the world of Python"
user = 'user123'
print(str1)
print(str2)
print(user)
```
Checking Data Type
``` python
print(type(str1))
```



Boolean Type 
``` python
is_valid = True
is_admin = False
print(is_valid)
print(is_admin)
```
Checking Data Type
``` python
print(type(is_admin))
```


Dynamic Typing
``` python
my_var = 10
print(type(my_var))

my_var = "Hello World"
print(type(my_var))

my_var = 1.2
print(type(my_var))
```



## Python Operators and Expressions
Arithmetic operators
``` python
# Addition
print("Addition:", a + b)

# Subtraction
print("Subtraction:", a - b)

# Multiplication
print("Multiplication:", a * b)

# Division
print("Division:", a / b)

# Floor Division (result is floored to the nearest integer)
print("Floor Division:", a // b)

# Modulus (remainder of the division)
print("Modulus:", a % b)

# Exponentiation
print("Exponentiation:", a ** 2)
```


Comparison Operators
``` python
x = 10
y = 5

# Equal to
result = x == y

# Not equal to
result = x != y

# Greater than
result = x > y

# Less than
result = x < y

# Greater than or equal to
result = x >= y

# Less than or equal to
result = x <= y

print(result)
```



Logical Operators
``` python
x = 10
y = 5

# AND
result = (x > 5) and (y < 10)

# OR
result = (x > 5) or (y < 3)

# NOT
result = not (x == 10)
```



Assignment Operators
``` python
x = 10

# Addition Assignment
x += 5  # Equivalent to x = x + 5

# Subtraction Assignment
x -= 3  # Equivalent to x = x - 3

# Multiplication Assignment
x *= 2  # Equivalent to x = x * 2

# Division Assignment
x /= 4  # Equivalent to x = x / 4

# Modulus Assignment
x %= 3  # Equivalent to x = x % 3
```



## Strings
Creating and Accessing Strings
``` python
my_string = "Hello, Python!"
print(my_string)
my_string = 'Hello, Python!'
print(my_string)

first_letter = my_string[0]
print("The first letter is:", first_letter)

slice_string = my_string[0:5]
print("Slice of string:", slice_string)

my_text = "Reverse this string!"
reversed_string = my_text[::-1]
print("Reversed string:", reversed_string)
```

Creating and Accessing Strings
``` python
my_string = "Hello, Python!"
print(my_string)
my_string = 'Hello, Python!'
print(my_string)

first_letter = my_string[0]
print("The first letter is:", first_letter)

slice_string = my_string[0:5]
print("Slice of string:", slice_string)

my_text = "Reverse this string!"
reversed_string = my_text[::-1]
print("Reversed string:", reversed_string)
```


String Methods
``` python
sample_string = "data science science"  # Initialize the string

# Capitalize the first letter of the string and convert the rest to lowercase
print(sample_string.capitalize())  # Output: 'Data science science'

# Capitalize the first letter of each word in the string
print(sample_string.title())  # Output: 'Data Science Science'

# Find the first occurrence of the substring 'science' in the string
print(sample_string.find("science"))  # Output: 5

# Replace the substring 'data' with 'information' in the string
print(sample_string.replace("data", "information"))  # Output: 'information science science'

# Initialize another string
text = "the quick brown fox jumps over the lazy dog"

# Count the occurrences of the substring 'the' in the string
print(text.count("the"))
```


String Manipulation and Analysis Examples

``` python
# String Manipulation and Analysis Examples

# Initialize the messy string with leading and trailing whitespace and a newline character
messy_string = "   Data Analyst - Junior    \n"

# Remove leading and trailing whitespace and newline characters from the string
clean_string = messy_string.strip()
print(clean_string)  # Output: 'Data Analyst - Junior'

# Check if the substring "Data Analyst" is present in the sentence
sentence = "Data Analyst is a sexy job."
print("Data Analyst" in sentence)  # Output: True

# Initialize the phrase
phrase = "Python Programming"

# Convert all characters in the string to uppercase
print("Upper case:", phrase.upper())  # Output: 'PYTHON PROGRAMMING'

# Convert all characters in the string to lowercase
print("Lower case:", phrase.lower())  # Output: 'python programming'

# Initialize the sentence with comma-separated values
sentence = "Python,is,fun,to,learn"

# Split the sentence into a list of words based on commas
words = sentence.split(",")
print("Words:", words)  # Output: ['Python', 'is', 'fun', 'to', 'learn']
```


Boolean Checks for String Methods
``` python
# Initialize the filename
filename = "report.doc"

# Check if the filename ends with the ".pdf" extension
print(filename.endswith(".pdf"))  # Output: False

# Initialize the greeting
greeting = "Hello, world!"

# Check if the greeting starts with "Hello"
print(greeting.startswith("Hello"))  # Output: True

# The string is alphanumeric
alpha_string = "Python3"
print(alpha_string.isalnum())  # Output: True

# The string is numeric
numeric_string = "12345"
print(numeric_string.isdigit())  # Output: True

# The string contains only alphabetic characters
alpha_string = "Python"
print(alpha_string.isalpha())  # Output: True
```

Concatenation and Formatting
``` python
first_name = "Data"
last_name = "Scientist"

# Concatenation
full_name = first_name + " " + last_name
print("Concatenated string:", full_name)

# Formatting using f-strings
print(f"My job is a {first_name} {last_name}")
```




