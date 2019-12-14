# Python

Python is a dynamic, interpreted (bytecode-compiled) language for Rapid Application Development and also for scripting language.

# Two Types Of STrings:

1.Byte sequences have to be literal characters from the ASCII alphabet.
2.Unicode strings can hold onto pretty much any character


# Basic Python Notes:

1.Python provides a direct interface known as a Python Console to interact and execute the code directly. The advanced version of thePython console is the IPython (Interactive Python) console.

2. A whole number is called an integer and a fractional number is called a float. They are represented by int and float data types respectively.

3. Expressions are evaluated from left to right in Python. An expression with a float value as input will return the float output.

4. Strings are immutable in Python. They are written using a single quote or double quote and are represented by str data type. Any
characters enclosed within quotes is considered a string.

5. Comments are used to annotate code. In Python, # character marks the beginning of a single line comment. Python discards anything
written after the #.

6. Multiline comments are within triple single or double quotes. They start and end with either """ or ”’.

7. Use the type() function to determine the type of data, print() to print on the standard output device and format() to format the output.

8. Use the escape character to escape certain characters within a string.They can be used to mark tab within a line, a new line within a string
and so on.

9. Blocks of code are separated using indentation in Python. Code statements which go together within a single block must have
the same indentation level. Otherwise, Python will generate an IndentationError.


# Python Variables and Data Types 

1. A variable is used to store a value that can be used repetitively based on the requirement within a program.

2. Python is a loosely typed language. It is not required to specify the type of a variable while declaring it. Python determines the type of
the variable based on the value assigned to it.

3. Assignment operator = is used for assigning a value to a variable.

4. Variable names should start with either a letter or an underscore character.They can contain alpha-numeric characters only. It is a good
programming practice to have descriptive variable names.

5. Variable names are case sensitive and cannot start with a number.

6. There are four primitive data types in Python:
(a) Integer represented by int
(b) Float represented by float
(c) String represented by str
(d) Boolean (True or False) represented by bool

7. Internally, True is treated as 1 and False is treated as 0 in Python.

8. A substring or a part of a string is selected using the square brackets [] also known as slice operation.
9. Type conversion happens either implicitly or explicitly.
(a) Implicit type conversion happens when an operation with compatible data types is executed. For example, 4/2 (integer division)
will return 2.0 (float output).
(b) When an operation involves incompatible data types, they need to be converted to compatible or similar data type. For example:
To print a string and an integer together, the integer value needs to be converted to a string before printing.

# Standard Modules

• Text Processing : string, readline, re, unicodedata, etc.
• Data Types : datetime, calendar, array, copy, pprint, enum, etc.
• Mathematical : numbers, math, random, decimal, statistics, etc.
• Files and Directories : pathlib, stat, glob, shutil, filinput, etc.
• Data Persistence: pickle, dbm, sqlite3, etc.
• Compression and Archiving: gzip, bz2, zipfile, tarfile, etc
• Concurrent Execution: threading, multiprocessing, sched, queue,etc.
• Networking: socket, ssl, asyncio, signal, etc.
• Internet Data Handling: email, json, mailbox, mimetypes, binascii,etc.
• Internet Protocols: urllib, http, ftplib, smtplib, telnetlib, xmlrpc

# Data Structures

1. Data structures are used to store a collection of values.

2. Arrays, tuples, lists, sets and dictionaries are primitive data structuresin Python. Except for dictionaries, all data structures are sequential in
nature.

3. In Python, indexing starts with 0 and negative indexing starts with -1.

4. Elements within data structures are accessed using the slicing operation [start_index:end_index] where start_index is inclusive and
end_index is exclusive.

5. An array can hold a fixed number of data values of the same type.Arrays are not built-in data structures. We can use an array library to
perform basic array operations.

6. A tuple can hold multiple values of different types within it separated by commas. Tuples are enclosed within parentheses () and they are
immutable.

7. A list holds an ordered collection of items. Lists are created by placing all items within square brackets [] separated by a comma. They
can also be used to implement other data structures like stacks and
queues.

8. A list can also have another list as an item. This is called a nested list.

9. Dictionary stores data in the form of a key-value pair. It can be createdusing the curly brackets {}. Element/Pair within the dictionary is
accessed using the corresponding keys instead of an index.

10. Sets are an unordered data structure created using the curly brackets{}. It cannot contain duplicate elements.


# Python Keywords

1. Keywords are reserved words in Python. They can be used only in certain predefined ways when we code. They are always available
and cannot be used as a variable name, class name, function name or any other identifier.

2. Keywords are case-sensitive. All keywords are in lowercase except True, False and None.

3. In Python, logical expressions are evaluated from left to right.

4. Operators are special constructs or symbols which are used to perform operations on variables and literals.

5. Arithmetic operators are used for performing various mathematical operations.

6. Comparison operators are used for comparing two or more values. It works with almost all data types and returns either True or False as
an output.

7. Logical operators are used for comparing two or more conditional statements or expressions. They return boolean True or False as an
output.

8. Bitwise operators act on bits and perform bit by bit operations. These operators perform operations on a binary (0 and 1) equivalent of a
decimal number.

9. Assignment operators are used for assigning values to variables.

10. Membership operators check whether the given value exists in a data structure or not.

11. Identity operators check if two objects belong to the same memory location or refer to the same instances or not.

12. Each operator has specific precedence in Python. The precedence of any expression can be changed using the parenthesis ().
