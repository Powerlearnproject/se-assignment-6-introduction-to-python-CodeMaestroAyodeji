[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15290133&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
## Assignment: Introduction to Python

### Answers:

#### 1. Python Basics:
- **Python** is a high-level, interpreted programming language known for its simplicity and readability. Key features include:
  - **Easy to learn:** Simple syntax similar to English.
  - **Versatile:** Can be used for web development, data analysis, artificial intelligence, and more.
  - **Extensive Libraries:** A vast standard library and third-party modules.
  Example use case: Automating small tasks or building complex applications like web servers.

#### 2. Installing Python on Windows 10:
- **Download Python**: Go to the official Python website at [python.org](https://www.python.org/downloads/windows/) and download the latest version of Python for Windows 10.

- **Run Installer**: Open the downloaded file and run the installer. Ensure you check the box that says "Add Python to PATH" before clicking "Install Now".

- **Verify Installation**: Open Command Prompt and type `python --version`. You should see the Python version number if the installation was successful.

- **Set Up Virtual Environment**:
  - Install the virtualenv package: `pip install virtualenv`.
  - Create a new virtual environment: `virtualenv myenv`.
  - Activate the virtual environment:
    - On Command Prompt: `myenv\Scripts\activate`.

#### 3. Python Syntax and Semantics:
- Simple program:
  ```python
  print("Hello, World!")
This uses the print() function to output text to the console.

#### 4. Data Types and Variables:
Basic data types include integers (int), floating-point numbers (float), strings (str), and booleans (bool). Example script:
```python
number = 42        # int
pi = 3.14159      # float
greeting = "Hi"   # str
is_valid = True   # bool
```
#### 5. Control Structures:
Conditional statements (if-else) and loops (for, while) control flow based on conditions. Examples:
```Python

if temperature > 30:
    print("It's hot today!")
else:
    print("It's not too hot today.")

for i in range(5):
    print(i)
```
#### 6. Functions in Python:
Functions are reusable blocks of code. They’re useful for organizing code and avoiding repetition. Example function:
```Python
def add(a, b):
    return a + b

# Call the function
result = add(10, 20)
print(result) # Output: 30
```
#### 7. Lists and Dictionaries:
Lists are ordered collections, while dictionaries store key-value pairs. Example operations:
```Python
numbers = [1,2,3]

AI-generated code. Review and use carefully. More info on FAQ.
numbers.append(4) # Add to list

info = {‘name’: ‘Alice’, ‘age’:25} info[‘age’] =26 # Update dictionary
```


#### 8. Exception Handling:
- Exception handling allows for the management of errors gracefully using `try`, `except`, and `finally`. Example:

```python
try:
    result =10/0
except ZeroDivisionError:
    print("Can't divide by zero.")
finally:
    print("This always executes.")
```
#### 9. Modules and Packages:
- **Modules** are individual files containing Python code that can be reused in other Python scripts through importation. **Packages** are a way of structuring Python’s module namespace by using “dotted module names”. A package can contain one or more modules.

  To import and use a module, use the `import` statement. For example, to use the `math` module:
  ```python
  import math
  print(math.sqrt(16))  # Output: 4.0
   ```

#### 10. File I/O:
Reading from and writing to files is done using the built-in open() function, which returns a file object. To read from a file:
```Python

with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
```
To write to a file:
```Python
lines = ['Hello', 'World', 'Welcome to Python']
with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')
```
These examples demonstrate how to import and use modules, read content from a file, and write content to a file in Python. Remember to replace the filenames with the actual files you're working with in your script.


### References:
* Python Software Foundation. (2021). About Python. Retrieved from [python.org](https://www.python.org/about/)*
* Python Software Foundation. (2021). Using Python on Windows. Retrieved from [python.org](https://docs.python.org/3/using/windows.html)*