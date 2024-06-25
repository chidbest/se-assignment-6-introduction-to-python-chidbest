# SE-Assignment-6

# Assignment: Introduction to Python

## Instructions:

### Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

### Questions:

#### 1. Python Basics:

#### - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

**What is Python**

Python is a dynamic, high-level, free open source, and interpreted programming language. It supports object-oriented programming as well as procedural-oriented programming.

**Features that make it popular among developers**

- Easy to learn and use: Python has a clean and simple syntax, which makes it a great language for beginners. Compared to other languages, it requires less code to achieve the same results.

- Interpreted language: Unlike compiled languages, Python code doesn't need to be translated into machine code before it can run. This makes development faster because you can write, test, and debug code much more quickly.

- Dynamically typed: In Python, you don't need to explicitly declare the data type of a variable. This can save time and effort when writing code, but it can also lead to errors if you're not careful.

- Extensive libraries and frameworks: Python has a vast collection of libraries and frameworks available for various tasks, including data science, web development, machine learning, and scientific computing. This saves developers time by providing pre-written code for common functions.

- Open-source and free: Python is an open-source language, which means it's free to use and modify. This has fostered a large and active community of developers who contribute to its development and create new libraries and tools.

**Examples of use cases where Python is particularly effective**

- Data Science: From wrangling massive datasets with libraries like Pandas to building complex machine learning models with Scikit-learn, Python offers a rich ecosystem for data manipulation and analysis.

- Web Development: Frameworks like Django and Flask allow you to build powerful web applications with Python. Its readability makes it easier to maintain and collaborate on large web projects.

- Automation: Python excels at automating repetitive tasks. You can write scripts to automate data processing, file management, web scraping, and more, saving you significant time and effort.

- Scientific Computing: Libraries like NumPy and SciPy provide powerful tools for numerical computations and scientific simulations. This makes Python a favorite among researchers and scientists.

- Machine Learning: TensorFlow and PyTorch are popular Python libraries for building and deploying machine learning models. Python's ease of use makes it a great choice for beginners venturing into machine learning.

#### 2. Installing Python:

#### - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

**Steps to install Python**

Here are steps to install Python on different operating systems:

1. Windows:

- Visit the official Python downloads page [download python windows](https://www.python.org/downloads/).
- Download the installer that matches your system architecture (32-bit or 64-bit).
- Run the installer and ensure you check the option to "Add Python 3.x to PATH" during installation. This allows you to run Python commands from any directory in your command prompt.
- Follow the on-screen instructions to complete the installation.

2. macOS:

- Check if you already have Python by opening Terminal and typing `python3 --version`. If you have an older version (Python 2.x) you may want to uninstall it first.
- Visit the official Python downloads page [download python mac](https://www.python.org/downloads/).
- Download the macOS installer for the latest version.
- Run the installer and follow the on-screen instructions.

3. Linux:

There are several ways to install Python on Linux, depending on your specific distribution. Here's a general guideline:

- Open a terminal window.
- Use your distribution's package manager to install Python. For example, on Ubuntu/Debian you would use `sudo apt install python3`.
- The exact command may vary depending on your distribution. Refer to your distribution's documentation for specific instructions.

After installing Python on any system, you can verify the installation by opening a terminal or command prompt and typing `python3 --version`. This should display the installed Python version.

#### 3. Python Syntax and Semantics:

#### - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

**Here's a simple Python program that prints "Hello, World!" to the console:**

```
print("Hello, World!")
```

**Explain the basic syntax elements used in the program.**

This program uses the `print` function, which is a built-in function in Python. The `print` function takes one or more arguments, which are the values you want to print. In this case, the argument is the string `"Hello, World!"`.

#### 4. Data Types and Variables:

#### - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

**List and describe the basic data types in Python.**

Python Data types are the classification or categorization of data items. It represents the kind of value that tells what operations can be performed on a particular data.

The following are the standard or built-in data types in Python:

1. Numeric Data Types in Python

The numeric data type in Python represents the data that has a numeric value. A numeric value can be an integer, a floating number, or even a complex number. These values are defined as Python int, Python float, and Python complex classes in Python.

- Integers – This value is represented by int class. It contains positive or negative whole numbers (without fractions or decimals). In Python, there is no limit to how long an integer value can be.
- Float – This value is represented by the float class. It is a real number with a floating-point representation. It is specified by a decimal point. Optionally, the character e or E followed by a positive or negative integer may be appended to specify scientific notation.
- Complex Numbers – A complex number is represented by a complex class. It is specified as (real part) + (imaginary part)j. For example – 2+3j

2. Text Type

- Strings (str) - A string is a collection of one or more characters put in a single quote, double-quote, or triple-quote. Examples: "Hello, world!", '''This is a string with multiple lines'''

3. Boolean Data Type in Python

Python Data type with one of the two built-in values, True or False. Boolean objects that are equal to True are truthy (true), and those equal to False are falsy (false).

4. Collections:

- Lists (list): Ordered, changeable collections of items. Elements can be of different data types. Enclosed in square brackets []. Examples: [1, 2, 3, "apple"]
- Tuples (tuple): Ordered, immutable collections of items. Elements can be of different data types. Enclosed in parentheses (). Examples: (1, "cat", 3.5)
- Sets (set): a Set is an unordered collection of data types that is iterable, mutable, and has no duplicate elements. The order of elements in a set is undefined though it may consist of various elements.

5. Dictionary Data Type in Python

A dictionary in Python is an unordered collection of data values, used to store data values like a map, unlike other Python Data Types that hold only a single value as an element, a Dictionary holds a key: value pair.

**Write a short script that demonstrates how to create and use variables of different data types.**

Here's a short script in Python demonstrating different data types:

```
Python
# Integer (whole number)
age = 25

# String (text)
name = "Alice"

# Boolean (True or False)
is_sunny = True

# Float (decimal number)
pi = 3.14159

# Print the variables and their types
print("Age:", age, " (type:", type(age), ")")
print("Name:", name, " (type:", type(name), ")")
print("Is it sunny:", is_sunny, " (type:", type(is_sunny), ")")
print("Pi:", pi, " (type:", type(pi), ")")
```

This script creates variables of different data types:

- age: Integer (whole number)
- name: String (text)
- is_sunny: Boolean (True or False)
- pi: Float (decimal number)

#### 5. Control Structures:

#### - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

**Explain the use of conditional statements and loops in Python.**

1. Conditional Statements:

- Decision Making: These statements allow your program to make choices based on certain conditions. They evaluate a condition (often something that results in True or False) and execute different code blocks depending on the outcome.

- Common Types:
  - if statement: Executes a block of code if the specified condition is True.
  - if-else statement: Executes one block of code if the condition is True, and another block if it's False.
  - if-elif-else statement: Allows checking multiple conditions sequentially using elif (else if) before an optional final else block.
  - Nested if statements: You can have if statements within other if statements for more complex decision making.

2. Loops:

- Repetition: Loops allow you to execute a block of code repeatedly until a certain condition is met. This is useful for tasks that need to be done multiple times, often with variations each time.

- Types of Loops:
  - for loop: Iterates over a sequence of items (like a list or string) and executes the code block for each item.
  - while loop: Continues executing the code block as long as a certain condition remains True.

**Provide examples of an `if-else` statement and a `for` loop.**

- if-else statement example

Here's an example of an `if-else statement` that checks if a number is even and prints a message accordingly:

```
Python
number = int(input("Enter a number: "))

if number % 2 == 0:
  print(f"{number} is even.")
else:
  print(f"{number} is odd.")
```

This code first asks the user to enter a number using input(). Then, it uses the modulo operator (%) to check if the remainder of dividing the number by 2 is 0. If it is, the number is even, and the if block is executed. Otherwise, the else block is executed.

- for loop example

This example uses a `for loop` to iterate through a list of fruits and print each one:

```
Python
fruits = ["apple", "banana", "orange"]

for fruit in fruits:
  print(fruit)
```

Here, we define a list called fruits. The for loop iterates through each item in the fruits list and assigns it to the variable fruit in each iteration. Inside the loop, we simply print the current fruit. This will print "apple", "banana", and "orange" on separate lines.

#### 6. Functions in Python:

#### - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

**What are functions in Python, and why are they useful?**

In Python, functions are reusable blocks of code that perform specific tasks. They are like mini-programs within your main program that can be called upon multiple times throughout your code. Functions offer several advantages:

- Reusability: By encapsulating a set of instructions into a function, you can avoid writing the same code repeatedly. This saves time and effort, especially when you're dealing with complex tasks.

- Modularity: Functions break down your code into smaller, more manageable pieces. This improves code readability and maintainability. You can focus on the logic of each function without getting bogged down in the details of the entire program.

- Clarity: Functions make your code easier to understand for yourself and others. By giving functions descriptive names, you can clearly communicate what each part of your code does.

Here's a Python function that takes two arguments and returns their sum, along with an example of how to call it:

```
Python
def sum_function(x, y):
  """This function takes two numbers as arguments and returns their sum.

  Args:
      x: The first number.
      y: The second number.

  Returns:
      The sum of x and y.
  """

  return x + y

# Example usage:
result = sum_function(5, 3)
print(result)  # Output: 8
```

This code defines a function named sum_function that takes two arguments, x and y. Inside the function, the + operator is used to add the two arguments and the result is returned using the return statement.

#### 7. Lists and Dictionaries:

#### - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

**Describe the differences between lists and dictionaries in Python**

Lists and dictionaries are both fundamental data structures in Python used to store collections of elements, but they differ in how they organize and access that data. Here's a breakdown of the key differences:

1. Ordering:

- Lists: Ordered collections. Elements are maintained in the order they are added. You can access elements by their position (index), starting from 0.
- Dictionaries: Unordered collections. Elements are not guaranteed to be stored or retrieved in the order they were added.

2. Accessing Elements:

- Lists: Accessed using numerical indexes within square brackets [].
- Dictionaries: Accessed using keys within curly braces {}. Keys can be of any immutable data type (strings, numbers, tuples). A key acts like a label for its corresponding value.

3. Duplicate Values:

- Lists: Can contain duplicate elements. You can have multiple instances of the same value at different positions in the list.
- Dictionaries: Cannot contain duplicate keys. Each key must be unique, but the corresponding values can be duplicates.

4. Use Cases:

- Lists: Ideal for storing sequences of items where order matters. Examples include shopping lists, to-do lists, or storing student grades in a class.
- Dictionaries: Well-suited for storing data where you need to associate a value with a unique identifier (key). Examples include phonebooks (name: phone number), student information (ID: name, grades), or configurations (key: value).

5. Mutable vs. Immutable Keys:

- Lists: Elements can be of any data type, including mutable ones like lists themselves.
- Dictionaries: Keys must be immutable data types (strings, numbers, tuples) to ensure efficient lookups. Values can be of any data type.

6. Performance:

- Lists: Faster for ordered operations like iterating through elements in sequence or sorting the list.
- Dictionaries: Faster for lookups by key, as they use hashing for efficient retrieval of specific values.

**Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.**

```
Python
# Create a list of numbers
numbers = [1, 5, 9, 13, 17]

# Create a dictionary with key-value pairs
info = {
    "name": "Example Dictionary",
    "version": 1.0,
    "created": "2024-06-25"
}

# Print the list and dictionary
print("Numbers:", numbers)
print("Information:", info)

# Access elements in the list
first_number = numbers[0]
third_number = numbers[2]

print("First number:", first_number)
print("Third number:", third_number)

# Access values in the dictionary using keys
name = info["name"]
version = info["version"]

print("Dictionary name:", name)
print("Dictionary version:", version)

# Add a new element to the list
numbers.append(21)
print("Numbers after adding:", numbers)

# Update a value in the dictionary
info["version"] = 1.1
print("Information after update:", info)

# Check if a key exists in the dictionary (using 'in' operator)
if "created" in info:
  print("The 'created' key exists in the dictionary.")

# Get the length of the list (number of elements)
list_length = len(numbers)
print("Length of the list:", list_length)
```

This script demonstrates creating a list and dictionary, accessing elements, adding/updating elements, checking for keys, and finding the length of the list. You can modify this script to explore other operations on these data structures.

#### 8. Exception Handling:

#### - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

**What is exception handling in Python?**

Exception handling in Python is a mechanism for dealing with unexpected errors that may occur during the execution of your program. It allows you to write robust code that can gracefully handle these errors and continue execution, or at least provide informative messages to the user.

**Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.**

```
Python
def get_user_age():
  while True:
    try:
      age = int(input("Enter your age: "))
      if age < 0:
        raise ValueError("Age cannot be negative")
      return age
    except ValueError as e:
      print("Invalid input:", e)
    finally:
      print("Thanks for trying!")

try:
  user_age = get_user_age()
  print("Your age is:", user_age)
except ValueError as e:
  print("There was an error:", e)

print("Program execution complete.")
```

This script defines a function `get_user_age` that prompts the user for their age. The `try` block attempts to convert the user input to an integer using `int(input())`.

- If the conversion is successful, the code checks if the age is negative. If it is, a `ValueError` is raised with a specific message.
- The` except` block catches the `ValueError` and prints a user-friendly message with the specific error details `(e)`.
- The `finally` block executes regardless of whether an exception occurs. Here, it prints a "Thanks for trying!" message.

The main part of the script calls `get_user_age` and stores the returned age in `user_age`. It then uses another `try-except` block to handle potential `ValueError` raised by `get_user_age`. Finally, it prints a completion message.

This example demonstrates how to use `try-except-finally` for:

- Handling specific exceptions (`ValueError` in this case).
- Providing informative error messages to the user.
- Ensuring essential code (like the "Thanks for trying!" message) always executes.

#### 9. Modules and Packages:

#### - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

**Explain the concepts of modules and packages in Python.**

In Python, modules and packages are fundamental building blocks for organizing your code. They both promote a concept called modular programming, which breaks down large programs into smaller, manageable pieces.

1. Modules:

- A single Python file containing code like functions, classes, and variables.
- Think of it as a toolbox containing specific tools for a particular task.
- Imported using the `import` statement followed by the module name.
- Once imported, the module's contents become available in your program's namespace.
- Example: A file named `math_functions.py` containing mathematical functions can be imported and used in another script.

2. Packages:

- A collection of modules organized within a directory structure.
- Imagine it as a workshop containing multiple toolboxes categorized for different purposes.
- A directory containing Python modules and a special file named `__init__.py` (can be empty).
- Imported using either the package name or dot notation for specific modules within the package.
- Provides a hierarchical organization for related modules, preventing naming conflicts.
- Example: A directory named `geometry` containing modules for `area.py`, `perimeter.py`, and `volume.py` can be considered a package for geometrical calculations.

**How can you import and use a module in your script? Provide an example using the `math` module.**

Importing a module in Python allows you to access functionality defined elsewhere in reusable blocks of code. The `math` module is a built-in library in Python that provides a variety of mathematical functions and constants.

Here's how you can import and use the `math` module:

1. Import the module:

```
Python
import math
```

This statement tells Python to make the `math` module available for your script.

2. Use functions and constants:
   Once the module is imported, you can access its functions and constants using the dot notation (`math.function_name` or `math.constant_name`).

For example, to calculate the area of a circle with radius 5, you can use the following code:

```
Python
import math

radius = 5
area = math.pi * radius**2

print(f"The area of the circle is: {area}")
```

In this code:

- `math.pi` accesses the value of pi from the `math` module.
- The area is calculated using the formula `pi * radius**2`.
- The `print` function displays the calculated area.

This is a simple example of how to import and use a module in Python. The `math` module provides many other useful functions, and there are many other modules available in Python that can extend the functionality of your programs.

#### 10. File I/O:

#### - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

** How do you read from and write to files in Python?**

Reading and writing files in Python is a fundamental operation for many tasks. Here's a breakdown of the process:

1. Opening the File:

The first step is to open the file using the built-in open() function. This function takes two arguments:

- File Path: The location of the file on your system.
- Mode: A string indicating how you want to access the file. Here are some common modes:
  - `'r'`: Read mode (default). Opens the file for reading. Attempting to write in this mode will result in an error.
  - `'w'`: Write mode. Creates a new file or overwrites an existing one.
  - `'a'`: Append mode. Opens the file for appending data. If the file doesn't exist, it will be created.
  - `'r+'`: Read and write mode. Opens the file for both reading and writing. Existing data will be overwritten from the beginning.
  - `'a+'`: Append and read mode. Opens the file for reading and appending. The handle is positioned at the end of the file initially.

2. Reading the File:

There are several methods for reading file content depending on your needs:

- `read(size)`: Reads a specified number of bytes (or the entire file if no argument is provided) and returns it as a string.
- `readline()`: Reads a single line from the file and returns it as a string.
- `readlines()`: Reads all lines from the file and returns them as a list of strings.

3. Writing to the File:

Similar to reading, you have methods for writing data:

- `write(string)`: Writes a string to the file.
- `writelines(list_of_strings)`: Writes a list of strings to the file, each on a new line.

4. Closing the File:

It's important to close the file after you're done to release resources. You can use the `close()` method on the file object.

**Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.**

Script 1: Read a file and print its content

```
Python
def read_file(filename):
  """
  This function reads the content of a file and prints it to the console.

  Args:
    filename: The name of the file to read.
  """
  try:
    with open(filename, 'r') as f:
      content = f.read()
      print(content)
  except FileNotFoundError:
    print(f"Error: The file '{filename}' does not exist.")

# Example usage
read_file('my_file.txt')  # Replace 'my_file.txt' with the actual filename
```

Script 2: Write a list of strings to a file

```
Python
def write_list_to_file(filename, string_list):
  """
  This function writes a list of strings to a file.

  Args:
    filename: The name of the file to write to.
    string_list: A list of strings to write to the file.
  """
  with open(filename, 'w') as f:
    for string in string_list:
      f.write(string + '\n')  # Add a newline character after each string

# Example usage
string_list = ["This is the first line.", "This is the second line.", "This is the third line."]
write_list_to_file('output.txt', string_list)
```

# REFERENCES

https://www.geeksforgeeks.org/python-features/
https://gemini.google.com/app/febf9531b8ae21c0
https://www.geeksforgeeks.org/python-data-types/
https://www.datacamp.com/tutorial/functions-python-tutorial
https://www.shiksha.com/online-courses/articles/difference-between-list-and-dictionary-in-python/#:~:text=Lists%20and%20Dictionaries%20are%20different,delete%2C%20or%20modify%20the%20elements.
https://realpython.com/python-exceptions/
