# Python Part 1

## **Typeof Comments**
Single Line Comments
``` python
# This is a single-line comment
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

Inline Comments
``` python
x = 5  # This is an inline comment that extends until the end of the line
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
a = 10
b = 5

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


