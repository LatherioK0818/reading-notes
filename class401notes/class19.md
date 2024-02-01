# Regular Expressions in Python

Regular expressions (regex) are a powerful tool in Python for searching and manipulating strings. Python uses the `re` module to work with regular expressions. This module provides a set of functions that allows you to search for patterns within strings, replace parts of strings, split strings based on regex patterns, and more.

For example, if you want to find all instances of a specific pattern in a string, like email addresses or phone numbers, you can use `re.findall()`. Here's a basic example:

```python
import re

text = "Contact us at support@example.com or sales@example.com"
emails = re.findall(r'\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Z|a-z]{2,}\b', text)

print(emails)
```

In this example, `re.findall()` searches `text` for any pattern that matches the regular expression for email addresses.

## The shutil Module in Python

The `shutil` (shell utilities) module in Python provides a higher-level interface for file operations. It is particularly useful for operations involving copying and removal of files and directories.

A common use case for `shutil` is copying a file from one directory to another. Here's an example:

```python
import shutil

shutil.copy('source.txt', 'destination.txt')
```

This command copies the file `source.txt` to a new file called `destination.txt`. It's a more convenient method than opening the source file, reading its content, and writing it to the destination file.

## Comparing os and shutil Modules

The `os` and `shutil` modules are both used for file and directory operations, but they serve slightly different purposes.

- **os module**: This module provides a way to interact with the operating system. You can use it to do things like create directories, delete files, move files, and get information about files. It's more granular and works well for file-level operations.

- **shutil module**: This module is better for higher-level file operations, like copying or moving entire directories. It is more convenient for tasks that involve multiple files or directories at once.

You would choose `os` when you need more control over individual file operations, like changing file permissions or working with file paths. On the other hand, `shutil` is more efficient for bulk file operations like copying directories.

## Things I Want to Know More About

- Advanced uses of regular expressions for complex string patterns.
- Best practices for managing file systems in Python.
- Differences in performance between `os` and `shutil` for large-scale file operations.

