[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15324053&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   - Python is a high-level, interpreted programming language known for its simplicity and readability.

   Key features why it is popular
   1. Easy to learn:Python's syntax is designed to be clear and readable, making it accessible for beginners and enjoyable for experienced programmers
   2. Interpreted and Dynamic: Python is interpreted at runtime, which means code execution is immediate, making the development process faster. It also supports dynamic typing, allowing for flexibility in code development.

   3. Rich Standard Library: Python comes with a large standard library that provides modules and packages for tasks such as string operations, file I/O, web services, and more. This reduces the need for additional libraries and enhances productivity.

   4. Cross-platform: Python is available for all major operating systems (Windows, macOS, Linux), ensuring compatibility across different platforms without modifications to the code. 

   Use Cases:
   1. Web Development: Python frameworks like Django and Flask are popular choices for building web applications due to their simplicity and robustness.

   2. Data Science and Machine Learning: Python's libraries such as NumPy, Pandas, SciPy, and machine learning frameworks like TensorFlow and PyTorch are widely used in data analysis, machine learning modeling, and AI applications.

   3. Automation and Scripting: Python's ease of use and cross-platform compatibility make it ideal for automation tasks, system administration, and scripting.

   4. Scientific Computing: Python's capabilities in handling complex mathematical computations, combined with libraries like SciPy, make it suitable for scientific computing and research.

   5. Game Development: Python, along with libraries like Pygame, is used in game development for prototyping, scripting, and building game logic.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   1. Download Python Installer from the official python website
   2. Run the installer
   3. Verify Installation
   4 Install 'virtualenv':Open a command prompt or PowerShell.
   Install virtualenv globally using pip (Python's package installer)
   5. Create a Virtual Environment:Choose or create a directory where you want to keep your Python projects.
   Navigate to that directory in the command prompt or PowerShell.
   6. Activate the Virtual Environment:To use the virtual environment, you need to activate it:
   In the command prompt or PowerShell, navigate into the directory where venv (or your chosen virtual environment name) is located.
   Navigate into the Scripts directory inside venv:Activate the virtual environment 
   7. Verify Virtual Environment:While the virtual environment is active, check Python's version again.It should reflect the version installed in your virtual environment (venv).
   8. Deactivate the Virtual Environment:
   To deactivate the virtual environment and return to the global Python environment.This restores your command prompt or PowerShell session to the global Python environment.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   print("Hello, World!")

   - print(): Function that outputs text to the console.
   - "Hello, World!": String literal containing the message to be printed.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic data types include:

   1. Integer (int): Whole numbers without decimal points.
   2. Float (float): Numbers with decimal points or in exponential form.
   3. String (str): Sequence of characters enclosed in quotes (single or double).
   4. Boolean (bool): Represents truth values True or False.
  
  Short script

   # Integer variable
   age = 25

   # Float variable
   height = 1.75

   # String variable
   name = "Alice"

   # Boolean variable
   is_student = True

   # Printing variables
   print("Name:", name)
   print("Age:", age)
   print("Height:", height)
   print("Is Student:", is_student)
5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   1. Conditional Statements (if-else): Used to make decisions based on conditions (if) and provide alternative actions (else) when conditions are not met.
   2. Loops (for): Used to iterate over sequences or collections of data, executing a block of code for each item in the sequence.

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   - Functions in Python are blocks of organized, reusable code that perform a specific task. 
   Usage - They allow you to break down your program into smaller, modular pieces, making it easier to manage, debug, and reuse code.
               
               script
   def calculate_sum(a, b):
    """
    Function to calculate the sum of two numbers.
    
    Parameters:
    a (int or float): First number
    b (int or float): Second number
    
    Returns:
    int or float: Sum of a and b
    """
    return a + b

   # Example of calling the calculate_sum function
   result = calculate_sum(5, 3)
   print("Sum:", result)  # Output: Sum: 8

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
      Lists (list):

   1. Ordered collection of items.
   2.Accessed by index (integer).
   Examples: [1, 2, 3], ['apple', 'banana', 'cherry'].

   Dictionaries (dict):

   1. Unordered collection of key-value pairs.
   2. Accessed by keys (can be any immutable type).
   3. Examples: {'name': 'Alice', 'age': 30}, {'fruit': 'apple', 'color': 'red'}.

   # List example
   numbers = [1, 2, 3]
   print("List:", numbers)
   print("First element:", numbers[0])  # Accessing by index
   print()

   # Dictionary example
   person = {'name': 'Alice', 'age': 30}
   print("Dictionary:", person)
   print("Name:", person['name'])  # Accessing by key
   print()

   # Modifying elements
   numbers[0] = 10
   person['age'] = 25
   print("Modified list:", numbers)
   print("Modified dictionary:", person)
   print()

   # Adding elements
   numbers.append(4)
   person['city'] = 'New York'
   print("List after adding element:", numbers)
   print("Dictionary after adding key-value pair:", person)
   print()

   # Removing elements
   removed_number = numbers.pop()
   del person['age']
   print("List after removing last element:", numbers)
   print("Dictionary after deleting key:", person)

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   - Exception handling helps manage errors or unexpected situations in your code without crashing the program.

      # Example: Handling division by zero and invalid input
   try:
      num1 = int(input("Enter a number: "))
      num2 = int(input("Enter another number: "))
      
      result = num1 / num2
      print("Result:", result)

   except ZeroDivisionError:
      print("Error: Division by zero is not allowed.")
      
   except ValueError:
      print("Error: Please enter valid integers.")

   finally:
      print("Execution completed.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   - Modules are individual Python files containing definitions and statements.
   - Packages are directories of modules with an __init__.py file, organizing code into namespaces.

  
   Importing and Using a Module in Python
   1. Importing Modules:Use the import statement followed by the module name.
   2. Using Functions or Classes:Access functions, classes, or variables defined in the module using dot notation (module_name.function() or module_name.variable).

   # Example: Using the math module to calculate square root and pi
   import math

   # Calculate square root
   num = 16
   sqrt = math.sqrt(num)
   print(f"Square root of {num}:", sqrt)

   # Access constant pi
   print("Value of pi:", math.pi)


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

   Reading from a File:
   To read from a file in Python:

   1. Open the File:Use open() with 'r' mode to open the file for reading.
   2. Read Content:Use read(), readline(), or readlines() to access the file's content.
   3. Close the File:Always close the file using close() to free up resources.
            example
   try:
      with open('example.txt', 'r') as file:
         content = file.read()
         print(content)

   except FileNotFoundError:
      print("Error: File not found.")

   except IOError:
      print("Error: Failed to read the file.")

      Writing to a File:
   To write to a file in Python:

   1. Open the File:Use open() with 'w' mode to open the file for writing.
   2. Write Content:Use write() or writelines() to write data to the file.
   3. Close the File:Always close the file using close() to save changes.
                example 
   data = ['Line 1\n', 'Line 2\n', 'Line 3\n']

   try:
      with open('output.txt', 'w') as file:
         file.writelines(data)
      print("Data successfully written to 'output.txt'.")

   except IOError:
      print("Error: Failed to write to the file.")

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


