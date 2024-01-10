
# Readings: File I/O & Exceptions in Python

## Key Concepts and Questions

### 1. Purpose of the ‘with’ Statement in Python
The `with` statement in Python is crucial for managing resources, particularly for file operations. It simplifies exception handling by encapsulating common preparation and cleanup tasks in a block. This ensures that resources like files are properly closed after their use, even if an error occurs, thus preventing resource leaks.

### 2. Difference Between ‘read()’ and ‘readline()’
- `read()`: Reads the entire file's content into a string. It's ideal for smaller files where you need to process the entire content at once.
  
  **Example:**
  ```python
  with open('example.txt', 'r') as file:
      data = file.read()
  ```

- `readline()`: Reads one line from the file at a time. This method is more memory-efficient and suitable for large files or when you need to process each line individually.

  **Example:**
  ```python
  with open('example.txt', 'r') as file:
      line = file.readline()
      while line:
          print(line, end='')
          line = file.readline()
  ```

### 3. Exception Handling in Python
Exception handling in Python is achieved using the `try`, `except`, and `finally` blocks. This structure allows the program to respond to different types of errors without crashing.

- `try` block: The code that might raise an exception is placed here.
- `except` block: If an exception occurs, this block catches and handles it.
- `finally` block: This code runs no matter what, often used for cleanup.

**Example:**
```python
try:
    file = open('non_existent_file.txt', 'r')
except FileNotFoundError:
    print("File not found.")
finally:
    file.close()
```

## Things I Want to Know More About

- How can context managers (`with` statement) be created for custom resource management?
- Are there specific best practices for handling multiple different exceptions in a single try block?
- Examples of real-world scenarios where efficient file I/O operations and exception handling have significantly impacted a project.