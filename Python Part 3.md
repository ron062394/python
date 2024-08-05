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
