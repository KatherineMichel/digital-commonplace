# Python Notes- Additional

# Python Glossaries and ToCs

Search attribute reference, Class Objects and Instance Objects

https://runestone.academy/runestone/static/thinkcspy/Appendices/PrecedenceTable.html#operator-summary

<!--
## Installation

IDEs
* [Python Integrated Development Environments (IDEs) Page](https://wiki.python.org/moin/IntegratedDevelopmentEnvironments)

http://docs.python-guide.org/en/latest/starting/installation/
http://docs.python-guide.org/en/latest/dev/virtualenvs/
-->

<!--
Mastering Regular Expressions Jeffrey Friedl
https://it-ebooks.info/search/?q=mastering+regular+expressions&type=title
http://regex.info/book.html

RegEx
* [Regular Expression Wikipedia](http://en.wikipedia.org/wiki/Regular_expression)  
* [Learning to Code the Hard Way- RegEx](http://regex.learncodethehardway.org) 

http://www.diveintopython.net/regular_expressions/
-->

### Python Debugging

<!--
pdb.set_trace
idbp trace
dtrace
-->
	   
## The Python Tutorial

Django Notes
https://code.djangoproject.com/wiki/NewbieMistakes | NewbieMistakes – Django
https://www.python.org/download/releases/2.2/descrintro/#metaclasses | Unifying types and classes in Python 2.2 | Python.org
https://code.djangoproject.com/wiki/DynamicModels | DynamicModels – Django
https://code.djangoproject.com/wiki/DevModelCreation | DevModelCreation – Django

https://docs.python.org/2/howto/doanddont.html | Idioms and Anti-Idioms in Python — Python 2.7.15 documentation
https://docs.python-guide.org/writing/gotchas/ | Common Gotchas — The Hitchhiker's Guide to Python
http://django-gotchas.readthedocs.io/en/latest/ | Welcome to Django gotchas documentation! — Django gotchas 0.1 documentation

<!--
Possible repeats in here

https://docs.python.org/3/library/stdtypes.html

https://docs.python.org/3/reference/datamodel.html
https://docs.python.org/3/library/datatypes.html
https://docs.python.org/3/tutorial/datastructures.html
https://docs.python.org/3/library/dataclasses.html
https://docs.python.org/3/tutorial/classes.html
https://docs.python.org/3/library/functions.html

https://docs.python.org/3/reference/expressions.html
https://docs.python.org/3/reference/simple_stmts.html
https://docs.python.org/3/reference/compound_stmts.html

https://docs.python.org/3/tutorial/controlflow.html
https://docs.python.org/3/tutorial/controlflow.html#more-control-flow-tools

https://docs.python.org/3/reference/introduction.html#alternate-implementations

https://docs.python.org/3/tutorial/inputoutput.html#input-and-output

https://docs.python.org/3/tutorial/datastructures.html#data-structures

 
https://docs.python.org/3/tutorial/classes.html#odds-and-ends

27. Development Tools
https://docs.python.org/3/library/development.html#development-tools

ToCs
https://docs.python.org/3/library/language.html
https://docs.python.org/3/library/internet.html
https://docs.python.org/3/library/python.html
12. Data Persistence
https://docs.python.org/3/library/persistence.html

3.1. Constants added by the site module
https://docs.python.org/3/library/constants.html#constants-added-by-the-site-module

8.10. copy — Shallow and deep copy operations
https://docs.python.org/3/library/copy.html

## Notes

## How Tos

Porting Python 2 Code to Python 3
Porting Extension Modules to Python 3
Curses Programming with Python

Descriptor HowTo Guide
https://docs.python.org/3/howto/descriptor.html

https://docs.python.org/3/library/functional.html

Functional Programming HOWTO
https://docs.python.org/3/howto/functional.html

An introduction to the ipaddress module

Argument Clinic How-To
https://docs.python.org/3/howto/clinic.html

Instrumenting CPython with DTrace and SystemTap

## Utilities

19. Internet Data Handling
https://docs.python.org/3/library/netdata.html


37. Superseded Modules
37.1. optparse — Parser for command line options
37.2. imp — Access the import internals

"The modules described in this chapter are deprecated and only kept for backwards compatibility. They have been superseded by other modules."
https://docs.python.org/3/library/superseded.html
Continue...

38. Undocumented Modules
38.1. Platform specific modules

https://docs.python.org/3/library/undoc.html



<!--
## Protocols

<!--
https://docs.python.org/3/library/http.server.html#http.server.BaseHTTPRequestHandler

https://docs.python.org/3/library/urllib.parse.html#url-quoting
-->

<!--
Three Types of Assignment
https://medium.com/broken-window/many-names-one-memory-address-122f78734cb6

Dot notation
https://www.codecademy.com/en/forum_questions/5170307264a7402d9a0012f5

See also: expressions comparisons

https://dbader.org/blog/difference-between-is-and-equals-in-python
-->

https://stackoverflow.com/questions/21553327/why-is-except-pass-a-bad-programming-practice

You can see all list methods by calling the help for lists! help(list)
https://github.com/Stephen-Rimac/Python-for-Data-Scientists/blob/master/Python%20for%20Data%20Scientists.ipynb

https://stackoverflow.com/questions/9189172/why-doesnt-calling-a-python-string-method-do-anything-unless-you-assign-its-out

https://github.com/leon-lee-jl/JLDoc/blob/master/source/profession/books/data_structure_and_algorithms_in_python.rst
-->

<!--
Navigating Your FileSystem
Magic Commands
List directory contents of files and directories 
Return the current working directory path
$ pwd

os Library
>>> import os
>>> path = "/usr/tmp"
>>> wd = os.getcwd()
>>> os.listdir(wd)
>>> os.chdir(path)
>>> os.rename("test1.txt",
              "test2.txt")
>>> os.remove("test1.txt")
>>> os.mkdir("newdir")
Store the name of current directory in a string 
Output contents of the directory in a list 
Change current working directory
Rename a file
Delete an existing file 
Create a new directory
-->

<!--
The default prompt of Python interactive shell when entering code for an indented code block
... when within a pair of matching left and right delimiters (parentheses, square brackets, curly braces or triple quotes), or after specifying a decorator.
-->

<!--
down arrow to scroll
-->

## Scripts

<!--
Three main types of I/O
* text I/O
* binary I/O
* raw I/O. 

* file object
* stream object
* file-like object
-->

<!--
### Multiplication, Floating Point Division, Floor Division, Modulo/Modulus/Remainder 

32, 64 bits
Floating point numbers and division explanation

"x divided by y with z remaining." 
-->

## Conditions

<!--
List (mutable, sequence, iterable)

['__add__', '__contains__', '__delitem__', '__getitem__', '__iadd__', '__imul__', '__iter__', '__len__', '__mul__', '__reduce__', '__reduce_ex__', '__reversed__', '__rmul__', '__setitem__', '__sizeof__', '__str__'

'append', 'clear', 'copy', 'count', 'extend', 'index', 'insert', 'pop', 'remove', 'reverse', 'sort']

String (immutable, sequence, iterable)

['__add__', '__contains__', '__getitem__', '__getnewargs__', '__iter__', '__len__', '__mod__', '__mul__', '__reduce__', '__reduce_ex__', '__rmod__', '__rmul__', '__sizeof__', '__str__'

'capitalize', 'casefold', 'center', 'count', 'encode', 'endswith', 'expandtabs', 'find', 'format', 'format_map', 'index', 'isalnum', 'isalpha', 'isdecimal', 'isdigit', 'isidentifier', 'islower', 'isnumeric', 'isprintable', 'isspace', 'istitle', 'isupper', 'join', 'ljust', 'lower', 'lstrip', 'maketrans', 'partition', 'replace', 'rfind', 'rindex', 'rjust', 'rpartition', 'rsplit', 'rstrip', 'split', 'splitlines', 'startswith', 'strip', 'swapcase', 'title', 'translate', 'upper', 'zfill']

Tuple (immutable, sequence, iterable)

['__add__', '__contains__', '__getitem__', '__getnewargs__', '__iter__', '__len__', '__mul__', '__reduce__', '__reduce_ex__', '__rmul__', '__sizeof__', '__str__'

'count', 'index']

Dict (mutable, non-sequence, iterable)

['__contains__', '__delitem__', '__getitem__', '__iter__', '__len__', '__reduce__', '__reduce_ex__', '__setitem__', '__sizeof__', '__str__'

'clear', 'copy', 'fromkeys', 'get', 'items', 'keys', 'pop', 'popitem', 'setdefault', 'update', 'values']

Set (mutable, non-sequence, iterable)

['__and__', '__contains__', '__iand__', '__ior__', '__isub__', '__iter__', '__ixor__', '__len__', '__or__', '__rand__', '__reduce__', '__reduce_ex__', '__ror__', '__rsub__', '__rxor__', '__sizeof__', '__str__', '__sub__', '__xor__'

'add', 'clear', 'copy', 'difference', 'difference_update', 'discard', 'intersection', 'intersection_update', 'isdisjoint', 'issubset', 'issuperset', 'pop', 'remove', 'symmetric_difference', 'symmetric_difference_update', 'union', 'update']

Int and Bool

['__abs__', '__add__', '__and__', '__bool__', '__ceil__', '__divmod__', '__float__', '__floor__', '__floordiv__', '__getnewargs__', '__index__', '__int__', '__invert__', '__lshift__', '__mod__', '__mul__', '__neg__', '__or__', '__pos__', '__pow__', '__radd__', '__rand__', '__rdivmod__', '__reduce__', '__reduce_ex__', '__rfloordiv__', '__rlshift__', '__rmod__', '__rmul__', '__ror__', '__round__', '__rpow__', '__rrshift__', '__rshift__', '__rsub__', '__rtruediv__', '__rxor__', '__sizeof__', '__str__', '__sub__', '__truediv__', '__trunc__', '__xor__'

'bit_length', 'conjugate', 'denominator', 'from_bytes', 'imag', 'numerator', 'real', 'to_bytes']

Float

['__abs__', '__add__', '__bool__', '__divmod__', '__float__', '__floordiv__', '__getformat__', '__getnewargs__', '__int__', '__mod__', '__mul__', '__neg__', '__pos__', '__pow__', '__radd__', '__rdivmod__', '__reduce__', '__reduce_ex__', '__rfloordiv__', '__rmod__', '__rmul__', '__round__', '__rpow__', '__rsub__', '__rtruediv__', '__setformat__', '__sizeof__', '__str__', '__sub__', '__truediv__', '__trunc__'

'as_integer_ratio', 'conjugate', 'fromhex', 'hex', 'imag', 'is_integer', 'real']

Dir

All have
'__dir__'
'__init__'
'__init_subclass__'
'__class__'
'__delattr__'
'__getattribute__'
'__setattr__'
'__repr__'
'__subclasshook__'
'__format__'
'__doc__'
'__hash__'
'__eq__'
'__ge__'
'__gt__'
'__le__'
'__lt__'
'__ne__'
'__new__'
-->

<!--
dictionary view
-->


### Indentation

Nesting
* nesting can be useful in some situations, but can also make your code unnecessarily complex
* there might be a simpler way of managing the data (example: classes)

Rules
* any lines that are not indented run after the loop is completed

Nesting example


<!--
print, return statement
-->

## Functions

Functions
* named blocks of code
* designed to do one job 

## Built-In Functions, Call, Attribute Reference

Built-In Function

```python
function(object)
```

Built-In Function

```python
function(argument)
```

Built-In Function

```python
function(arguments...)
```

Built-In Function Example

```python
>>> an_integer = 5
>>> str(an_integer)
'5'
```

Not dot notation

```python
>>> an_integer.str()
```

<!--
Why does sorted() work this way?
-->

## Methods

"Methods are functions that are called using the attribute notation."

Two types of methods

* built-in methods
* class instance methods

## Variable (or Object) and Dot Notation

Dot notation
* the dot tells Python to perform method (action) on preceding variable
* parenthesis exist for additional argument, if needed; otherwise empty

Variable

```python
variable.attribute
variable.method()
```

Chaining

```python
variable.method().method()
```

## Functions

A simple function

```python
def function():
    action

function()
```

Passing an argument

```python
def function(argument):
    action involving argument

function(argument)
```

Default values for parameters

```python
def function(parameter=argument):
    action involving argument

function()
function(argument)
```

<!--
Python Crash Course Cheat Sheet Notes
Returning a value

def add_numbers(x, y):
    """Add two numbers and return the sum."""
    return x + y

sum = add_numbers(3, 5)
print(sum)
-->

## Object-Oriented Programming

<!--
Python Crash Course Cheat Sheet Notes

Class
A class defines the behavior of an object and the kind of information an object can store.
A child class inherits the attributes and methods from its parent class.
-->

### Parts

Function

Types of attributes (info stored within a class)
* class attribute
* instance attribute

Functions versus methods (behavior that takes place within a class)
* a function that belongs to a class is called a method

Types of methods
* class method
* instance method
* static method

Transform a method into a class method or static method.

```classmethod()```
```staticmethod()```

### Class, Instance, and Ineritance

Define a class (usually a noun, can have attributes and methods (a function within a class namespace))

```python
class Class:
    def __init__(self, attribute):
        self.attribute = attribute
 
    def method(self):
        action
```

Create an instance of a class

```python
instance_name = Class(attribute)
another_instance_name = Class(attribute)
```

Namespace access of object instance attributes and methods through dot notation

```python
instance_name.attribute
instance_name.method()
another_instance_name.attribute
another_instance_name.method()
```

Inheritance

```python
class NewClass(Class):
    def __init__(self, attribute):
        super().__init__(attribute)
                
    def method(self):
        action
```

Create an instance of a new class

```python
new_instance_name = NewClass(attribute)
another_new_instance_name = NewClass(attribute)
```

Access instance attributes and methods

```python
new_instance_name.attribute
new_instance_name.method()
another_new_instance_name.attribute
another_new_instance_name.method()
```


## Formatting and f-strings

Insert dynamic value into a string

```python
>>> '1 + 2 = {}'.format(1 + 2)
'1 + 2 = 3'
```

Insert 3 dynamic values into a string

```python
>>> '{} + {} = {}'.format(1, 2, 1 + 2)
'1 + 2 = 3'
```

## Open File, Read, and Write to File

<!--
Python Crash Course

Reading line by line
Each line that's read from the file has a newline character at the end of the line, and the print function adds its own newline character. The rstrip() method gets rid of the the extra blank lines this would result in when printing to the terminal.

print(line.rstrip())
contents = file_object.read()
lines = file_object.readlines()
file_object.write("New line")
file_object.write("New line\n") 

How are these different?
Read a file line by line
Read a file and store its lines (in a list)

file_object is a made up variable


Data Camp Cheat Sheet Example

Text Files
Plain Text Files
>>> filename = 'huck_ nn.txt'
>>> file = open(filename, mode='r')
>>> text = file.read()
>>> print(file.closed)
>>> file.close()
>>> print(text)
Open the file for reading 
Read a file’s contents
Check whether file is closed 
Close file

Using the context manager with
>>> with open('huck_ nn.txt', 'r') as file:
        print(file.readline())
        print(file.readline())
        print(file.readline())
Read a single line
-->

Passing arguments to open()
* Files are opened in read mode ('r') by default
* Pass the 'w' argument to open() to write to the file (will erase contents of file if it already exists)
* Pass the 'a' argument to open() to append to the end of an existing file

Read from and write to a file
* open the file
* read the contents of the file (all at once or line by line)
* the with statement ensures the file is properly closed when the program is done accessing the file

<!--
Notes from Python Crash Course Files and Exceptions Cheet Sheet

write data to files. writing to files allows users to pick up where they left off the next time they run your program. You can write text to files, and you can store Python structures such as lists in data files.
-->

Open file and return a corresponding file object. 

```open()```

<!--
When Python runs the open() function, it looks for the file in the same directory where the program that's being excuted is stored. You can open a file from a subfolder using a relative path. You can also use an absolute path to open any file on your system.
-->

Read an entire file at once

```python
file_name = 'file.txt'

with open(file_name) as file_object:
    contents = file_object.read()
    
print(contents)
```

Read a file line by line

```python
file_name = 'file.txt'

with open(file_name) as file_object:
    for line in file_object:

print(line.rstrip())
```

Read a file and store its lines (in a list)

```python
file_name = 'file.txt'

with open(file_name) as file_object:
    lines = file_object.readlines()
    
for line in lines:
    print(line)
```

Alternatively

```python
for line in lines:
    print(line.rstrip())
```

Write to an empty file

```python
file_name = 'file.txt'

with open(file_name, 'w') as file_object:
    file_object.write("New line")
```

Write multiple lines to an empty file

```python
file_name = 'file.txt'

with open(file_name, 'w') as file_object:
    file_object.write("New line\n")
    file_object.write("New line\n")
```

Append to a file

```python
file_name = 'file.txt'

with open(file_name, 'a') as file_object:
    file_object.write("New line")
```
    
File paths- Open a file from a subfolder

```python
file_path = "directory/file.txt"

with open(file_path) as file_object:
    lines = file_object.readlines()

for line in lines:
    print(line.rstrip())
```
    
File paths- Open a file using an absolute path

```python
file_path = "/home/directory/directory/file.txt"

with open(file_path) as file_object:
    lines = file_object.readlines()
```

File paths- Open a file on Windows (might need to use backslashes)

```python
file_path = "C:\Users\directory\directory\file.txt"

with open(file_path) as file_object:
    lines = file_object.readlines()
```


<!--
https://github.com/Stephen-Rimac/Python-for-Data-Scientists/blob/master/Python%20for%20Data%20Scientists.ipynb
input/output methods
"Note that when text files are read using the splitlines() function, the resulting object is a list."
So the object you just created from the file - is a list.

Operations you might use after opening a file

# Read list  
with open('directory/file.txt', 'r') as file_object:
    lines = file_object.read().splitlines()
    
print(type(lines))

Print length of each list
print(len(lines))

Print the first 5 items
print(lines[:5])

Membership
print('String' in lines)

Print minimum value in lines (min in this case is alphabet-sorted)
print(min(lines))

Print maximum value in lines
print(max(lines))
-->

## Python and Django Control Flow

<!--
7. Simple statements

8. Compound statements

"A compound statement consists of one or more ‘clauses.’ A clause consists of a header and a ‘suite.’ The clause headers of a particular compound statement are all at the same indentation level. Each clause header begins with a uniquely identifying keyword and ends with a colon. A suite is a group of statements controlled by a clause. A suite can be one or more semicolon-separated simple statements on the same line as the header, following the header’s colon, or it can be one or more indented statements on subsequent lines. Only the latter form of a suite can contain nested compound statements; the following is illegal, mostly because it wouldn’t be clear to which if clause a following else clause would belong:"
-->

## Conditional Tests

See previous section

<!--
for Statement Example

for element in [1, 2, 3]:
    print(element)
for element in (1, 2, 3):
    print(element)
for key in {'one':1, 'two':2}:
    print(key)
for char in "123":
    print(char)
for line in open("myfile.txt"):
    print(line, end='')
-->

### range() Function (for Statement)

<!--
range = list(range(1, 1000001))
range = [action for i in range(x, y)]
list_comprehension = [items.method() for item in items]
-->


### with Statement

<!--
"The with statement is used to wrap the execution of a block with methods defined by a context manager"
-->


## Examples

### Remove Items From a List (while Statement)

Remove all instances of a value from a list

```python
while item in items:
    items.remove(item)
print(items)
```

<!--
Are dictionary keys always referred to as 'key'?
-->


### Dictionary Order and OrderedDict (for Statement)

<!--
how many spaces between import and next line?
-->

A dictionary only tracks the connections between keys and values, not order added.

Loop through all the keys, sorting them, and show value by order of key

```python
for key in sorted(a_dictionary.keys()):
    print(key, value)
```

Use OrderedDict to show keys and values in order added

```python
from collections import OrderedDict

a_dictionary = OrderedDict()

a_dictionary[key] = [value, value]
a_dictionary[key] = [value]
```

```python
for key, value in a_dictionary.items():
    print(key)
    for value in values:
        print(value)
```



## Dictionaries and Lists- Nesting

Storing dictionaries in a list

```python
a_list = []

new_item = {
    key: value,
    key: value,
    key: value,
    }
a_list.append(new_item)

new_item = {
    key: value,
    key: value,
    key: value,
    }
a_list.append(new_item)
```

```python
for item_dict in a_list:
    for key, value in item_dict.a_list():
        print(key, value)
    print("\n")
```

Define a list of dictionaries directly, without using append()

```python
a_list = [
    {
        key: value,
        key: value,
        key: value,
    }, 
    {
        key: value,
        key: value,
        key: value,
    }, 
]
```

```python
for item_dict in a_list:
    for key, value in item_dict.items():
        print(key, value)
    print("\n")
```

Storing lists in a dictionary (allows you to associate more than one value with each key)

```python
a_dictionary = {
    key: [value],
    key: [value, value],
    key: [value, value, value],
}
```

```python
for key, value in a_dictionary.items():
    print(key)
    for value in values:
        print(value)
```

Storing dictionaries in a dictionary (each value associated with a key is itself a dictionary)

```python
a_dictionary = {
    another_dictionary: {
        key: value,
        key: value,
        key: value,
        },
    yet_another_dictionary: {
        key: value,
        key: value,
        key: value,
        },
}
```


<!--
Python Crash Course Cheat Sheet Notes
    
for name, item_dict in a_dictionary.items():

    print("\nUsername: " + username)
    full_name = user_dict['first'] + " "
    full_name += user_dict['last']
    location = user_dict['location']
    
    print("\tFull name: " + full_name.title())
    print("\tLocation: " + location.title())
-->


<!--
Python Crash Course Cheat Sheet Notes

You can use a loop to generate a list based on a range of numbers or on another list.
define an expression for the values you want to store in the list. Then write a for loop to generate input values needed to make the list.

You can use the list() function to efficiently generate a large list of numbers."


Letting the user choose when to quit
msg = ''
while msg != 'quit':
    msg = input("What's your message? ")
    print(msg)
-->

<!--
Python Crash Course Cheat Sheet Notes

* Items can be accessed through an index or loop

"It is sometimes tempting to change a list while you are looping over it; however, it is often simpler and safer to create a new list instead."

Looping through a list
Lists can contain millions of items, so Python provides an efficient way to loop through all the items in a list. When you set up a loop, Python pulls each item from the list one at a time and stores it in a temporary variable, which you provide a name for. This name should be the singular version of the list name.

The indented block of code makes up the body of the loop, where you can work with each individual item. Any lines that are not indented run after the loop is completed.

Build a list and print the items in the list

dogs = []
dogs.append()

for dog in dogs:
    print("Hello " + dog + "!")
print("I love these dogs!")

print("\nThese were my first two dogs:")
old_dogs = dogs[:2]
for old_dog in old_dogs:
    print(old_dog)

del dogs[0]
dogs.remove('peso')
print(dogs)
-->

<!--
Syntax examples
print("Answer:")
print(1 + 1)
print("Answer:", 1 + 1)


Example Patterns

Insert a variable into string
Find the length of a list (number of items)
number_items = len(items)
print("We have " + str(number_items) + " items.")

Insert variable that was entered as string

def greet_user(username):
    """Display a personalized greeting."""
    print("Hello, " + username + "!")

greet_user('Kati')

List of users, stored as strings

Printing a message for each item, and a separate message afterwards

for user in users:
    print("Welcome, " + user + "!")
    

a_dictionary = {'key': 'value', 'key': 'value'}
    print("The dictionary key is " + a_dictionary['key'])
    
list_message = "String " + item[index].method() + "." 
    
General syntax example
# Show each person's favorite language.
for name, language in fav_languages.items():
    print(name + ": " + language)
    
Default values for parameters

def make_pizza(topping='bacon'):
    """Make a single-topping pizza."""
    print("Have a " + topping + " pizza!")

make_pizza()
make_pizza('pepperoni')
-->

### try-except Statement

<!--
* try statement (except, else)

Notes from Python Crash Course Files and Exceptions Cheet Sheet

Exceptions help you respond appropriately to errors that are likely to occur. 

Exceptions are special objects that help your programs respond to errors in appropriate ways. For example if your program tries to open a file that doesn’t exist, you can use exceptions to display an informative error message instead of having the program crash.

Practice with exceptions
Take a program you've already written that prompts for user input, and add some error-handling code to the program.

Knowing which exception to handle 
It can be hard to know what kind of exception to handle when writing code. Try writing your code without a try block, and make it generate an error. The traceback will tell you what kind of exception your program needs to handle.

Handling the ZeroDivisionError exception


try:
    print(5/0)
except ZeroDivisionError:
    print("You can't divide by zero!")

Handling the FileNotFoundError exception

f_name = 'siddhartha.txt'

try:
    with open(f_name) as f_obj:
        lines = f_obj.readlines()
except FileNotFoundError:
    msg = "Can't find file {0}.".format(f_name)
    print(msg)


Using an else block

print("Enter two numbers. I'll divide them.")

x = input("First number: ")
y = input("Second number: ")

try:
    result = int(x) / int(y)
except ZeroDivisionError:
    print("You can't divide by zero!")
else:
    print(result)


Preventing crashes from user input
Without the except block in the following example, the program would crash if the user tries to divide by zero. As written, it will handle the error gracefully and keep running.      

"""A simple calculator for division only."""

print("Enter two numbers. I'll divide them.")
print("Enter 'q' to quit.")

while True:
    x = input("\nFirst number: ")
    if x == 'q':
        break
    y = input("Second number: ")
    if y == 'q':
        break

try:
        result = int(x) / int(y)
    except ZeroDivisionError:
        print("You can't divide by zero!")
    else:
        print(result)

Using the pass statement in an else block

f_names = ['alice.txt', 'siddhartha.txt',
        'moby_dick.txt', 'little_women.txt']

for f_name in f_names:
    # Report the length of each file found.
    try:
        with open(f_name) as f_obj:
            lines = f_obj.readlines()
    except FileNotFoundError:
         # Just move on to the next file.
         pass 
     else:
        num_lines = len(lines)
        msg = "{0} has {1} lines.".format(
            f_name, num_lines)
        print(msg)
-->

<!--
Python Crash Course

Deciding which errors to report
Well-written, properly tested code is not very prone to internal errors such as syntax or logical errors. But every time your program depends on something external such as user input or the existence of a file, there's a possibility of an exception being raised.
Sometimes users need to know if a file is missing
-->

### except

<!--
"The except clause(s) specify one or more exception handlers."
-->

<!--
Python Crash Course

Exception-handling code should catch specific exceptions that you expect to happen during your program's execution. A bare except block will catch all exceptions, including keyboard interrupts and system exits you might need when forcing a program to close. If you want to use a try block and you're not sure which exception to catch, use Exception. It will catch most exceptions, but still allow you to interrupt programs intentionally.
-->


## Data Structures

### Check Membership in a List

Test if a value is in or not in a list

```python
>>> alphabet = ['a', 'b', 'c', 'd']
>>> 'a' in alphabet
True
>>> 'z' in alphabet
False
>>> 'a' not in alphabet
False
>>> 'z' not in alphabet
True
```

Check if a list is empty

  
## List (mutable, sequence, iterable)

A collection of items stored in a particular order (ex. letters of the alphabet, the digits from 0–9, or the names of family members). Similar to a tuple or array, but can mix data types and items can be modified. Most list will be dynamic- you will add and remove elements as the program runs.

* List names are usually plural, for readability
* Items can be accessed through an index or loop

Create empty list and add items to the list

```python
items = []
items.append(<new-value>)
items.append(<new-value>)
items.append(<new-value>)
```

<!--
???
items.append = <new-value>
-->
  
## Array

Similar to a list, but stores items of same type; type is specified at object creation using type code (a single character)

## Tuple (immutable, sequence, iterable)

Similar to a list, but items can't be modified. Can only overwrite the entire tuple.

Create a tuple

```python
a_tuple = ()
```

Overwrite a tuple

```python
a_tuple = ()
print(a_tuple)
a_tuple = ()
print(a_tuple)
```

Tuple singleton

```python
a_tuple = (value,)
```

<!--
Python- Journey from Notive to Expert
"To me, tuples are Python's built-in data that most closely represent a mathematical vector. Tuples usually contain an heterogeneous sequence of elements, while on the other hand lists are most of the times homogeneous. Moreover, tuples are normally accessed via unpacking or indexing, while lists are usually iterated over."
-->

## Dictionary (mutable, non-sequence, iterable)
 
Items are stored as key-value pairs. When you provide the key, Python returns the value linked to the key. Only immutable/hashable data types can be used as keys (string, tuple, etc.).

Dictionaries

```python
items = {}
```

```python
items = {key: value, key: value}
```

```python
items = {
    key: value,
    key: value,
    key: value,
 }
```

<!--
Python Crash Course Notes
     
Accessing values
If the key you're asking for is not in the dictionary, an error will occur.
You can also use the get() method, which returns None instead of an error if the key doesn't exist. You can also specify a default value to use if the key is not in the dictionary.
-->

## Set (mutable, non-sequence, iterable)

A set of integers

```python
a_set = {0, 1, 2, 3, 4}
```

## String (immutable, sequence, iterable)



## Subscription, Slicing

Bracket Notation and Zero-Based Numbering
* [Bracket Notation Wikipedia](https://en.wikipedia.org/wiki/Bracket_(mathematics))
* [Zero-Based Numbering Wikipedia](https://en.wikipedia.org/wiki/Zero-based_numbering)

Zero-Based Numbering
* Index of first item is 0, second is 1, etc.
* Negative index indicates items is at the end of the list 

Subscription 
"A subscription selects an item of a sequence (string, tuple or list) or mapping (dictionary) object"

```python
x[index]
```

Slicing
"A slicing selects a range of items in a sequence object (e.g., a string, tuple or list). Slicings may be used as expressions or as targets in assignment or del statements."

```python
x[index:index]
```


## Sequence Operations

Sequence Examples

```python
items = 'astring'
items = [1, 2, 3]
items = ['astring', 'astring', 'astring']
```

### Mutable Sequence Type Operations (list, byte array)

Operation/Result (See notes)

```python
items[i] = x	    item i of items is replaced by x	 
items[i:j] = t	    slice of items from i to j is replaced by the contents of the iterable t	 

del items[i:j]	    same as items[i:j] = []	 
items[i:j:k] = t	the elements of items[i:j:k] are replaced by those of t
del items[i:j:k]	removes the elements of items[i:j:k] from the list	 
items.clear()	    removes all items from items (same as del items[:])
items.remove(item)	    remove the first item from items where items[i] == x

items.append(x)	    appends x to the end of the sequence (same as items[len(items):len(items)] = [x])	 
items.extend(t)     or items += t	extends items with the contents of t (for the most part the same as items[len(items):len(items)] = t)	 
items.insert(i, x)	inserts x into items at the index given by i (same as items[i:i] = [x])	 


items.copy() (create a shallow copy of items (same as items[:]))
items.pop([i]) (retrieve the item at index and also remove it from items)
items.reverse() (reverse the order of items in place)

items *= n (update items with its contents repeated n times)
```

### Mutable and Immutable Sequences Type Operations (list, string, tuple, bytes, range?)

"The operations in the following table are supported by most sequence types, both mutable and immutable"

Subscription and Slicing (up to but not including stopping point)

```python
items[x] (item at x index, origin 0)
items[x:y] (slice of items from x to y)
items[x:y:z] (slice of items from x to y with step z)
items.index(x[, y[, z]]) (index of the first occurrence of x in items (at or after index y and before index z))
```

Concatenation and Multiplication

```python
items + items (the concatenation of sequences)
items * x (add sequence to itself, x number of times)
```

Membership

```python
item in items                
item not in items	            
```

Smallest or Largest Item

```python
min(items) (smallest item in sequence)               	 
max(items) (largest item in sequence)
```

Length and Count

```python
len(items) (length of sequence)	 
items.count(x) (total number of occurrences of x in sequence)
```

<!--
List Operations

print( 3 in a ) # Membership
True
print( min(b), max(b) ) # Min, Max
4 6
-->

### Sequence Subscription Examples

```python
first_item = items[0]
second_item = items[1]
last_item = items[-1]
second_from_last_item = items[-2]
third_from_last_item = items[-3]
```

Newest and Oldest Items

```python
oldest_item = items[0]
newest_item = items[-1]
```

### Sequence Slicing Examples

Slice a sequence
     
```python
first_three_items = items[:3]
middle_three_items = items[1:4]
last_three_items = items[-3:]
```

<!--
items[0:2]
items[0:]
items[:]

Slicing a list
You can work with any set of elements from a list. A portion of a list is called a slice. To slice a list start with the index of the first item you want, then add a colon and the index after the last item you want. Leave off the first index to start at the beginning of the list, and leave off the last index to slice through the end of the list.
   
https://github.com/Stephen-Rimac/Python-for-Data-Scientists/blob/master/Python%20for%20Data%20Scientists.ipynb

# Selects all starting from the 2nd element, but BEFORE the 4th element
# Selects all BEFORE the 4th element
# Selects all starting from the 2nd element

# Select the last element
# Select all BEFORE the last element
# Selects all starting from the 2nd element, but before the last element
-->

### Common String Methods (immutable, sequence, iterable)

In the example of replace(), a new string is created

```python
a_string = 'astring'
a_string.upper()
a_string.lower()
a_string.count('a')
a_string.replace('a', 'z')
a_string.strip()
```

### Common List Methods (mutable, sequence, iterable)

See also: Mutable Sequence Type Operations (list, byte array)

Find an item through index

```python
items[index]
```

Find index of item

```python
items.index(item)
```

You can use a method on item

```python
items[index].method()
```

Insert item at a particular index

```python
items.insert(index, item)
```

Change item

```python
items[index] = item
```

Append an item (to the end of the list)

```python
items.append(item)
```

Extend existing list by appending another list

```python
items.extend(another_list)
```

Sorting: reversing order is an option; lowercase and uppercase letters might affect sort order.

Sort a list permanently

```python
items.sort()
items.sort(reverse=True)
```

Sort a list temporarily (returns a copy of the list, leaving original list unchanged)

```python
print(sorted(items))
print(sorted(items, reverse=True))
```
 
Find the length of a list (number of items)

```python
len(items)
```

Delete an item by its index

```python
del items[index]
```

Remove an item by its value (only removes first instance; use while loop to remove all instances)

```python
items.remove(item)
```

Pop the first item in a list

```python
items.pop(0)
```

Pop the last item from a list

```python
items.pop()
```

Example

```python
first_user = users.pop(0)
```

<!--
Python Crash Course

Popping elements
If you want to work with an element that you're removing from the list, you can "pop" the element. If you think of the list as a stack of items, pop() takes an item off the top of the stack. By default pop() returns the last element in the list, but you can also pop elements from any position in the list.
-->     

Copy

```python
items = new_list[:]
```

<!--
8.10. copy — Shallow and deep copy operations

Python Crash Course

Copying a list
"To copy a list make a slice that starts at the first item and ends at the last item. If you try to copy a list without using this approach, whatever you do to the copies list will affect the original list as well." 
-->

<!--
Subset

items2 = [[], []]

Subset Lists of Lists (items2[list][itemofList]
items2[0][0]
items2[0][0:]
-->

### Common Dictionary Methods (mutable, non-sequence, iterable)

Empty dictionary

```python
items = {}
```

Existing dictionary

```python
items = {key: value, key: value}
```

Add a key-value pair to a empty or existing dictionary

```python
items[key] = value
items[key] = value
```

Find a value in a dictionary using key

```python
items[key]
```

Find a value in a dictionary using get()

```python
items.get(key)
```

<!--
alien_0 = {'color': 'green'}

alien_points = alien_0.get('points', 0)
-->

Modify a value in a dictionary

```python
items[key] = new_value
```

Find the length of a dictionary (number of key-value pairs)

```python
len(items)
```

Delete a key-value pair

```python
del items[key]
```

Print the value associated with a key

```python
print(items[key])
```

### Set Operations

Remove duplicates by using a set

```python
a_list = [0, 0, 1, 1, 2, 2, 3, 3, 4, 4]
a_set = {0, 0, 1, 1, 2, 2, 3, 3, 4, 4}

>>> print(a_list)
[0, 0, 1, 1, 2, 2, 3, 3, 4, 4]
>>> print(a_set)
{0, 1, 2, 3, 4}
```

Convert list to set

```python
a_list = [0, 0, 1, 1, 2, 2, 3, 3, 4, 4]
a_set = set(a_list)

>>> print(a_set)
{0, 1, 2, 3, 4}
```

## String and List Concatenation and Operator Overloading

### String Concatenation

```python
first_name = 'Kati'
last_name = 'Michel'
full_name = first_name + ' ' + last_name
print(full_name)
Kati Michel
```

### Numbers as a Calculation

```python
>>> a_calculation = 992 + 345
>>> a_calculation
1337
```

### Numbers as a String

```python
>>> a_string = '992 + 345'
>>> a_string
'992 + 345'
```

### String Operator Overloading Examples

```python
>>> a_string = 'mystring'
>>> a_string
'mystring'
```

### String Addition (Characters)

```python
>>> a_string + 'isawesome'
'mystringisawesome'
```

### String Addition (Numbers)

```python
>>> '123' + '456'
'123456'
```

### String Multiplication (Characters)

```python
>>> a_string * 2
'mystringmystring'
```

### String Multiplication (Numbers)

```python
>>> '123' * 2
'123123'
```

### List Operator Overloading Example

```python
>>> first_word = 'my'
>>> a_list = [first_word, 'list', 'is', 'awesome']
>>> a_list
['my', 'list', 'is', 'awesome']
```

### List Addition

```python
>>> a_list + a_list
['my', 'list', 'is', 'awesome', 'my', 'list', 'is', 'awesome']
```

### List Multiplication

```python
>>> a_list * 2
['my', 'list', 'is', 'awesome', 'my', 'list', 'is', 'awesome']
```

## Simple Statistics (on numerical data)

Find the minimum value in a list

```python
ages = [1, 2, 3, 4]
youngest = min(ages)
```

Find the maximum value

```python
ages = [1, 2, 3, 4]
oldest = max(ages)
```

Find the sum of all values

```python
ages = [1, 2, 3, 4]
total_years = sum(ages)
```

Sequences

<!--
''.join(sequence)
-->


## Advanced Data Structures

<!--
https://twitter.com/raymondh/status/1025252216985346048 | Raymond Hettinger on Twitter: "#Python 3.8 news: We now have a Euclidean distance function in the math math module :-) https://t.co/nJZX0cfOcK Now, k-nearest neighbors boils down to: nsmallest(k, training_data, partial(dist, new_point))"
-->

### Heap Queue Algorithm

#### Heap Queue Algorithm- Priority Queue Implementation

### Timsort

<!--
https://twitter.com/raymondh/status/1013589736538042368
https://bugs.python.org/issue28685

https://en.wikipedia.org/wiki/Timsort | Timsort - Wikipedia
https://www.geeksforgeeks.org/timsort/ | TimSort - GeeksforGeeks
-->

<!--
operators
list sort, pop, copy
range() Function (for Statement)
reversed()
sorted()
sort()
sort(reverse=True)
sorted(items, reverse=True)

https://www.geeksforgeeks.org/sort-in-python/ | sort() in Python - GeeksforGeeks
https://www.geeksforgeeks.org/sort-sorteda-np-argsorta-np-lexsortb-python/ | a.sort(), sorted(a), np.argsort(a) and np.lexsort(b, a) in Python - GeeksforGeeks
-->

## Math

<!--
```Python
import math
math.pi
```

## Fibonacci series

9.2.1. Number-theoretic and representation functions
math.ceil(x)
math.copysign(x, y)
math.fabs(x)
math.factorial(x)
math.floor(x)
math.fmod(x, y)
math.frexp(x)
math.fsum(iterable)
math.gcd(a, b)
math.isclose(a, b, *, rel_tol=1e-09, abs_tol=0.0)
math.isfinite(x)
math.isinf(x)
math.isnan(x)
math.ldexp(x, i)
math.modf(x)
math.remainder(x, y)
math.trunc(x)

9.2.2. Power and logarithmic functions
math.exp(x)
math.expm1(x)
math.log(x[, base])
math.log1p(x)
math.log2(x)
math.log10(x)
math.pow(x, y)
math.sqrt(x)

9.2.3. Trigonometric functions
math.acos(x)
math.asin(x)
math.atan(x)
math.atan2(y, x)
math.cos(x)
math.hypot(x, y)
math.sin(x)
math.tan(x)

9.2.4. Angular conversion
math.degrees(x)
math.radians(x)

9.2.5. Hyperbolic functions
math.acosh(x)
math.asinh(x)
math.atanh(x)
math.cosh(x)
math.sinh(x)
math.tanh(x)

9.2.6. Special functions
math.erf(x)
math.erfc(x)
math.gamma(x)
math.lgamma(x)

9.2.7. Constants
math.pi
math.e
math.tau
math.inf
math.nan

9.7. statistics — Mathematical statistics functions

Source code: Lib/statistics.py

This module provides functions for calculating mathematical statistics of numeric (Real-valued) data.
Note Unless explicitly noted otherwise, these functions support int, float, decimal.Decimal and fractions.Fraction. Behaviour with other types (whether in the numeric tower or not) is currently unsupported. Mixed types are also undefined and implementation-dependent. If your input data consists of mixed types, you may be able to use map() to ensure a consistent result, e.g. map(float, input_data).

9.7.1. Averages and measures of central location
"These functions calculate an average or typical value from a population or sample."
mean()	Arithmetic mean (“average”) of data.
harmonic_mean()	Harmonic mean of data.
median()	Median (middle value) of data.
median_low()	Low median of data.
median_high()	High median of data.
median_grouped()	Median, or 50th percentile, of grouped data.
mode()	Mode (most common value) of discrete data.

9.7.2. Measures of spread
"These functions calculate a measure of how much the population or sample tends to deviate from the typical or average values."
pstdev()	Population standard deviation of data.
pvariance()	Population variance of data.
stdev()	Sample standard deviation of data.
variance()	Sample variance of data.

9.7.3. Function details
"Note: The functions do not require the data given to them to be sorted. However, for reading convenience, most of the examples show sorted sequences."
statistics.mean(data)
statistics.harmonic_mean(data)
statistics.median(data)
statistics.median_low(data)
statistics.median_high(data)
statistics.median_grouped(data, interval=1)
statistics.mode(data)
statistics.pstdev(data, mu=None)
statistics.pvariance(data, mu=None)
statistics.stdev(data, xbar=None)
statistics.variance(data, xbar=None)
-->

## Set Math

<!--
Sets 

powers_of_two  = { 1, 2, 4, 8, 16 }
fibonacci_set = { 1, 1, 2, 3, 5, 8, 13 }

# Union: Elements in either set (two ways, both do same thing)
print( powers_of_two.union( fibonacci_set ) )
print( powers_of_two | fibonacci_set )
{1, 2, 3, 4, 5, 8, 13, 16}
{1, 2, 3, 4, 5, 8, 13, 16}

# Intersection: Elements in both sets (two ways, both do same thing)
print( powers_of_two.intersection( fibonacci_set ) )
print( powers_of_two & fibonacci_set )
{8, 1, 2}
{8, 1, 2}

# Difference
print( powers_of_two )
print( fibonacci_set )
print( powers_of_two - fibonacci_set )
print( fibonacci_set - powers_of_two)
{1, 2, 4, 8, 16}
{1, 2, 3, 5, 8, 13}
{16, 4}
{13, 3, 5}
-->
