# Course Notes

## General Notes

<!--
HTMl and CSS
https://developer.mozilla.org/en-US/docs/Web/HTML/Element | HTML elements reference - HTML: Hypertext Markup Language | MDN
https://developer.mozilla.org/en-US/docs/Web/CSS | CSS: Cascading Style Sheets | MDN

https://twitter.com/unclebobmartin/status/1010660993851117569 | Uncle Bob Martin on Twitter: "Programs are made up of Dijkstra’s three structures: Sequence, Selection, and Iteration. Each of these is based upon jumps. Sequential statements jump from the end of the first to be beginning of the second."

https://www.python.org/dev/peps/pep-0008/#indentation | PEP 8 -- Style Guide for Python Code | Python.org

http://pythontutor.com/visualize.html#mode=edit | Visualize Python, Java, JavaScript, C, C++, Ruby code execution

https://en.wikipedia.org/wiki/Self-documenting_code | Self-documenting code - Wikipedia
https://en.wikipedia.org/wiki/Precondition | Precondition - Wikipedia
https://en.wikipedia.org/wiki/Postcondition | Postcondition - Wikipedia

https://en.wikipedia.org/wiki/Off-by-one_error | Off-by-one error - Wikipedia
https://en.wikipedia.org/wiki/Off-by-one_error#Fencepost_error | Off-by-one error - Wikipedia

https://en.wikipedia.org/wiki/Control_flow
https://docs.python.org/3/tutorial/controlflow.html | 4. More Control Flow Tools — Python 3.8.2 documentation
https://en.wikipedia.org/wiki/Conditional_(computer_programming) | Conditional (computer programming) - Wikipedia
https://en.wikipedia.org/wiki/Conditional_(computer_programming)#If%E2%80%93then(%E2%80%93else) | Conditional (computer programming) - Wikipedia
https://docs.python.org/3/reference/compound_stmts.html#the-while-statement | 8. Compound statements — Python 3.8.2 documentation

https://docs.python.org/3/library/functions.html | Built-in Functions — Python 3.8.3 documentation
https://docs.python.org/3.8/library/functions.html#func-range | Built-in Functions — Python 3.8.2 documentation

https://docs.python.org/3.9/library/random.html | random — Generate pseudo-random numbers — Python 3.9.0a5 documentation
https://docs.python.org/3/library/math.html | math — Mathematical functions — Python 3.8.2 documentation
https://docs.python.org/3/library/fileformats.html | File Formats — Python 3.8.3 documentation

https://en.wikipedia.org/wiki/Increment_and_decrement_operators

https://codeinplace2020.github.io/faqs/7-Functions.pdf | 7-Functions

https://en.wikipedia.org/wiki/Decomposition | Decomposition - Wikipedia

https://en.wikipedia.org/wiki/Random-access_memory | Random-access memory - Wikipedia
https://en.wikipedia.org/wiki/Scope_(computer_science) | Scope (computer science) - Wikipedia
https://en.wikipedia.org/wiki/Concatenation | Concatenation - Wikipedia
https://en.wikipedia.org/wiki/Snake_case | Snake case - Wikipedia

https://developer.mozilla.org/en-US/docs/Glossary/Parameter | Parameter - MDN Web Docs Glossary: Definitions of Web-related terms | MDN
  
https://en.wikipedia.org/wiki/George_Boole#Death | George Boole - Wikipedia
https://en.wikipedia.org/wiki/Pseudorandomness | Pseudorandomness - Wikipedia

https://docs.python.org/3.8/library/types.html | types — Dynamic type creation and names for built-in types — Python 3.8.3 documentation
https://docs.python.org/3/library/constants.html#None | Built-in Constants — Python 3.8.3 documentation

https://docs.python.org/3/library/exceptions.html#TypeError | Built-in Exceptions — Python 3.8.3 documentation
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypeError | TypeError - JavaScript | MDN
https://docs.python.org/3/library/exceptions.html#NameError | Built-in Exceptions — Python 3.8.3 documentation
https://docs.python.org/3/library/exceptions.html#ValueError | Built-in Exceptions — Python 3.8.3 documentation
https://eli.thegreenplace.net/2011/05/15/understanding-unboundlocalerror-in-python/ | Understanding UnboundLocalError in Python - Eli Bendersky's website

https://en.wikipedia.org/wiki/Call_stack | Call stack - Wikipedia
frame object - Google Search
https://docs.python.org/3/library/inspect.html#the-interpreter-stack

https://stackoverflow.com/questions/373419/whats-the-difference-between-passing-by-reference-vs-passing-by-value | language agnostic - What's the difference between passing by reference vs. passing by value? - Stack Overflow

negative indexes python - Google Search

https://docs.python.org/3/library/pathlib.html | pathlib — Object-oriented filesystem paths — Python 3.8.3 documentation
-->

## Twilio

<!--
Twilio
https://www.twilio.com/ | Twilio - Communication APIs for SMS, Voice, Video and Authentication
https://www.twilio.com/docs/api | API Reference - In-Depth Reference for all Twilio APIs and SDKs - Twilio
https://www.twilio.com/docs/quickstart | Quickstart - Guides for Voice, SMS, Video, Chat, Notifications, and More - Twilio
-->

## Automate the Boring Stuff with Python

https://automatetheboringstuff.com/ | Automate the Boring Stuff with Python

Valid variable names
https://automatetheboringstuff.com/2e/chapter1/
https://docs.python.org/3/library/exceptions.html#TypeError
Boolean values
True/False matrix
Boolean operators
Table 2-2: The and Operator’s Truth Tabl
Table 2-3: The or Operator’s Truth Table
Table 2-4: The not Operator’s Truth Table
Break statement (while loop)
https://automatetheboringstuff.com/2e/chapter2/
Infinite loop
continue statement (same thing that happens when execution reaches end of the loop)
while True
Truthy and falsy values
An Equivalent while Loop
https://autbor.com/fivetimeswhile/

```bash
print('My name is')
i = 0
while i < 5:
    print('Jimmy Five Times (' + str(i) + ')')
    i = i + 1
```

range loop -1
Optionally, more module names, as long as they are separated by commas
Don't overwrite module names
from import Statements
sys.exit()
A Short Program: Rock, Paper, Scissors

https://automatetheboringstuff.com/2e/chapter3/
deduplication
parameter versus argument
"that the value stored in a parameter is forgotten when the function returns."
https://docs.python.org/3/library/exceptions.html#NameError
global and local scope
Define, Call, Pass, Argument, Parameter
Return Values and return Statements
Magic eight ball program
The None Value
https://docs.python.org/3/library/constants.html#None
(Other programming languages might call this value null, nil, or undefined.) 
keyword arguments, optional parameters
end''
end and sep
the print() function automatically adds a newline character to the end of the string it is passed
multiple string values to print()
you could replace the default separating string by passing the sep keyword
The Call Stack
Call stack explanation
Local and Global Scope
local variable, global variable
"There is only one global scope, and it is created when your program begins. When your program terminates, the global scope is destroyed, and all its variables are forgotten."
"A local scope is created whenever a function is called. Any variables assigned in the function exist within the function’s local scope. When the function returns, the local scope is destroyed, and these variables are forgotten. The next time you call the function, the local variables will not remember the values stored in them from the last time the function was called. Local variables are also stored in frame objects on the call stack."
Global statement
try except statement
zig-zag program
time.sleep()
https://docs.python.org/3/library/exceptions.html#KeyboardInterrupt
https://docs.python.org/3/tutorial/errors.html#handling-exceptions
https://docs.python.org/3/library/exceptions.html#ValueError
https://docs.python.org/3/library/exceptions.html#UnboundLocalError
https://automatetheboringstuff.com/2e/chapter4/
https://docs.python.org/3/library/exceptions.html#IndexError
negative indexes
list methods
using a for loop with lists
(Sequences are described in “Sequence Data Types” on page 93.)
A common Python technique is to use range(len(someList)) with a for loop to iterate over the indexes of a list. 
"Using range(len(supplies)) in the previously shown for loop is handy because the code in the loop can access the index (as the variable i) and the value at that index (as supplies[i])."
in and not in
The Multiple Assignment Trick
The multiple assignment trick (technically called tuple unpacking)
ValueError
"Instead of using the range(len(someList)) technique with a for loop to obtain the integer index of the items in the list, you can call the enumerate() function instead. The enumerate() function is useful if you need both the item and the item’s index in the loop’s block."
Using the random.choice() and random.shuffle() Functions with Lists
"You can consider random.choice(someList) to be a shorter form of someList[random.randint(0, len(someList) – 1]."
Augmented Assignment Operators
The += operator can also do string and list concatenation, and the *= operator can do string and list replication.
List methods
Exceptions to indentation rules in Python
You can also split up a single instruction across multiple lines using the \ line continuation character at the end. 
Magic 8 ball redux
messages: random.randint (0, len(messages)
Sequence Data Types
Mutable and Immutable Data Types
tuple data type
trailing comma
Identity and the id() Function
Passing References
References are particularly important for understanding how arguments get passed to functions. When a function is called, the values of the arguments are copied to the parameter variables. For lists (and dictionaries, which I’ll describe in the next chapter), this means a copy of the reference is used for the parameter. 
copy() and deepcopy()
A Short Program: Conway’s Game of Life
Conway’s Game of Life is an example of cellular automata:
"Variables do not store list values directly; they store references to lists. This is an important distinction when you are copying variables or passing lists as arguments in function calls. Because the value that is being copied is the list reference, be aware that any changes you make to the list might impact another variable in your program."
https://automatetheboringstuff.com/2e/chapter5/
dictionary data type
key-value pair
Dictionaries can still use integer values as keys, just like lists use integers for indexes, but they do not have to start at 0 and can be any number.
Unlike lists, items in dictionaries are unordered. 
Birthdays program
Ordered dictionaries in Python 3.7
The keys(), values(), and items() Methods
But these data types (dict_keys, dict_values, and dict_items, respectively) can be used in for loops. 
"Notice that the values in the dict_items value returned by the items() method are tuples of the key and value.
If you want a true list from one of these methods, pass its list-like return value to the list() function. "
You can also use the multiple assignment trick in a for loop to assign the key and value to separate variables. 
Dictionary methods
Pretty printing: pprint() and pformat() functions
The pprint.pprint() function is especially helpful when the dictionary itself contains nested lists or dictionaries.
pprint.pprint(someDictionaryValue)
print(pprint.pformat(someDictionaryValue))
Algebraic chess notation
Tic tac toe board
https://nostarch.com/automatestuff2/
Nested Dictionaries and Lists
https://automatetheboringstuff.com/2e/chapter6/
escape characters
raw strings
Multiline Strings with Triple Quotes
Multiline Comments
string methods
in and out operator
Putting strings inside strings
The isX() Method (interesting)
The join() and split() Methods
Splitting Strings with the partition() Method
Removing Whitespace with the strip(), rstrip(), and lstrip() Methods
Numeric Values of Characters with the ord() and chr() Functions
Unicode code point
These functions are useful when you need to do an ordering or mathematical operation on characters:
"There is more to Unicode and code points, but those details are beyond the scope of this book. If you’d like to know more, I recommend watching Ned Batchelder’s 2012 PyCon talk, “Pragmatic Unicode, or, How Do I Stop the Pain?” at https://youtu.be/sgHbC6udIqc."
Turn to Appendix B to learn how to run your Python scripts conveniently and be able to pass command line arguments to them. 
Copying and Pasting Strings with the pyperclip Module
The pyperclip module has copy() and paste() functions that can send text to and receive text from your computer’s clipboard. 
Project: Multi-Clipboard Automatic Messages
Project: Adding Bullets to Wiki Markup
A Short Progam: Pig Latin
Another way to manipulate large amounts of text is reading and writing files directly off the hard drive. You’ll learn how to do this with Python in Chapter 9.
https://github.com/asweigart/pythonstdiogames/
https://automatetheboringstuff.com/2e/chapter7/
Regex
I’ll show you basic matching with regular expressions and then move on to some more powerful features, such as string substitution and creating your own character classes. 
Regex object
Passing a string value representing your regular expression to re.compile() returns a Regex pattern object (or simply, a Regex object)
Matching Multiple Groups with the Pipe
Character classes (important!)
Making your own character classes
The Caret and Dollar Sign Characters
The Wildcard Character
Matching Everything with Dot-Star
Matching Newlines with the Dot Character
Review of Regex Symbols
Case-Insensitive Matching
Substituting Strings with the sub() Method
Managing Complex Regexes
Combining re.IGNORECASE, re.DOTALL, and re.VERBOSE
Project: Phone Number and Email Address Extractor
Ideas for Similar Programs
https://www.regular-expressions.info/
https://pythex.org/
https://pypi.org/project/PyInputPlus/
Project: How to Keep an Idiot Busy for Hours
Project: Multiplication Quiz

https://automatetheboringstuff.com/2e/chapter9/
You can think of a file’s contents as a single string value, potentially gigabytes in size. 
A file has two key properties: a filename (usually written as one word) and a path. 
root folder
On macOS and Linux, the root folder is /. 
On macOS, they appear as new folders under the /Volumes folder. 
The macOS and Linux operating systems, however, use the forward slash (/) as their path separator. If you want your programs to work on all operating systems, you will have to write your Python scripts to handle both cases.
Fortunately, this is simple to do with the Path() function in the pathlib module. If you pass it the string values of individual file and folder names in your path, Path() will return a string with a file path using the correct path separators. 
https://docs.python.org/3/library/pathlib.html
Note that the convention for importing pathlib is to run from pathlib import Path, since otherwise we’d have to enter pathlib.Path everywhere Path shows up in our code. Not only is this extra typing redundant, but it’s also redundant.
If you want to get a simple text string of this path, you can pass it to the str() function, which in our example returns 'spam\\bacon\\eggs'. 
(POSIX is a set of standards for Unix-like operating systems such as Linux.)
These Path objects (really, WindowsPath or PosixPath objects, depending on your operating system) will be passed to several of the file-related functions introduced in this chapter. For example, the following code joins names from a list of filenames to the end of a folder’s name:
However, you can use backslashes in filenames on macOS and Linux. 
the same command would refer to a single folder (or file) named spam\eggs on macOS and Linux. For this reason, it’s usually a good idea to always use forward slashes in your Python code 
Using the / Operator to Join Paths
Using the / operator with Path objects makes joining paths just as easy as string concatenation. It’s also safer than using string concatenation or the join() method, like we do in this example:
The pathlib module solves these problems by reusing the / math division operator to join paths correctly, no matter what operating system your code is running on. 
The only thing you need to keep in mind when using the / operator for joining paths is that one of the first two values must be a Path object. 
Diagram
current working directory, or cwd. Any filenames or paths that do not begin with the root folder are assumed to be under the current working directory.
You can get the current working directory as a string value with the Path.cwd() function and change it using os.chdir(). 
You can get a Path object of the home folder by calling Path.home():
On Mac, home directories are under /Users.
Absolute vs. Relative Paths
A single period (“dot”) for a folder name is shorthand for “this directory.” Two periods (“dot-dot”) means “the parent folder.”
Creating New Folders Using the os.makedirs() Function
To make a directory from a Path object, call the mkdir() method. 
Note that mkdir() can only make one directory at a time; it won’t make several subdirectories at once like os.makedirs().
Handling Absolute and Relative Paths
Calling the is_absolute() method on a Path object will return True if it represents an absolute path or False if it represents a relative path. 
To get an absolute path from a relative path, you can put Path.cwd() / in front of the relative Path object. 
If your relative path is relative to another path besides the current working directory, just replace Path.cwd() with that other path instead. 
os.path.abspath(path)
os.path.isabs(path)
os.path.relpath(path, start)
os.path.relpath()
Getting the Parts of a File Path
Diagram
os.path.dirname(path)
os.path.basename(path)
os.path.split()
os.path.dirname() and os.path.basename()
os.sep. (Note that sep is in os, not os.path.)
Finding File Sizes and Folder Contents
os.path.getsize(path)
os.listdir(path)
os.path.getsize()
os.path.join()
Modifying a List of Files Using Glob Patterns
If you want to work on specific files, the glob() method is simpler to use than listdir(). Path objects have a glob() method for listing the contents of a folder according to a glob pattern. Glob patterns are like a simplified form of regular expressions often used in command line commands. The glob() method returns a generator object (which are beyond the scope of this book) that you’ll need to pass to list() to easily view in the interactive shell:
The asterisk (*) stands for “multiple of any characters,” so p.glob('*') returns a generator of all files in the path stored in p. Like with regexes, you can create complex expressions:
The glob pattern '*.txt' will return files that start with any combination of characters as long as it ends with the string '.txt', which is the text file extension.
In contrast with the asterisk, the question mark (?) stands for any single character:
Finally, you can also combine the asterisk and question mark to create even more complex glob expressions, like this:
The glob expression '*.?x?' will return files with any name and any three-character extension where the middle character is an 'x'.
By picking out files with specific attributes, the glob() method lets you easily specify the files in a directory you want to perform some operation on. You can use a for loop to iterate over the generator that glob() returns:
If you want to perform some operation on every file in a directory, you can use either os.listdir(p) or p.glob('*').
Checking Path Validity
p.exists()
p.is_file()
p.is_dir()
The File Reading/Writing Process
plaintext files
Binary files are all other file types
If you open a binary file in Notepad or TextEdit, it will look like scrambled nonsense, like in Figure 9-6.
The pathlib module’s read_text() method returns a string of the full contents of a text file. Its write_text() method creates a new text file (or overwrites an existing one) with the string passed to it.
Call the open() function to return a File object.
Call the read() or write() method on the File object.
Close the file by calling the close() method on the File object.
Opening Files with the open() Function
Both these commands will open the file in “reading plaintext” mode, or read mode for short. 
But if you don’t want to rely on Python’s defaults, you can explicitly specify the mode by passing the string value 'r' as a second argument to open(). So open('/Users/Al/hello.txt', 'r') and open('/Users/Al/hello.txt') do the same thing.
Reading the Contents of Files
If you think of the contents of a file as a single large string value, the read() method returns the string that is stored in the file.
Alternatively, you can use the readlines() method to get a list of string values from the file, one string for each line of text. 
Writing to Files
Python allows you to write content to a file in a way similar to how the print() function “writes” strings to the screen. You can’t write to a file you’ve opened in read mode, though. Instead, you need to open it in “write plaintext” mode or “append plaintext” mode, or write mode and append mode for short.
Write mode will overwrite the existing file and start from scratch, just like when you overwrite a variable’s value with a new value. Pass 'w' as the second argument to open() to open the file in write mode. Append mode, on the other hand, will append text to the end of the existing file. 
Pass 'a' as the second argument to open() to open the file in append mode.
If the filename passed to open() does not exist, both write and append mode will create a new, blank file. 
After reading or writing a file, call the close() method before opening the file again.
Saving Variables with the shelve Module
shelve.open()
On macOS, only a single mydata.db file will be created.
Saving Variables with the pprint.pformat() Function
pprint.pformat()
The benefit of creating a .py file (as opposed to saving variables with the shelve module) is that because it is a text file, the contents of the file can be read and modified by anyone with a simple text editor. For most applications, however, saving data using the shelve module is the preferred way to save variables to a file. Only basic data types such as integers, floats, strings, lists, and dictionaries can be written to a file as simple text. File objects, for example, cannot be encoded as text.
Project: Generating Random Quiz Files
Project: Updatable Multi-Clipboard
Summary
https://automatetheboringstuff.com/2e/chapter10/
Making copies of all PDF files (and only the PDF files) in every subfolder of a folder
Removing the leading zeros in the filenames for every file in a folder of hundreds of files named spam001.txt, spam002.txt, spam003.txt, and so on
Compressing the contents of several folders into one ZIP file (which could be a simple backup system)
The shutil Module
The shutil (or shell utilities) module has functions to let you copy, move, rename, and delete files in your Python programs.
Copying Files and Folders
shutil.copy()
shutil.copytree()
shutil.copytree(source, destination)
Moving and Renaming Files and Folders
Calling shutil.move(source, destination) will move the file or folder at the path source to the path destination and will return a string of the absolute path of the new location.
shutil.move()
move()
Permanently Deleting Files and Folders
os.rmdir(path) 
shutil.rmtree(path)
os.unlink()
os.unlink(filename)
Safe Deletes with the send2trash Module
Walking a Directory Tree
os.walk()
similar to range()
Compressing Files with the zipfile Module
Reading ZIP Files
Extracting from ZIP Files
Creating and Adding to ZIP Files
Project: Renaming Files with American-Style Dates to European-Style Dates
Project: Backing Up a Folder into a ZIP File
os and shutil modules
send2trash module
print() call
os.walk()
zipfile module

https://automatetheboringstuff.com/2e/chapter11/
Raising Exceptions
try, except, raise
A call to the Exception() function
If there are no try and except statements covering the raise statement that raised the exception, the program simply crashes and displays the exception’s error message.
Often it’s the code that calls the function, rather than the function itself, that knows how to handle an exception. That means you will commonly see a raise statement inside a function and the try and except statements in the code calling the function. 
Getting the Traceback as a String
This sequence of calls is called the call stack.
Python displays the traceback whenever a raised exception goes unhandled. But you can also obtain it as a string by calling traceback.format_exc(). This function is useful if you want the information from an exception’s traceback but also want an except statement to gracefully handle the exception. You will need to import Python’s traceback module before calling this function. For example, instead of crashing your program right when an exception occurs, you can write the traceback information to a text file and keep your program running. You can look at the text file later, when you’re ready to debug your program. 

>>> import traceback
>>> try:
...          raise Exception('This is the error message.')
except:
...          errorFile = open('errorInfo.txt', 'w')
...          errorFile.write(traceback.format_exc())
...          errorFile.close()
...          print('The traceback info was written to errorInfo.txt.')

In “Logging” on page 255, you’ll learn how to use the logging module, which is more effective than simply writing this error information to text files.

Assertions
sanity checks
The assert keyword
A condition (that is, an expression that evaluates to True or False)
A comma
A string to display when the condition is False
In plain English, an assert statement says, “I assert that the condition holds true, and if not, there is a bug somewhere, so immediately stop the program.” 

reverse() list method instead of the sort() list method
“failing fast”
Assertions are for programmer errors, not user errors. Assertions should only fail while the program is under development; a user should never see an assertion error in a finished program. For errors that your program can run into as a normal part of its operation (such as a file not being found or the user entering invalid data), raise an exception instead of detecting it with an assert statement. You shouldn’t use assert statements in place of raising exceptions, because users can choose to turn off assertions. If you run a Python script with python -O myscript.py instead of python myscript.py, Python will skip assert statements. Users might disable assertions when they’re developing a program and need to run it in a production setting that requires peak performance. (Though, in many cases, they’ll leave assertions enabled even then.)
Using an Assertion in a Traffic Light Simulation
Logging
logging module
import logging
logging.basicConfig(level=logging.DEBUG, format=' %(asctime)s -  %(levelname)
s -  %(message)s')
How it works
logging.debug() function
This debug() function will call basicConfig(), and a line of information will be printed. This information will be in the format we specified in basicConfig() and will include the messages we passed to debug(). 
Don’t Debug with the print() Function
you can always disable them later by adding a single logging.disable(logging.CRITICAL) call. Unlike print(), the logging module makes it easy to switch between showing and hiding log messages.
Log messages are intended for the programmer, not the user. 
Logging Levels
The benefit of logging levels is that you can change what priority of logging message you want to see. Passing logging.DEBUG to the basicConfig() function’s level keyword argument will show messages from all the logging levels (DEBUG being the lowest level). But after developing your program some more, you may be interested only in errors. In that case, you can set basicConfig()’s level argument to logging.ERROR. This will show only ERROR and CRITICAL messages and skip the DEBUG, INFO, and WARNING messages.
Disabling Logging
logging.disable()
Logging to a File
import logging
logging.basicConfig(filename='myProgramLog.txt', level=logging.DEBUG, format='
%(asctime)s -  %(levelname)s -  %(message)s')
Mu debugger

## CPython Internals Book

<!--
https://www.youtube.com/watch?time_continue=1&v=3hl39VMd0f0&feature=emb_logo | What's inside my new Python book - YouTube

https://docs.python.org/3/library/python.html
https://docs.python.org/3/reference/grammar.html

https://docs.python.org/3/library/dis.html | 404 Not Found

https://en.wikipedia.org/wiki/Bootstrapping_(compilers) | Bootstrapping (compilers) - Wikipedia
https://en.wikipedia.org/wiki/Self-hosting_(compilers) | Self-hosting (compilers) - Wikipedia
https://en.wikipedia.org/wiki/Source-to-source_compiler | Source-to-source compiler - Wikipedia
https://github.com/lark-parser/lark
C System API
https://docs.python.org/3.8/extending/extending.html

https://realpython.com/python-sockets/ | Socket Programming in Python (Guide) – Real Python
https://realpython.com/working-with-files-in-python/ | Working With Files in Python – Real Python
https://realpython.com/python-gui-with-wxpython/ | How to Build a Python GUI Application With wxPython – Real Python
https://www.pypy.org/ | PyPy
-->

## Dave

<!--
https://github.com/KatherineMichel/practical-python
https://dabeaz-course.github.io/practical-python/Notes/00_Setup.html
https://dabeaz-course.github.io/practical-python/Notes/01_Introduction/03_Numbers.html

https://docs.python.org/3.8/library/xml.etree.elementtree.html#xml.etree.ElementTree.Element.findall | xml.etree.ElementTree — The ElementTree XML API — Python 3.8.3 documentation
https://docs.python.org/3/library/fractions.html | fractions — Rational numbers — Python 3.8.3 documentation
-->

## JavaScript 30

<!--
https://github.com/wesbos/JavaScript30

https://www.w3schools.com/jsref/met_document_queryselector.asp | HTML DOM querySelector() Method
https://developer.mozilla.org/en-US/docs/Web/API/Element/classList | Element.classList - Web APIs | MDN
https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/currentTime | HTMLMediaElement.currentTime - Web APIs | MDN

https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties | Using CSS custom properties (variables) - CSS: Cascading Style Sheets | MDN

arrow function
https://medium.com/javascript-scene/familiarity-bias-is-holding-you-back-its-time-to-embrace-arrow-functions-3d37e1a9bb75 | Familiarity Bias is Holding You Back: It’s Time to Embrace Arrow Functions

https://developer.mozilla.org/en-US/docs/Web/API/MessageEvent | MessageEvent - Web APIs | MDN

Project 1
https://developer.mozilla.org/en-US/docs/Web/API/UIEvent | UIEvent - Web APIs | MDN
https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent | KeyboardEvent - Web APIs | MDN
https://developer.mozilla.org/en-US/docs/Web/API/Document/keydown_event | Document: keydown event - Web APIs | MDN
https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement | HTMLMediaElement - Web APIs | MDN
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio | <audio>: The Embed Audio element - HTML: Hypertext Markup Language | MDN
https://wiki.mozilla.org/Audio_Data_API | Audio Data API - MozillaWiki

https://www.w3schools.com/jsref/event_onkeydown.asp | onkeydown Event

Not used
https://developer.mozilla.org/en-US/docs/Web/API/HTMLOrForeignElement/dataset | HTMLOrForeignElement.dataset - Web APIs | MDN
-->

## Stanford Code in Place

<!--
https://twitter.com/search?q=stanford%20code%20in%20place&src=typed_query&f=live | stanford code in place - Twitter Search / Twitter

https://compedu.stanford.edu/codeinplace/diagnostic/ae76ma.pdf | ae76ma.pdf
https://us.edstem.org/courses/490/discussion/49678 | Code in Place – Discussion
https://us.edstem.org/courses/490/discussion/47208 | Code in Place – Discussion

https://compedu.stanford.edu/codeinplace/v1/#/handout/submissionA2.html | Handout
https://us.edstem.org/courses/490/lessons/1198/slides/5976 | Code in Place – Lessons
https://us.edstem.org/courses/490/lessons/1236/slides/6431 | Code in Place – Lessons
https://us.edstem.org/courses/490/lessons/1135/slides/5433 | Code in Place – Lessons


Karel
https://www.jetbrains.com/help/pycharm/github.html | GitHub - Help | PyCharm
https://karelhelper.com/ | Karel Helper
http://stanford.edu/~cpiech/karel/lessons.html#/english/unit8/lesson5 | Learn to Program

Stanford
https://compedu.stanford.edu/codeinplace/v1/#/admitted | Admitted Student
https://compedu.stanford.edu/karel-reader/docs/python/en/ide.html | Karel Reader
https://compedu.stanford.edu/karel-reader/docs/python/en/reference.html | Karel Reader
https://compedu.stanford.edu/karel-reader/docs/python/en/chapter9.html | Karel Reader
https://compedu.stanford.edu/karel-reader/docs/python/en/chapter8.html | Karel Reader

Code in Place
https://compedu.stanford.edu/codeinplace/v1/#/assignment/karel | Assignment
https://compedu.stanford.edu/codeinplace/v1/#/handout/karelInPycharm.pdf | Handout
https://compedu.stanford.edu/codeinplace/v1/#/karel/section1/arches | Code in Place Application
https://compedu.stanford.edu/codeinplace/assn0/#/exercises/warmup | Assn0

http://stanford.edu/~cpiech/karel/lessons.html#/english/unit9/lesson1 | Learn to Program

https://us.edstem.org/courses/490/discussion/27750 | Code in Place – Discussion
https://us.edstem.org/courses/490/discussion/28037 | Code in Place – Discussion
https://us.edstem.org/courses/490/discussion/33978 | Code in Place – Discussion
https://us.edstem.org/courses/490/discussion/33861 | Matt posted an announcement Zoom Meeting Invitation
https://us.edstem.org/courses/1470/discussion/30564 | Section 470 – Discussion
https://us.edstem.org/courses/1470/discussion/34173 | Section 470 – Discussion


https://us.edstem.org/courses/490/discussion/78319 | Code in Place – Discussion
https://us.edstem.org/courses/490/discussion/71966 | Code in Place – Discussion

https://www.youtube.com/watch?time_continue=178&v=U5KT89HJIw4&feature=emb_logo | (2) Goodbye Code in Place - YouTube
https://us.edstem.org/courses/1470/discussion/ | Section 470 – Discussion

https://twitter.com/KatiMichel/status/1276539905535959041 | Katherine Michel on Twitter: "Thanks again to @chrispiech and Mehran Sahami for a wonderful Stanford Code in Place experience. I wrote a post about what the experience was like for me and some of my thoughts about it! https://t.co/W9qTI2SLuw" / Twitter

https://dl.acm.org/doi/pdf/10.1145/3051457.3053985 | Deep Knowledge Tracing On Programming Exercises

http://karel.sourceforge.net/ | Karel The Robot

tikinter pong game - Google Search


https://twitter.com/chrispiech/status/1244692768431038473 | chrispiech on Twitter: "Mehran Sahami and I are going to host a community-service online coding course called Code in Place alongside CS106A. Led by a army of volunteer teachers. We are keeping a teacher to student ratio of 10:1. Calling for volunteers and students! Please share: https://t.co/y6QAkshwTA https://t.co/s92Z4MBjf5" / Twitter

Introductory video
https://twitter.com/KatiMichel/status/1249787619342336000

https://twitter.com/KatiMichel/status/1250932687780450305 | Katherine Michel on Twitter: "Just finished solving the assignment problems for Stanford's Code in 
Place course. Fun but challenging. It took some hours and I had a few light bulb moments. I thought I was done at one point, but my answer didn't pass all the test cases. 🤣 Will solve the bonus material now. 👩‍💻" / Twitter

Midpoint message
https://twitter.com/KatiMichel/status/1256097561024163840

https://twitter.com/KatiMichel/status/1259262140394827778 | Katherine Michel on Twitter: "In the running for coolest thing I've learned this week is how to use Python to replace a green background in a photo with the background of a different photo (greenscreening) via Stanford Code in Place. 💚" / Twitter
https://twitter.com/KatiMichel/status/1263737007324332032 | Katherine Michel on Twitter: "Sitting here stunned at what I just did with @GitHub Actions for my Stanford Code in Place final project. Succeeded at something I didn't even know could be done. 🤯" / Twitter

"Negative" image tweet
https://twitter.com/KatiMichel/status/1264308702594527238
https://twitter.com/KatiMichel/status/1264702476797673472

My [first programmatic tweet of text](https://twitter.com/SimbaFriendsBot/status/1263318557380706305)
My [first programmatic tweet of text and an image](https://twitter.com/SimbaFriendsBot/status/1263365130760273920). 
-->

### Final Project

<!--
https://twitter.com/chrispiech/status/1268934076381007872 | chrispiech on Twitter: "When I was a child in Kenya, I lost my vision (first one eye, then the other). Just before losing vision in the second eye I met a doctor in Kenyatta Hospital who had dedicated his life to others. He helped me regain my vision -- it required a scary injection..." / Twitter

Stanford Reflections
https://www.stanforddaily.com/2020/06/08/code-in-place-makes-cs-accessible-to-thousands-worldwide/ | Code in Place makes CS accessible to thousands worldwide - The Stanford Daily
https://twitter.com/faridaelchuzade/status/1266107357496578050 | Farida Elchuzade on Twitter: "We have come to the end of 'Code in Place' Program organized by great professors and leaders of Stanford University. I made a sketch-note to summarize the topics I learned during the 5-week program. Let me know your thoughts about the note😊 #codeinplace #sketchandcode https://t.co/94bbbijduq" / Twitter
https://www.linkedin.com/in/sanjay-mirchandani-54bb212/ | (86) Sanjay Mirchandani | LinkedIn

Simba
https://us.edstem.org/courses/490/lessons/1236/slides/6413 | Code in Place – Lessons

https://compedu.stanford.edu/codeinplace/public/projectlist.html | Project List
https://www.facebook.com/katherine.michel.5/posts/3283829794969992?comment_id=3285660654786906&notif_id=1591753826009940&notif_t=feed_comment | The final projects students created for the... - Katherine Michel

Final project
https://compedu.stanford.edu/codeinplace/v1/#/assignment/finalProject | Assignment
https://us.edstem.org/courses/490/discussion/69666 | Code in Place – Discussion
https://us.edstem.org/courses/490/discussion/67446 | Code in Place – Discussion

Mark's project
https://us.edstem.org/courses/490/discussion/69604 | Code in Place – Discussion
https://static.us.edusercontent.com/files/N85hJ2IHRnSfFI4iHjknP5hW

My project
https://us.edstem.org/courses/490/lessons/1327/slides/7012 | Code in Place – Lessons
https://us.edstem.org/courses/1470/discussion/67793?comment=197647 | Section 470 – Discussion

https://twitter.com/KatiMichel/status/1263737007324332032 | Katherine Michel on Twitter: "Sitting here stunned at what I just did with @GitHub Actions for my Stanford Code in Place final project. Succeeded at something I didn't even know could be done. 🤯" / Twitter
https://twitter.com/KatiMichel/status/1264308702594527238 | Katherine Michel on Twitter: "Beautiful "negative" image tweeted by @SimbaFriendsBot, my Stanford Code in Place final project, inspired by @chrispiech's dog. My Python script that powers it is run solely via @GitHub Actions, downloading, modifying, and tweeting an image within GitHub. https://t.co/RjlFu8HxYp" / Twitter
https://www.facebook.com/katherine.michel.5/posts/3238560776163561?comment_id=3239852896034349&notif_id=1590320706494522&notif_t=feed_comment | In April, I posted that I would be taking part... - Katherine Michel

https://en.wikipedia.org/wiki/Proof_of_concept | Proof of concept - Wikipedia

https://developer.twitter.com/en/apps/17971730 | Twitter Developers
https://mail.google.com/mail/u/3/?ogbl#inbox | Inbox (2) - simbaandfriendsbot@gmail.com - Gmail
https://twitter.com/SimbaFriendsBot | Katherine Michel (@SimbaFriendsBot) / Twitter
https://twitter.com/SimbaFriendsBot/status/1263318557380706305 | Katherine Michel on Twitter: "Hello world!" / Twitter
https://twitter.com/SimbaFriendsBot/status/1263365130760273920 | Katherine Michel on Twitter: "Checkout this cool image! https://t.co/H74aEcH4zp" / Twitter
https://twitter.com/SimbaFriendsBot/status/1264297922092503043 | Katherine Michel on Twitter: "https://t.co/hJjPthlIlo" / Twitter
https://twitter.com/SimbaFriendsBot/status/1264291085335101440 | Katherine Michel on Twitter: "https://t.co/rOyk6NSZxP" / 
Twitter

https://help.twitter.com/en/rules-and-policies/twitter-automation | Automation rules
https://unsplash.com/license | License | Unsplash

https://source.unsplash.com/collection/
https://source.unsplash.com/ | Unsplash Source | A Simple API for Embedding Free Photos from Unsplash
https://unsplash.com/documentation#get-a-random-photo | Unsplash API Documentation | Free HD Photo API | Unsplash

Python
https://docs.python.org/3/library/urllib.request.html | urllib.request — Extensible library for opening URLs — Python 3.8.3 documentation
https://docs.python.org/3/howto/urllib2.html | HOWTO Fetch Internet Resources Using The urllib Package — Python 3.8.3 documentation
https://docs.python.org/2/library/urllib.html#urllib.urlretrieve | 20.5. urllib — Open arbitrary resources by URL — Python 2.7.18 documentation
https://docs.python.org/3/library/urllib.parse.html | urllib.parse — Parse URLs into components — Python 3.8.3 documentation
-->

### Images

https://compedu.stanford.edu/codeinplace/v1/#/assignment/images | Assignment
https://codeinplace2020.github.io/faqs/imageReference.pdf | Microsoft Word - Image Reference.docx
https://web.stanford.edu/class/archive/cs/cs106a/cs106a.1202/handouts/reference-image.html
https://web.stanford.edu/class/archive/cs/cs106ap/cs106ap.1198/handouts/h10_Image_Reference_Guide.pdf | h10_Image_Reference_Guide.pdf

### Further Learning

Stanford
Post-Class Resources
https://us.edstem.org/courses/490/discussion/71967 | Code in Place – Discussion
Life after Code in Place
https://us.edstem.org/courses/490/discussion/71966 | Code in Place – Discussion

Additional Resources that I Gave to My Section (Life After Code in Place)
https://us.edstem.org/courses/490/discussion/74252 | Code in Place – Discussion

Stanford Engineering Anywhere
https://see.stanford.edu/Course#Introduction%20to%20Computer%20Science

Stanford
https://see.stanford.edu/Course/CS106B/153 | Stanford Engineering Everywhere | CS106B - Programming Abstractions | Lecture 2 - Similarity between C++ & Java: - syntax - variable types - operators - control structures
http://web.stanford.edu/class/cs106x/ | CS106X Programming Abstractions in C++
http://web.stanford.edu/class/cs106b/ | CS106B Home

### General Info

Chris Piech
https://github.com/chrispiech | chrispiech (Chris Piech)
http://stanford.edu/~cpiech/bio/index.html | Chris Piech

T-Shirt
https://us.edstem.org/courses/490/discussion/57042 | Code in Place – Discussion

Excellent Notes
https://www.rpgbx.com/python/masternotes | ALL Notes, Compiled! — rpgbx
https://static1.squarespace.com/static/5e6685ae2118a020c291f4c0/t/5ec19af73ca6b4722cef1285/1589746454734/MASTER+PDF.pdf | MASTER+PDF.pdf

Midpoint Message
https://www.youtube.com/watch?v=yANUka-4mjE&feature=emb_title

https://compedu.stanford.edu/codeinplace/announcement/
https://compedu.stanford.edu/codeinplace/assn0/#/splash

https://compedu.stanford.edu/codeinplace/handouts/Recruitment.pdf | Recruitment.pdf
https://github.com/codeinplace2020

https://us.edstem.org/courses/490/discussion/
https://compedu.stanford.edu/codeinplace/v1/#/course
https://compedu.stanford.edu/codeinplace/v1/#/course/schedule | Schedule
https://compedu.stanford.edu/codeinplace/v1/#/handout/submissionInstructions.html | Handout
https://compedu.stanford.edu/codeinplace/v1/#/submissions | Submissions
https://compedu.stanford.edu/codeinplace/v1/#/handout/installingPyCharm
https://compedu.stanford.edu/codeinplace/v1/#/lectures | Lectures

<!--
http://web.stanford.edu/class/cs106a/ | CS106A

Python playground
https://us.edstem.org/code/python | Section 470 – Python Playground

https://twitter.com/davidjmalan/status/1258555662688309248 | David J. Malan on Twitter: "A mosaic of screenshots of @CS50's Office Hours via @Zoom_us on 7 May 2020 with 354+ students from &lt;= 114 countries around the world. #computerscience #education #programming #code #community https://t.co/FIB4nX4XVW" / Twitter
-->

### Assignments and Resources

https://compedu.stanford.edu/codeinplace/v1/#/example/index.html | Worked Example

Midpoint
https://static.us.edusercontent.com/files/czQD53Pp3JyBCA4BcERBUHoU | https://static.us.edusercontent.com/files/9p3RFpGWL0DvhAUmoz2p3KUj

Week 2 Notes
https://us.edstem.org/courses/1470/discussion/46041 | Section 470 – Discussion
Week 2 Reminder
https://us.edstem.org/courses/1470/discussion/43529 | Section 470 – Discussion
Week 4 Notes
https://us.edstem.org/courses/1470/discussion/58899 | Section 470 – Discussion
https://static.us.edusercontent.com/files/dN7xThik0SRKeqbahSkrKoDJ

https://www.youtube.com/watch?time_continue=430&v=Y9Qi-6TWwpM&feature=emb_logo | Lecture10 - Checkers - YouTube
https://www.youtube.com/watch?time_continue=551&v=8PCQndHgkPE&feature=emb_logo | Lecture8 - Calendar - YouTube
https://www.youtube.com/watch?time_continue=112&v=lZ8DGnIRsng&feature=emb_logo | Lecture7 - Anatomy of a Function - YouTube
https://www.youtube.com/watch?time_continue=340&v=Y_IWN4OxhlM&feature=emb_logo | Lecture6 - Guess Num and Sentinal Sum - YouTube

https://compedu.stanford.edu/codeinplace/v1/#/handout/Assignment1.pdf
https://compedu.stanford.edu/codeinplace/v1/#/handout/section1.pdf
https://compedu.stanford.edu/codeinplace/v1/#/karel/section1/hospital | Hospital
https://compedu.stanford.edu/codeinplace/v1/#/handout/section2.pdf | Handout
https://compedu.stanford.edu/codeinplace/v1/#/handout/Assignment2.pdf | Handout
https://codeinplace2020.github.io/faqs/Assignment2.pdf | Microsoft Word - Assignment 2.docx
https://compedu.stanford.edu/codeinplace/v1/#/assignment/khansole | Assignment
https://codeinplace2020.github.io/faqs/section3-v2.pdf | section3-v2.pdf
https://codeinplace2020.github.io/faqs/section3-alt.pdf | section3-alt.pdf
https://codeinplace2020.github.io/faqs/section3.pdf | section3.pdf
https://codeinplace2020.github.io/faqs/section5.pdf | section5.pdf

### Karel

* [Karel Programming Language Wikipedia](https://en.wikipedia.org/wiki/Karel_(programming_language))
* [Karel The Robot: A Gentle Introduction to the Art of Programming](https://www.amazon.com/Karel-Robot-2E-Richard-Pattis/dp/0471597252)

<!--
https://compedu.stanford.edu/karel-reader/docs/python/en/intro.html | Karel Reader
https://compedu.stanford.edu/karel-reader/docs/python/en/reference.html | Karel Reader

Karel on Instagram
https://www.instagram.com/p/B_YSrXvn6F4/

Karel IDE
http://stanford.edu/~cpiech/karel/lessons.html#/english/unit8/lesson5

Reeborg
http://reeborg.ca/docs/en/# | Learn Python with Reeborg! — Learn Python with Reeborg
http://reeborg.ca/reeborg.html?lang=en&mode=python&menu=%2Fworlds%2Fmenus%2Fselect_collection_en.json&name=Other%20worlds&url=%2Fworlds%2Fmenus%2Fselect_collection_en.json | Reeborg's World

http://reeborg.ca/docs/en/basics/move.html | 1. First program — Learn Python with Reeborg
-->
