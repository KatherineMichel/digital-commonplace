# Python Doc- Data

## General Notes

<!--
dir()
https://www.youtube.com/watch?v=LxCdn18eGng&feature=emb_logo


https://en.wikipedia.org/wiki/Backward_compatibility | Backward compatibility - Wikipedia
https://en.wikipedia.org/wiki/Self-documenting_code | Self-documenting code - Wikipedia

https://codeinplace2020.github.io/faqs/7-Functions.pdf | 7-Functions

https://twitter.com/unclebobmartin/status/1010660993851117569 | Uncle Bob Martin on Twitter: "Programs are made up of Dijkstra’s three structures: Sequence, Selection, and Iteration. Each of these is based upon jumps. Sequential statements jump from the end of the first to be beginning of the second."

https://stackoverflow.com/questions/373419/whats-the-difference-between-passing-by-reference-vs-passing-by-value | language agnostic - What's the difference between passing by reference vs. passing by value? - Stack Overflow
https://developer.mozilla.org/en-US/docs/Glossary/Parameter | Parameter - MDN Web Docs Glossary: Definitions of Web-related terms | MDN
-->

<!--
1.2. Notation
https://docs.python.org/3/reference/introduction.html#notation

https://docs.python.org/3/tutorial/controlflow.html#intermezzo-coding-style

http://akaptur.com/blog/2014/03/16/reading-ebnf/ | Reading EBNF - Allison Kaptur
https://en.wikipedia.org/wiki/Extended_Backus%E2%80%93Naur_form | Extended Backus–Naur form - Wikipedia
https://en.wikipedia.org/wiki/Backus%E2%80%93Naur_form	
https://www.iso.org/standard/26153.html | ISO/IEC 14977:1996 - Information technology -- Syntactic metalanguage -- Extended BNF
https://standards.iso.org/ittf/PubliclyAvailableStandards/s026153_ISO_IEC_14977_1996(E).zip | Publicly Available Standards
-->

<!--
https://www.python.org/dev/peps/pep-0008/ | PEP 8 -- Style Guide for Python Code | Python.org

negative indexes python - Google Search

Coding problems
https://docs.python.org/3/library/string.html | string — Common string operations — Python 3.10.0a0 documentation
https://docs.python.org/3/library/stdtypes.html#str.replace
https://docs.python.org/3/library/array.html | array — Efficient arrays of numeric values — Python 3.8.6rc1 documentation
https://docs.python.org/3/library/functions.html#func-range | Built-in Functions — Python 3.8.2 documentation
https://docs.python.org/3.3/library/stdtypes.html?highlight=range#ranges | 4. Built-in Types — Python 3.3.7 documentation
https://docs.python.org/2.3/whatsnew/section-slices.html | 15 Extended Slices
https://docs.python.org/3.4/library/functions.html?highlight=ord#ord | 2. Built-in Functions — Python 3.4.10 documentation
https://en.wikipedia.org/wiki/Bit_array | Bit array - Wikipedia

https://en.wikipedia.org/wiki/Precondition | Precondition - Wikipedia
https://en.wikipedia.org/wiki/Postcondition | Postcondition - Wikipedia

https://en.wikipedia.org/wiki/Off-by-one_error | Off-by-one error - Wikipedia
https://en.wikipedia.org/wiki/Off-by-one_error#Fencepost_error | Off-by-one error - Wikipedia

Errors
https://docs.python.org/3/library/exceptions.html#TypeError | Built-in Exceptions — Python 3.8.3 documentation
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypeError | TypeError - JavaScript | MDN
https://docs.python.org/3/library/exceptions.html#NameError | Built-in Exceptions — Python 3.8.3 documentation
https://docs.python.org/3/library/exceptions.html#ValueError | Built-in Exceptions — Python 3.8.3 documentation
https://eli.thegreenplace.net/2011/05/15/understanding-unboundlocalerror-in-python/ | Understanding UnboundLocalError in Python - Eli Bendersky's website

https://en.wikipedia.org/wiki/Control_flow
https://docs.python.org/3/tutorial/controlflow.html | 4. More Control Flow Tools — Python 3.8.2 documentation
https://en.wikipedia.org/wiki/Conditional_(computer_programming) | Conditional (computer programming) - Wikipedia
https://en.wikipedia.org/wiki/Conditional_(computer_programming)#If%E2%80%93then(%E2%80%93else) | Conditional (computer programming) - Wikipedia
https://docs.python.org/3/reference/compound_stmts.html#the-while-statement | 8. Compound statements — Python 3.8.2 documentation

https://docs.python.org/3/library/functions.html | Built-in Functions — Python 3.8.3 documentation

https://docs.python.org/3/library/functions.html#built-in-funcs
https://docs.python.org/3/library/constants.html#built-in-consts

Recommended
https://docs.python.org/3/library/pathlib.html | pathlib — Object-oriented filesystem paths — Python 3.8.3 documentation

https://docs.python.org/3/library/sys.html#sys.path | sys — System-specific parameters and functions — Python 3.8.6 documentation
https://docs.python.org/3/library/filesys.html | File and Directory Access — Python 3.8.6 documentation

Super
https://docs.python.org/2/library/functions.html#super | 2. Built-in Functions — Python 2.7.16 documentation

https://en.wikipedia.org/wiki/Increment_and_decrement_operators
https://en.wikipedia.org/wiki/Concatenation | Concatenation - Wikipedia

Use Often
https://realpython.com/python-f-strings/ | Python 3's f-Strings: An Improved String Formatting Syntax (Guide) – Real Python
https://docs.python.org/3/reference/lexical_analysis.html#f-strings | 2. Lexical analysis — Python 3.8.3 documentation
https://docs.python.org/3/library/random.html | random — Generate pseudo-random numbers — Python 3.9.0a5 documentation
https://docs.python.org/3/library/math.html | math — Mathematical functions — Python 3.8.2 documentation
https://docs.python.org/3/library/math.html#math.floor
https://docs.python.org/3/library/functions.html#open | Built-in Functions — Python 3.8.5 documentation

https://docs.python.org/3/library/stdtypes.html?highlight=split#str.split | 4. Built-in Types — Python 3.3.7 documentation
https://docs.python.org/3/library/os.path.html#os.path.join

https://docs.python.org/3/library/pathlib.html#pathlib.Path.replace | pathlib — Object-oriented filesystem paths — Python 3.8.5 documentation

Regular expression
https://en.wikipedia.org/wiki/Regular_expression | Regular expression - Wikipedia
https://docs.python.org/3/library/re.html | re — Regular expression operations — Python 3.8.3 documentation
https://docs.python.org/3/library/re.html#module-re | re — Regular expression operations — Python 3.8.6rc1 documentation
-->

## Strings

Strip whitespace (right, left, both sides)

```python
lstrip()
rstrip()
strip()
```

<!--
6.1. string — Common string operations
https://docs.python.org/3/library/string.html#module-string
https://docs.python.org/3/library/string.html#string-constants
https://docs.python.org/3/library/string.html#custom-string-formatting
https://docs.python.org/3/library/string.html#format-string-syntax
https://docs.python.org/3/library/string.html#format-specification-mini-language
https://docs.python.org/3/library/string.html#format-examples
https://docs.python.org/3/library/string.html#template-strings
https://docs.python.org/3/library/string.html#helper-functions

String methods
https://docs.python.org/3/library/stdtypes.html#string-methods

https://docs.python.org/3/library/stdtypes.html#str.lstrip
https://docs.python.org/3/library/stdtypes.html#str.rstrip
https://docs.python.org/3/library/stdtypes.html#str.strip
-->

<!--
## Tutorial

3. An Informal Introduction to Python
https://docs.python.org/3/tutorial/introduction.html
https://docs.python.org/3/tutorial/introduction.html#an-informal-introduction-to-python
https://docs.python.org/3/tutorial/introduction.html#using-python-as-a-calculator
https://docs.python.org/3/tutorial/introduction.html#numbers
https://docs.python.org/3/tutorial/introduction.html#strings
https://docs.python.org/3/library/stdtypes.html#textseq
https://docs.python.org/3/reference/lexical_analysis.html#f-strings
Fibonacci series 
https://docs.python.org/3/tutorial/introduction.html#first-steps-towards-programming



Unix
https://docs.python.org/3/tutorial/appendix.html#executable-python-scripts
https://docs.python.org/3/tutorial/appendix.html#the-interactive-startup-file

https://docs.python.org/3/tutorial/appendix.html#interactive-mode

https://docs.python.org/3/tutorial/appendix.html#error-handling
https://docs.python.org/3/reference/compound_stmts.html#try
https://docs.python.org/3/reference/compound_stmts.html#except
https://docs.python.org/3/library/exceptions.html#KeyboardInterrupt
https://docs.python.org/3/reference/compound_stmts.html#finally
https://docs.python.org/3/reference/simple_stmts.html#from
https://docs.python.org/3/reference/simple_stmts.html#raise
https://docs.python.org/3/library/constants.html#None

https://docs.python.org/3/tutorial/appendix.html#the-customization-modules


File
https://docs.python.org/3/library/os.html#file-object-creation
https://docs.python.org/3/library/os.html#os.open
https://docs.python.org/3/library/functions.html#open
https://docs.python.org/3/library/fileinput.html#module-fileinput
https://docs.python.org/3/library/tempfile.html#module-tempfile
https://docs.python.org/3/library/shutil.html#module-shutil

Path
https://docs.python.org/3/library/os.path.html#os.path.join

10.4. Error Output Redirection and Program Termination
https://docs.python.org/3/tutorial/stdlib.html#error-output-redirection-and-program-termination



https://docs.python.org/3/library/allos.html

16.14. platform — Access to underlying platform’s identifying data
https://docs.python.org/3/library/platform.html

10.1. Operating System Interface
https://docs.python.org/3/tutorial/stdlib.html#operating-system-interface

https://treyhunner.com/2018/12/why-you-should-be-using-pathlib/

16.1. os — Miscellaneous operating system interfaces
https://docs.python.org/3/library/os.html

11.2. os.path — Common pathname manipulations
https://docs.python.org/3/library/os.path.html

11.4. stat — Interpreting stat() results
https://docs.python.org/3/library/stat.html
https://docs.python.org/3/library/os.html#os.stat

11.1. pathlib — Object-oriented filesystem paths
https://docs.python.org/3/library/pathlib.html
Interesting (os and os.path versus pathlib)
https://docs.python.org/3/library/pathlib.html#correspondence-to-tools-in-the-os-module

29.1. sys — System-specific parameters and functions
https://docs.python.org/3/library/sys.html
https://docs.python.org/3/library/sys.html#sys.path
https://docs.python.org/3/library/sys.html#sys.stdin
https://docs.python.org/3/library/sys.html#sys.stdout
https://docs.python.org/3/library/sys.html#sys.stderr

30.2. sysconfig — Provide access to Python’s configuration information
https://docs.python.org/3/library/sysconfig.html

11.10. shutil — High-level file operations
https://docs.python.org/3/library/shutil.html


10.3. Command Line Arguments
https://docs.python.org/3/tutorial/stdlib.html#command-line-arguments
https://docs.python.org/3/library/sys.html#sys.argv

10.5. String Pattern Matching
https://docs.python.org/3/tutorial/stdlib.html#string-pattern-matching
https://docs.python.org/3/library/re.html#module-re

10.2. File Wildcards
https://docs.python.org/3/tutorial/stdlib.html#file-wildcards
https://docs.python.org/3/library/glob.html#module-glob

10.12. Batteries Included
https://docs.python.org/3/library/json.html#module-json
https://docs.python.org/3/library/csv.html#module-csv
https://docs.python.org/3/library/sqlite3.html#module-sqlite3

10.6. Mathematics
https://docs.python.org/3/tutorial/stdlib.html#mathematics
https://docs.python.org/3/library/random.html#module-random

11.1. Output Formatting
https://docs.python.org/3/tutorial/stdlib2.html#output-formatting
https://docs.python.org/3/library/functions.html#repr
https://docs.python.org/3/library/pprint.html#module-pprint

11.7. Tools for Working with Lists
https://docs.python.org/3/tutorial/stdlib2.html#tools-for-working-with-lists
https://docs.python.org/3/library/array.html#module-array
https://docs.python.org/3/library/array.html#array.array
https://docs.python.org/3/library/collections.html#module-collections
https://docs.python.org/3/library/collections.html#collections.deque
https://docs.python.org/3/library/bisect.html#module-bisect
https://docs.python.org/3/library/heapq.html#module-heapq
11.8. Decimal Floating Point Arithmetic
https://docs.python.org/3/tutorial/stdlib2.html#decimal-floating-point-arithmetic

11.4. Multi-threading
https://docs.python.org/3/tutorial/stdlib2.html#multi-threading
https://docs.python.org/3/library/threading.html#module-threading
https://docs.python.org/3/library/queue.html#module-queue
https://docs.python.org/3/library/queue.html#queue.Queue

10.11. Quality Control
https://docs.python.org/3/tutorial/stdlib.html#quality-control

10.10. Performance Measurement
https://docs.python.org/3/tutorial/stdlib.html#performance-measurement

28.4. The Python Profilers
28.5. timeit — Measure execution time of small code snippets
28.6. trace — Trace or track Python statement execution
https://docs.python.org/3/library/profile.html
https://docs.python.org/3/library/timeit.html
https://docs.python.org/3/library/trace.html

https://docs.python.org/3/library/profile.html#module-profile
https://docs.python.org/3/library/timeit.html#module-timeit
https://docs.python.org/3/library/profile.html#module-pstats

11.5. Logging
https://docs.python.org/3/tutorial/stdlib2.html#logging
https://docs.python.org/3/library/logging.html#module-logging

10.8. Dates and Times
https://docs.python.org/3/tutorial/stdlib.html#dates-and-times
https://docs.python.org/3/library/datetime.html#module-datetime

16.3. time — Time access and conversions
https://docs.python.org/3/library/time.html
8.1. datetime — Basic date and time types
https://docs.python.org/3/library/datetime.html
8.2. calendar — General calendar-related functions
https://docs.python.org/3/library/calendar.html


## Data Model

https://docs.python.org/3/reference/datamodel.html#implementing-descriptors
https://docs.python.org/3/reference/datamodel.html#invoking-descriptors
https://docs.python.org/3/reference/datamodel.html#slots
https://docs.python.org/3/reference/datamodel.html#customizing-class-creation
https://docs.python.org/3/reference/datamodel.html#metaclasses
https://docs.python.org/3/reference/datamodel.html#resolving-mro-entries
https://docs.python.org/3/reference/datamodel.html#determining-the-appropriate-metaclass
https://docs.python.org/3/reference/datamodel.html#preparing-the-class-namespace
https://docs.python.org/3/reference/datamodel.html#executing-the-class-body
https://docs.python.org/3/reference/datamodel.html#creating-the-class-object
https://docs.python.org/3/reference/datamodel.html#metaclass-example
https://docs.python.org/3/reference/datamodel.html#customizing-instance-and-subclass-checks

https://docs.python.org/3/reference/datamodel.html#emulating-generic-types
https://docs.python.org/3/reference/datamodel.html#emulating-callable-objects
https://docs.python.org/3/reference/datamodel.html#emulating-container-types
https://docs.python.org/3/reference/datamodel.html#emulating-numeric-types
https://docs.python.org/3/reference/datamodel.html#with-statement-context-managers
https://docs.python.org/3/reference/datamodel.html#special-method-lookup

## Method Resolution Order

Method Resolution Order
* [C3 Linearization Wikipedia](https://en.wikipedia.org/wiki/C3_linearization)
* [Multiple Inheritance Wikipedia](https://en.wikipedia.org/wiki/Multiple_inheritance)
* [The Python 2.3 Method Resolution Order](https://www.python.org/download/releases/2.3/mro)

MRO
http://python-history.blogspot.com/2010/06/method-resolution-order.html
https://docs.python.org/3/library/stdtypes.html#class.__mro__

New Style
https://www.python.org/doc/newstyle/ | New-style Classes | Python.org
https://docs.python.org/2/glossary.html#term-new-style-class | Glossary — Python 2.7.16 documentation
http://python-history.blogspot.com/2010/06/inside-story-on-new-style-classes.html


## Classes, Objects, Functions, Methods, Attributes

https://docs.python.org/3/glossary.html#term-new-style-class
https://docs.python.org/3/glossary.html#term-object
https://docs.python.org/3/reference/datamodel.html#objects-values-and-types
https://docs.python.org/3/reference/datamodel.html#objects
https://docs.python.org/3/reference/datamodel.html#basic-customization

https://docs.python.org/3/reference/datamodel.html#customizing-attribute-access
https://docs.python.org/3/reference/datamodel.html#customizing-module-attribute-access

https://docs.python.org/3/glossary.html#term-class
https://docs.python.org/3/tutorial/classes.html#classes
https://docs.python.org/3/reference/compound_stmts.html#class-definitions

https://docs.python.org/3/tutorial/classes.html#a-first-look-at-classes
https://docs.python.org/3/tutorial/classes.html#class-definition-syntax

https://docs.python.org/3/library/stdtypes.html#classes-and-class-instances

Important!
https://docs.python.org/3/tutorial/classes.html#class-objects
https://docs.python.org/3/tutorial/classes.html#instance-objects
https://docs.python.org/3/tutorial/classes.html#method-objects

https://docs.python.org/3/tutorial/classes.html#random-remarks
https://docs.python.org/3/tutorial/classes.html#inheritance
https://docs.python.org/3/tutorial/classes.html#multiple-inheritance

https://docs.python.org/3/tutorial/classes.html#class-and-instance-variables
https://docs.python.org/3/tutorial/classes.html#private-variables

Function Objects
https://docs.python.org/3/library/stdtypes.html#functions

Calls!
https://docs.python.org/3/reference/expressions.html#calls

"A series of statements which returns some value to a caller. It can also be passed zero or more arguments which may be used in the execution of the body. See also parameter, method, and the Function definitions section."
https://stackoverflow.com/questions/53485906/what-exactly-is-a-caller-in-python
https://docs.python.org/3/glossary.html#term-function

https://docs.python.org/3/reference/compound_stmts.html#function-definitions

https://docs.python.org/3/tutorial/controlflow.html#defining-functions
https://docs.python.org/3/tutorial/controlflow.html#more-on-defining-functions

"There are really two flavors of function objects: built-in functions and user-defined functions. Both support the same operation (to call the function), but the implementation is different, hence the different object types."
https://docs.python.org/3/library/stdtypes.html#functions

Look again
https://docs.python.org/3/glossary.html#term-generic-function

Usually used for type hints
https://docs.python.org/3/tutorial/controlflow.html#function-annotations

"Methods are functions that are called using the attribute notation. There are two flavors: built-in methods (such as append() on lists) and class instance methods. Built-in methods are described with the types that support them.
If you access a method (a function defined in a class namespace) through an instance, you get a special object: a bound method (also called instance method) object."
https://docs.python.org/3/library/stdtypes.html#methods

"A function which is defined inside a class body. If called as an attribute of an instance of that class, the method will get the instance object as its first argument (which is usually called self). See function and nested scope."
https://docs.python.org/3/glossary.html#term-method

https://docs.python.org/3/glossary.html#term-attribute

https://docs.python.org/3/reference/expressions.html#attribute-references


## Mapping Operators to Functions

Mapping Operators to Functions

"For backward compatibility, many of these have a variant with the double underscores kept."
https://docs.python.org/3/library/operator.html
https://docs.python.org/3/library/operator.html#module-operator
https://docs.python.org/3/library/operator.html#mapping-operators-to-functions
https://docs.python.org/3/library/operator.html#inplace-operators


## Scope

Scope
* [Scope Wikipedia](https://en.wikipedia.org/wiki/Scope_(computer_science))

https://en.wikipedia.org/wiki/Scope_(computer_science)#Lexical_scope_vs._dynamic_scope


7.12. The global statement
https://docs.python.org/3/reference/simple_stmts.html#the-global-statement
7.13. The nonlocal statement
https://docs.python.org/3/reference/simple_stmts.html#the-nonlocal-statement

Classes
9.1. A Word About Names and Objects
https://docs.python.org/3/tutorial/classes.html#a-word-about-names-and-objects
9.2. Python Scopes and Namespaces
https://docs.python.org/3/tutorial/classes.html#python-scopes-and-namespaces
9.2.1. Scopes and Namespaces Example
https://docs.python.org/3/tutorial/classes.html#scopes-and-namespaces-example

https://docs.python.org/3/glossary.html#term-nested-scope


## Standard

https://docs.python.org/3/reference/lexical_analysis.html

https://docs.python.org/3/library/stdtypes.html#internal-objects
https://docs.python.org/3/reference/datamodel.html#the-standard-type-hierarchy

https://docs.python.org/3/library/stdtypes.html#code-objects
https://docs.python.org/3/library/stdtypes.html#type-objects

https://docs.python.org/3/reference/datamodel.html#types
https://docs.python.org/3/library/stdtypes.html#built-in-types
https://docs.python.org/3/library/stdtypes.html#other-built-in-types

https://docs.python.org/3/library/builtins.html
https://docs.python.org/3/library/functions.html#built-in-funcs
https://docs.python.org/3/library/constants.html#built-in-consts

https://docs.python.org/3/reference/expressions.html#expression-lists
https://docs.python.org/3/reference/simple_stmts.html#expression-statements
https://docs.python.org/3/reference/expressions.html

https://docs.python.org/3/tutorial/modules.html#standard-modules

3.1. Constants added by the site module

Special attribute and method names
https://docs.python.org/3/glossary.html#term-special-method
https://docs.python.org/3/reference/datamodel.html#special-method-names
"Some of these are not reported by the dir() built-in function."
https://docs.python.org/3/library/stdtypes.html#special-attributes
https://docs.python.org/3/reference/lexical_analysis.html#reserved-classes-of-identifiers


https://docs.python.org/3/glossary.html#term-decorator
https://docs.python.org/3/glossary.html#term-descriptor
https://docs.python.org/3/reference/datamodel.html#descriptors

dot notation
https://docs.python.org/3/library/stdtypes.html#modules


## Lexical Analysis

https://en.wikipedia.org/wiki/Lexical_analysis | Lexical analysis - Wikipedia

Lexical Analysis
https://docs.python.org/3/reference/lexical_analysis.html#logical-lines
https://docs.python.org/3/reference/lexical_analysis.html#physical-lines
https://docs.python.org/3/reference/lexical_analysis.html#comments
https://docs.python.org/3/reference/lexical_analysis.html#encoding-declarations
https://docs.python.org/3/reference/lexical_analysis.html#explicit-line-joining
https://docs.python.org/3/reference/lexical_analysis.html#implicit-line-joining
https://docs.python.org/3/reference/lexical_analysis.html#blank-lines
https://docs.python.org/3/reference/lexical_analysis.html#indentation
https://docs.python.org/3/reference/lexical_analysis.html#whitespace-between-tokens

https://docs.python.org/3/reference/lexical_analysis.html#line-structure
https://docs.python.org/3/reference/lexical_analysis.html#other-tokens
https://docs.python.org/3/reference/lexical_analysis.html#identifiers


## Utilities

https://pypi.org/project/ipdb/ | ipdb · PyPI

28. Debugging and Profiling
28.3. pdb — The Python Debugger
28.1. bdb — Debugger framework

https://docs.python.org/3/library/debug.html

https://docs.python.org/3/library/pdb.html#debugger-commands

29.9. traceback — Print or retrieve a stack traceback
https://docs.python.org/3/library/traceback.html

## Exceptions, Errors, Warnings

Repeat
16.1.1. Error Handling
https://docs.python.org/3/tutorial/appendix.html#error-handling

8. Errors and Exceptions
8.1. Syntax Errors
8.2. Exceptions
8.3. Handling Exceptions
8.4. Raising Exceptions
8.5. User-defined Exceptions
8.6. Defining Clean-up Actions
8.7. Predefined Clean-up Actions

* [errors](https://docs.python.org/3/tutorial/errors.html)

https://docs.python.org/3/tutorial/errors.html#errors-and-exceptions
https://docs.python.org/3/tutorial/errors.html#syntax-errors
https://docs.python.org/3/tutorial/errors.html#exceptions
https://docs.python.org/3/tutorial/errors.html#handling-exceptions
https://docs.python.org/3/tutorial/errors.html#raising-exceptions
https://docs.python.org/3/tutorial/errors.html#user-defined-exceptions
https://docs.python.org/3/tutorial/errors.html#defining-clean-up-actions
https://docs.python.org/3/tutorial/errors.html#predefined-clean-up-actions

5. Built-in Exceptions
5.1. Base classes
5.2. Concrete exceptions
5.3. Warnings
5.4. Exception hierarchy

* [exceptions](https://docs.python.org/3/library/exceptions.html)

https://docs.python.org/3/library/exceptions.html#built-in-exceptions
https://docs.python.org/3/library/exceptions.html#base-classes
https://docs.python.org/3/library/exceptions.html#concrete-exceptions

https://docs.python.org/3/library/exceptions.html#os-exceptions

https://docs.python.org/3/library/exceptions.html#exception-hierarchy


https://docs.python.org/3/library/exceptions.html#warnings

Python Warnings
* [warnings](https://docs.python.org/3/library/warnings.html)

30.5. warnings — Warning control
https://docs.python.org/3/library/warnings.html#warning-categories
https://docs.python.org/3/library/warnings.html#the-warnings-filter
https://docs.python.org/3/library/warnings.html#describing-warning-filters
https://docs.python.org/3/library/warnings.html#default-warning-filter
https://docs.python.org/3/library/warnings.html#overriding-the-default-filter
https://docs.python.org/3/library/warnings.html#temporarily-suppressing-warnings
https://docs.python.org/3/library/warnings.html#testing-warnings
https://docs.python.org/3/library/warnings.html#updating-code-for-new-versions-of-dependencies
https://docs.python.org/3/library/warnings.html#available-functions
https://docs.python.org/3/library/warnings.html#available-context-managers


https://docs.python.org/3/howto/argparse.html
"The program defines what arguments it requires, and argparse will figure out how to parse those out of sys.argv. The argparse module also automatically generates help and usage messages and issues errors when users give the program invalid arguments."

Alternative
16.5. getopt — C-style parser for command line options
https://docs.python.org/3/library/getopt.html

16.4. argparse — Parser for command-line options, arguments and sub-commands
https://docs.python.org/3/library/argparse.html
https://docs.python.org/3/library/argparse.html#example
https://docs.python.org/3/library/argparse.html#creating-a-parser
https://docs.python.org/3/library/argparse.html#adding-arguments
https://docs.python.org/3/library/argparse.html#parsing-arguments
https://docs.python.org/3/library/argparse.html#argumentparser-objects
https://docs.python.org/3/library/argparse.html#prog
https://docs.python.org/3/library/argparse.html#usage
https://docs.python.org/3/library/argparse.html#description
https://docs.python.org/3/library/argparse.html#epilog
https://docs.python.org/3/library/argparse.html#parents
https://docs.python.org/3/library/argparse.html#formatter-class
https://docs.python.org/3/library/argparse.html#prefix-chars
https://docs.python.org/3/library/argparse.html#fromfile-prefix-chars
https://docs.python.org/3/library/argparse.html#argument-default
https://docs.python.org/3/library/argparse.html#allow-abbrev
https://docs.python.org/3/library/argparse.html#conflict-handler
https://docs.python.org/3/library/argparse.html#add-help
https://docs.python.org/3/library/argparse.html#the-add-argument-method
https://docs.python.org/3/library/argparse.html#name-or-flags
https://docs.python.org/3/library/argparse.html#action
https://docs.python.org/3/library/argparse.html#nargs
https://docs.python.org/3/library/argparse.html#const
https://docs.python.org/3/library/argparse.html#default
https://docs.python.org/3/library/argparse.html#type
https://docs.python.org/3/library/argparse.html#choices
https://docs.python.org/3/library/argparse.html#required
https://docs.python.org/3/library/argparse.html#help
https://docs.python.org/3/library/argparse.html#metavar
https://docs.python.org/3/library/argparse.html#dest
https://docs.python.org/3/library/argparse.html#action-classes
https://docs.python.org/3/library/argparse.html#the-parse-args-method
https://docs.python.org/3/library/argparse.html#option-value-syntax
https://docs.python.org/3/library/argparse.html#invalid-arguments
https://docs.python.org/3/library/argparse.html#arguments-containing
https://docs.python.org/3/library/argparse.html#argument-abbreviations-prefix-matching
https://docs.python.org/3/library/argparse.html#beyond-sys-argv
https://docs.python.org/3/library/argparse.html#the-namespace-object
https://docs.python.org/3/library/argparse.html#other-utilities
https://docs.python.org/3/library/argparse.html#sub-commands
https://docs.python.org/3/library/argparse.html#filetype-objects
https://docs.python.org/3/library/argparse.html#argument-groups
https://docs.python.org/3/library/argparse.html#mutual-exclusion
https://docs.python.org/3/library/argparse.html#parser-defaults
https://docs.python.org/3/library/argparse.html#printing-help
https://docs.python.org/3/library/argparse.html#partial-parsing
https://docs.python.org/3/library/argparse.html#customizing-file-parsing
https://docs.python.org/3/library/argparse.html#exiting-methods
https://docs.python.org/3/library/argparse.html#intermixed-parsing
https://docs.python.org/3/library/argparse.html#upgrading-optparse-code

Regular Expression HOWTO
https://docs.python.org/3/howto/regex.html

6.2. re — Regular expression operations
https://docs.python.org/3/library/re.html#regular-expression-syntax
https://docs.python.org/3/library/re.html#module-contents
https://docs.python.org/3/library/re.html#regular-expression-objects
https://docs.python.org/3/library/re.html#match-objects
https://docs.python.org/3/library/re.html#regular-expression-examples
https://docs.python.org/3/library/re.html#checking-for-a-pair
https://docs.python.org/3/library/re.html#simulating-scanf
https://docs.python.org/3/library/re.html#search-vs-match
https://docs.python.org/3/library/re.html#making-a-phonebook
https://docs.python.org/3/library/re.html#text-munging
https://docs.python.org/3/library/re.html#finding-all-adverbs
https://docs.python.org/3/library/re.html#finding-all-adverbs-and-their-positions
https://docs.python.org/3/library/re.html#raw-string-notation
https://docs.python.org/3/library/re.html#writing-a-tokenizer

11.7. glob — Unix style pathname pattern expansion
https://docs.python.org/3/library/glob.html

6. Text Processing Services
https://docs.python.org/3/library/text.html


Unicode HOWTO
https://docs.python.org/3/howto/unicode.html

22.5. urllib — URL handling modules
22.6. urllib.request — Extensible library for opening URLs
22.7. urllib.response — Response classes used by urllib
22.8. urllib.parse — Parse URLs into components

https://docs.python.org/3/library/urllib.html
https://docs.python.org/3/library/urllib.request.html
https://docs.python.org/3/library/urllib.parse.html

"The module has been designed to match the Internet RFC on Relative Uniform Resource Locators. It supports the following URL schemes: file, ftp, gopher, hdl, http, https, imap, mailto, mms, news, nntp, prospero, rsync, rtsp, rtspu, sftp, shttp, sip, sips, snews, svn, svn+ssh, telnet, wais, ws, wss."


21. Structured Markup Processing Tools
21.1. html — HyperText Markup Language support
21.2. html.parser — Simple HTML and XHTML parser
21.3. html.entities — Definitions of HTML general entities

20. Structured Markup Processing Tools
https://docs.python.org/3/library/markup.html
20.1. html — HyperText Markup Language support
https://docs.python.org/3/library/html.html

https://docs.python.org/3/library/html.parser.html
https://docs.python.org/3/library/html.parser.html#example-html-parser-application
https://docs.python.org/3/library/html.parser.html#htmlparser-methods
https://docs.python.org/3/library/html.parser.html#examples
https://docs.python.org/3/library/html.entities.html

14. File Formats
https://docs.python.org/3/library/fileformats.html

14.1. csv — CSV File Reading and Writing
https://docs.python.org/3/library/csv.html
https://docs.python.org/3/library/csv.html#module-contents
https://docs.python.org/3/library/csv.html#dialects-and-formatting-parameters
https://docs.python.org/3/library/csv.html#reader-objects
https://docs.python.org/3/library/csv.html#writer-objects
https://docs.python.org/3/library/csv.html#examples


21. Internet Protocols and Support

19.2. json — JSON encoder and decoder
20.2. json — JSON encoder and decoder
7.2.2. Saving structured data with json
https://docs.python.org/3/tutorial/inputoutput.html#saving-structured-data-with-json

https://docs.python.org/3/library/json.html

https://docs.python.org/3/library/json.html#basic-usage
https://docs.python.org/3/library/json.html#encoders-and-decoders
https://docs.python.org/3/library/json.html#exceptions
https://docs.python.org/3/library/json.html#standard-compliance-and-interoperability
https://docs.python.org/3/library/json.html#character-encodings
https://docs.python.org/3/library/json.html#infinite-and-nan-number-values
https://docs.python.org/3/library/json.html#repeated-names-within-an-object
https://docs.python.org/3/library/json.html#top-level-non-object-non-array-values
https://docs.python.org/3/library/json.html#implementation-limitations
https://docs.python.org/3/library/json.html#module-json.tool
https://docs.python.org/3/library/json.html#command-line-options


22.11. http — HTTP modules
22.12. http.client — HTTP protocol client
22.22. http.server — HTTP servers
22.23. http.cookies — HTTP state management
22.24. http.cookiejar — Cookie handling for HTTP clients

https://docs.python.org/3/library/http.html

Not recommended for production
https://docs.python.org/3/library/http.server.html

https://docs.python.org/3/library/http.html#http-status-codes

https://docs.python.org/3/library/http.client.html
https://docs.python.org/3/library/http.client.html#httpconnection-objects
https://docs.python.org/3/library/http.client.html#httpresponse-objects
https://docs.python.org/3/library/http.client.html#examples
https://docs.python.org/3/library/http.client.html#httpmessage-objects

https://docs.python.org/3/library/http.cookies.html
https://docs.python.org/3/library/http.cookiejar.html


## CGI and WSGI

22.2. cgi — Common Gateway Interface support
22.3. cgitb — Traceback manager for CGI scripts
22.4. wsgiref — WSGI Utilities and Reference Implementation

https://docs.python.org/3/library/cgi.html
https://docs.python.org/3/library/cgi.html#introduction
https://docs.python.org/3/library/cgi.html#using-the-cgi-module
https://docs.python.org/3/library/cgi.html#higher-level-interface
https://docs.python.org/3/library/cgi.html#functions
https://docs.python.org/3/library/cgi.html#caring-about-security
https://docs.python.org/3/library/cgi.html#installing-your-cgi-script-on-a-unix-system
https://docs.python.org/3/library/cgi.html#testing-your-cgi-script
https://docs.python.org/3/library/cgi.html#debugging-cgi-scripts
https://docs.python.org/3/library/cgi.html#common-problems-and-solutions

https://docs.python.org/3/library/cgitb.html

https://docs.python.org/3/library/wsgiref.html
https://docs.python.org/3/library/wsgiref.html#module-wsgiref.util
https://docs.python.org/3/library/wsgiref.html#module-wsgiref.headers
https://docs.python.org/3/library/wsgiref.html#module-wsgiref.simple_server
https://docs.python.org/3/library/wsgiref.html#module-wsgiref.validate
https://docs.python.org/3/library/wsgiref.html#module-wsgiref.handlers
https://docs.python.org/3/library/wsgiref.html#examples


12. Data Persistence
12.6. sqlite3 — DB-API 2.0 interface for SQLite databases

https://docs.python.org/3/library/sqlite3.html

https://docs.python.org/3/library/sqlite3.html#module-functions-and-constants
https://docs.python.org/3/library/sqlite3.html#connection-objects
https://docs.python.org/3/library/sqlite3.html#cursor-objects
https://docs.python.org/3/library/sqlite3.html#row-objects
https://docs.python.org/3/library/sqlite3.html#exceptions
https://docs.python.org/3/library/sqlite3.html#sqlite-and-python-types
https://docs.python.org/3/library/sqlite3.html#introduction
https://docs.python.org/3/library/sqlite3.html#using-adapters-to-store-additional-python-types-in-sqlite-databases
https://docs.python.org/3/library/sqlite3.html#converting-sqlite-values-to-custom-python-types
https://docs.python.org/3/library/sqlite3.html#default-adapters-and-converters
https://docs.python.org/3/library/sqlite3.html#controlling-transactions
https://docs.python.org/3/library/sqlite3.html#using-sqlite3-efficiently
https://docs.python.org/3/library/sqlite3.html#using-shortcut-methods
https://docs.python.org/3/library/sqlite3.html#accessing-columns-by-name-instead-of-by-index
https://docs.python.org/3/library/sqlite3.html#using-the-connection-as-a-context-manager
https://docs.python.org/3/library/sqlite3.html#common-issues

https://docs.python.org/3/library/sqlite3.html#multithreading

14. File Formats
14.5. plistlib — Generate and parse Mac OS X .plist files
https://docs.python.org/3/library/plistlib.html


https://docs.pytest.org/en/stable/

27.4. unittest — Unit testing framework
27.5. unittest.mock — mock object library
27.6. unittest.mock — getting started
27.8. test — Regression tests package for Python
27.9. test.support — Utilities for the Python test suite
27.10. test.support.script_helper — Utilities for the Python execution tests

https://docs.python.org/3/library/unittest.html#unittest.TestCase

7.3. The assert statement
https://docs.python.org/3/reference/simple_stmts.html#the-assert-statement
AssertionError

Where is this?
https://docs.python.org/3/library/unittest.html#assert-methods

https://docs.python.org/3/library/unittest.html#test-discovery

https://docs.python.org/3/library/unittest.html
https://docs.python.org/3/library/unittest.html#basic-example
https://docs.python.org/3/library/unittest.html#command-line-interface
https://docs.python.org/3/library/unittest.html#command-line-options
https://docs.python.org/3/library/unittest.html#organizing-test-code
https://docs.python.org/3/library/unittest.html#re-using-old-test-code
https://docs.python.org/3/library/unittest.html#skipping-tests-and-expected-failures
https://docs.python.org/3/library/unittest.html#distinguishing-test-iterations-using-subtests
https://docs.python.org/3/library/unittest.html#classes-and-functions
https://docs.python.org/3/library/unittest.html#test-cases
https://docs.python.org/3/library/unittest.html#deprecated-aliases
https://docs.python.org/3/library/unittest.html#grouping-tests
https://docs.python.org/3/library/unittest.html#loading-and-running-tests
https://docs.python.org/3/library/unittest.html#class-and-module-fixtures
https://docs.python.org/3/library/unittest.html#setupclass-and-teardownclass
https://docs.python.org/3/library/unittest.html#setupmodule-and-teardownmodule
https://docs.python.org/3/library/unittest.html#signal-handling

unittest.mock patch
https://docs.python.org/3/library/unittest.mock.html
https://docs.python.org/3/library/unittest.mock.html#quick-guide
https://docs.python.org/3/library/unittest.mock.html#the-mock-class
https://docs.python.org/3/library/unittest.mock.html#calling
https://docs.python.org/3/library/unittest.mock.html#deleting-attributes
https://docs.python.org/3/library/unittest.mock.html#mock-names-and-the-name-attribute
https://docs.python.org/3/library/unittest.mock.html#attaching-mocks-as-attributes
https://docs.python.org/3/library/unittest.mock.html#the-patchers
https://docs.python.org/3/library/unittest.mock.html#patch
https://docs.python.org/3/library/unittest.mock.html#patch-object
https://docs.python.org/3/library/unittest.mock.html#patch-dict
https://docs.python.org/3/library/unittest.mock.html#patch-multiple
https://docs.python.org/3/library/unittest.mock.html#patch-methods-start-and-stop
https://docs.python.org/3/library/unittest.mock.html#patch-builtins
https://docs.python.org/3/library/unittest.mock.html#test-prefix
https://docs.python.org/3/library/unittest.mock.html#nesting-patch-decorators
https://docs.python.org/3/library/unittest.mock.html#where-to-patch
https://docs.python.org/3/library/unittest.mock.html#patching-descriptors-and-proxy-objects
https://docs.python.org/3/library/unittest.mock.html#magicmock-and-magic-method-support
https://docs.python.org/3/library/unittest.mock.html#mocking-magic-methods
https://docs.python.org/3/library/unittest.mock.html#magic-mock
https://docs.python.org/3/library/unittest.mock.html#helpers
https://docs.python.org/3/library/unittest.mock.html#sentinel
https://docs.python.org/3/library/unittest.mock.html#default
https://docs.python.org/3/library/unittest.mock.html#call
https://docs.python.org/3/library/unittest.mock.html#create-autospec
https://docs.python.org/3/library/unittest.mock.html#any
https://docs.python.org/3/library/unittest.mock.html#filter-dir
https://docs.python.org/3/library/unittest.mock.html#mock-open
https://docs.python.org/3/library/unittest.mock.html#autospeccing
https://docs.python.org/3/library/unittest.mock.html#sealing-mocks

https://docs.python.org/3/library/unittest.mock-examples.html
https://docs.python.org/3/library/unittest.mock-examples.html#unittest-mock-getting-started
https://docs.python.org/3/library/unittest.mock-examples.html#using-mock
https://docs.python.org/3/library/unittest.mock-examples.html#mock-patching-methods
https://docs.python.org/3/library/unittest.mock-examples.html#mock-for-method-calls-on-an-object
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-classes
https://docs.python.org/3/library/unittest.mock-examples.html#naming-your-mocks
https://docs.python.org/3/library/unittest.mock-examples.html#tracking-all-calls
https://docs.python.org/3/library/unittest.mock-examples.html#setting-return-values-and-attributes
https://docs.python.org/3/library/unittest.mock-examples.html#raising-exceptions-with-mocks
https://docs.python.org/3/library/unittest.mock-examples.html#side-effect-functions-and-iterables
https://docs.python.org/3/library/unittest.mock-examples.html#creating-a-mock-from-an-existing-object
https://docs.python.org/3/library/unittest.mock-examples.html#patch-decorators
https://docs.python.org/3/library/unittest.mock-examples.html#further-examples
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-chained-calls
https://docs.python.org/3/library/unittest.mock-examples.html#partial-mocking
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-a-generator-method
https://docs.python.org/3/library/unittest.mock-examples.html#applying-the-same-patch-to-every-test-method
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-unbound-methods
https://docs.python.org/3/library/unittest.mock-examples.html#checking-multiple-calls-with-mock
https://docs.python.org/3/library/unittest.mock-examples.html#coping-with-mutable-arguments
https://docs.python.org/3/library/unittest.mock-examples.html#nesting-patches
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-a-dictionary-with-magicmock
https://docs.python.org/3/library/unittest.mock-examples.html#mock-subclasses-and-their-attributes
https://docs.python.org/3/library/unittest.mock-examples.html#mocking-imports-with-patch-dict
https://docs.python.org/3/library/unittest.mock-examples.html#tracking-order-of-calls-and-less-verbose-call-assertions
https://docs.python.org/3/library/unittest.mock-examples.html#more-complex-argument-matching
-->

## Kenneth Reitz Advice to Me 

* Python Object Model, [Python Data Model Docs](https://docs.python.org/3/reference/datamodel.html)
* Python Magic Classes

## Example Module File

Attribution
* [RichardBronosky PEP8 Cheatsheet](https://gist.github.com/RichardBronosky/454964087739a449da04)

```python
"""This module's multi-line docstring.
Paragraphs are separated with blank lines.
Lines conform to 79 character rule.
1234567891011121314151617181920212223242526272829303132333435363738394041424344
"""


import standard_library  # STD lib imports first, alphabetical

import third_party_library  # 3rd party library imports next, alphabetical

import local_library  # local library imports last
import library_one, library_two  # anti-pattern
from library import *  # anti-pattern, including pyflake problem # noqa
# Using # noqa in the line above avoids flake8 warnings about line length!


# 2 empty lines between top-level functions + classes
def new_function(): # snake_case
    """Description"""
    action
    

class NewClass(object): #CapWords
    """Description"""

    def __init__(self, attribute):
        self.attribute = attribute

    # 1 empty line between in-class definitions
    def new_method(self): # snake_class, always use self as first argument
        """Description"""
        action

    @classmethod
    def new_class_method(cls):
        """Description"""
        action

# Newline at end of file
```

## Reserved Keywords

<!--
(See Python Crash Course “Python Keywords and Built-in Functions” on page 489.)

Keywords!
https://docs.python.org/3/reference/lexical_analysis.html#keywords
-->

```python
class
def
```

```python
try
except
raise
assert
```

```python
for
while
else
if
elif
with
```

```python
continue
pass
break
```

Boolean

```python
True
False
```

```python
and
not
or
```

```python
import
from
```

```python
global
nonlocal
```

```python
async
await
```

```python
None
as
del
finally
in
is
lambda
return
yield
```

## Arguments and Parameters

Difference between kwargs and zip

Information passed to a function is called an argument
information received by a function is called a parameter.

Interpreter
2.1.1. Argument Passing
https://docs.python.org/3/tutorial/interpreter.html#argument-passing
sys.argv[0]

4.7.1. Default Argument Values
https://docs.python.org/3/tutorial/controlflow.html#default-argument-values
4.7.2. Keyword Arguments
https://docs.python.org/3/tutorial/controlflow.html#keyword-arguments
4.7.3. Arbitrary Argument Lists
https://docs.python.org/3/tutorial/controlflow.html#arbitrary-argument-lists
4.7.4. Unpacking Argument Lists
https://docs.python.org/3/tutorial/controlflow.html#unpacking-argument-lists

positional, keyword
https://docs.python.org/3/glossary.html#term-argument
https://docs.python.org/3/glossary.html#term-parameter

## Python Code Block Examples

<!--
See also: exceptions and pass statement
-->

Python structuring
* colons
* indentation (a.k.a. nesting)

## Colons

Python structures that end blocks with a colon (:)
* function statement
* class statement
* if-elif-else statement (branching)
* for-else statement (loop)
* while-else statement (loop)
* with statement
* try-except-else statement

Python structures that don't end blocks with a colon (:)
* range/list comprehension functions

Compound or complex statements

```python
header: 
   suite
header:
   suite 
header:
   suite
```

## Class or Function Syntax

Define a function or class

```python
def function():
class Class:
```

Function statement

```python
def function():
    """Description"""
    action

function()
```

Class statement

```python
class Class:
    """Description"""
    def __init__(self, attribute):
        self.attribute = attribute
 
    def method(self):
        action
```
           
## Control Flow Statement Examples

if-elif-else statement

```python
if condition true:
    action
elif condition true:
    action
else:
    action
```

for-else statement

```python
for condition:
    action
else:
    action
```

while-else statement

```python
while condition true:
    action
else:
    action
```

with statement

```python
with condition:
```

with-else statement

```python

```

## Django System Checks, Error Reporting, Exceptions

* [Django System Checks](https://docs.djangoproject.com/en/dev/topics/checks)
* [Django Error Reporting](https://docs.djangoproject.com/en/dev/howto/error-reporting)
* [Django Exceptions](https://docs.djangoproject.com/en/dev/ref/exceptions)

<!--
https://docs.djangoproject.com/en/2.1/topics/testing/tools/#transactiontestcase

Django Core Exceptions
AppRegistryNotReady, 1014
ObjectDoesNotExist, 1015 
EmptyResultSet, 1015 
FieldDoesNotExist, 1015 
MultipleObjectsReturned, 1015 
SuspiciousOperation, 1015 
PermissionDenied, 1016 
ViewDoesNotExist, 1016 
MiddlewareNotUsed, 1016 
ImproperlyConfigured, 1016 
FieldError, 1016 
ValidationError, 1016 
NON_FIELD_ERRORS

URL Resolver exceptions
Resolver404
NoReverseMatch, 1017 

Database Exceptions

Http Exceptions
UnreadablePostError, 1018 

Transaction Exceptions
TransactionManagementError, 1018 

Testing Framework Exceptions
RedirectCycleError

Python Exceptions


## Django Errors and Exceptions

DoesNotExist
Model.DoesNotExist, 1155
TemplateDoesNotExist, 276 

Django Errors
PageNotAnInteger, 507 
ContextPopException, 1376 
EmptyPage, 507 

Errors
IntegrityError, 1017 
InterfaceError, 1017 
InternalError, 1017 
models.ProtectedError, 1017 
OperationalError, 1017 
NotSupportedError, 1017 
CommandError, 545 
DatabaseError, 1017 
DataError, 1017 
Error, 1017 
client.RedirectCycleError, 1018  
ProgrammingError, 1017 
TemplateSyntaxError, 276 
-->
   
## Exceptions

Two kinds of errors
* syntax errors
* logical errors

Traceback
* 1: file name, line number, module (if applicable)
* 2: line, ^ (caret) where the error is
* 3: type of error and description
     
Example

```python
$ python program.py
  File "program.py", line 3, in <module>
print 'Hello world! ^
SyntaxError: EOL while scanning string literal
```

try-except-else statement

```python
try:
    something
except Exception:
    do something else
else:
    do something else
```

<!--
8.4. The try statement
https://docs.python.org/3/reference/compound_stmts.html#the-try-statement
https://docs.python.org/3/reference/compound_stmts.html#finally

7.8. The raise statement
https://docs.python.org/3/reference/simple_stmts.html#the-raise-statement
-->

## Python Built-In Exceptions Hierarchy

<!--
The most common exceptions?
-->

Django raises built-in Python exceptions when appropriate.
https://docs.python.org/3/library/exceptions.html#bltin-exceptions

5.4. Exception hierarchy
https://docs.python.org/3/library/exceptions.html#exception-hierarchy

BaseException
  +-- Exception
      +-- StopIteration
      +-- StopAsyncIteration
      
 +-- SystemExit
 +-- KeyboardInterrupt
 +-- GeneratorExit
 
      +-- ImportError
      |    +-- ModuleNotFoundError
      
      +-- SyntaxError
      |    +-- IndentationError
      |         +-- TabError
      
      +-- NameError
      |    +-- UnboundLocalError
      
      +-- TypeError
      +-- ValueError
      |    +-- UnicodeError
      |         +-- UnicodeDecodeError
      |         +-- UnicodeEncodeError
      |         +-- UnicodeTranslateError
      
      +-- AttributeError 
      
      +-- LookupError
      |    +-- IndexError
      |    +-- KeyError
      
      +-- ArithmeticError
      |    +-- FloatingPointError
      |    +-- OverflowError
      |    +-- ZeroDivisionError
      
      +-- EOFError
      
      +-- AssertionError
              
      +-- ReferenceError
      
      +-- OSError
      |    +-- BlockingIOError
      |    +-- ChildProcessError
      |    +-- ConnectionError
      |    |    +-- BrokenPipeError
      |    |    +-- ConnectionAbortedError
      |    |    +-- ConnectionRefusedError
      |    |    +-- ConnectionResetError
      |    +-- FileExistsError
      |    +-- FileNotFoundError
      |    +-- InterruptedError
      |    +-- IsADirectoryError
      |    +-- NotADirectoryError
      |    +-- PermissionError
      |    +-- ProcessLookupError
      |    +-- TimeoutError    
      
      +-- SystemError
      
      +-- RuntimeError
      |    +-- NotImplementedError
      |    +-- RecursionError
      
      +-- MemoryError     
      +-- BufferError
               
Python Warnings

      +-- Warning

           +-- SyntaxWarning
           +-- UserWarning
           +-- ImportWarning
	   
           +-- UnicodeWarning
           +-- BytesWarning
	   
           +-- RuntimeWarning
           +-- ResourceWarning
	   
           +-- FutureWarning	   
           +-- DeprecationWarning
           +-- PendingDeprecationWarning
           
	  
## Collections

collections- mutability?

8.3. collections — Container datatypes
https://docs.python.org/3/library/collections.html

"alternatives to Python’s general purpose built-in containers, dict, list, set, and tuple."

Container datatypes
* namedtuple()
* deque
* ChainMap
* Counter
* OrderedDict (see example)
* defaultdict
* UserDict
* UserList
* UserString

Abstract Base Classes for Containers
* collections.abc

https://docs.python.org/3/library/collections.html#collections.namedtuple	
https://docs.python.org/3/library/collections.html#collections.OrderedDict	

https://docs.python.org/3/library/collections.html#chainmap-objects
https://docs.python.org/3/library/collections.html#chainmap-examples-and-recipes
https://docs.python.org/3/library/collections.html#counter-objects
https://docs.python.org/3/library/collections.html#deque-objects
https://docs.python.org/3/library/collections.html#deque-recipes
https://docs.python.org/3/library/collections.html#defaultdict-objects
https://docs.python.org/3/library/collections.html#defaultdict-examples
https://docs.python.org/3/library/collections.html#namedtuple-factory-function-for-tuples-with-named-fields
https://docs.python.org/3/library/collections.html#ordereddict-objects
https://docs.python.org/3/library/collections.html#ordereddict-examples-and-recipes
https://docs.python.org/3/library/collections.html#userdict-objects
https://docs.python.org/3/library/collections.html#userlist-objects
https://docs.python.org/3/library/collections.html#userstring-objects

https://docs.python.org/3/glossary.html#term-abstract-base-class

8.4. collections.abc — Abstract Base Classes for Containers
https://docs.python.org/3/library/collections.abc.html
https://docs.python.org/3/library/collections.abc.html#collections-abstract-base-classes

29.7. abc — Abstract Base Classes
https://docs.python.org/3/library/abc.html


## Python and Django Control Flow

3 Types of Control structures
* true or false branch evaluation (if statement)
* repeating while a condition is True (while loop)
* sequential processing (for loop)

## if Statements

Conditional test
* evaluates statements one by one until one is found to be True (Boolean operation)
* that statement is executed (no other part of if statement is executed or evaluated)
* if all statements are False, else statement, if present, is executed

Number of statements
* can have as many elif statement as needed
* else statement is always optional

https://docs.python.org/3/tutorial/controlflow.html#if-statements
https://docs.python.org/3/reference/compound_stmts.html#the-if-statement

## while Statements

Conditional test
* repeats a block of code while the condition is True (Boolean operation)
* if the condition does not become False, the loop runs indefinitely as an infinite loop.
* if the while statements becomes False, the else statement, if present, is executed

https://docs.python.org/3/reference/compound_stmts.html#the-while-statement

## Sequences

Sequence Types — list, tuple, range, string

Sequence Types — list, tuple, range, string
https://docs.python.org/3/library/stdtypes.html#sequence-types-list-tuple-range
https://docs.python.org/3/library/stdtypes.html#textseq
https://docs.python.org/3/library/stdtypes.html#string-methods

immutable
https://docs.python.org/3/library/stdtypes.html#immutable-sequence-types
mutable
https://docs.python.org/3/library/stdtypes.html#mutable-sequence-types

mutable and immutable
https://docs.python.org/3/library/stdtypes.html#common-sequence-operations

https://docs.python.org/3/reference/expressions.html#subscriptions

Range
https://docs.python.org/3/reference/expressions.html#slicings

List, dictionaries, etc. 
https://docs.python.org/3/tutorial/datastructures.html#the-del-statement
https://docs.python.org/3/reference/simple_stmts.html#the-del-statement

Not common
https://docs.python.org/3/library/stdtypes.html#binaryseq

## Iterators

Difference between Sequences, Iterators, Iterables
https://stackoverflow.com/questions/9884132/what-exactly-are-iterator-iterable-and-iteration

Iterators
https://www.python.org/dev/peps/pep-0234/

string, list, tuple dict, set, or other iterator

4.5. Iterator Types
https://docs.python.org/3/library/stdtypes.html#iterator-types

5.6. Looping Techniques
https://docs.python.org/3/tutorial/datastructures.html#looping-techniques

## Built-In Functions- Data Sequence/Iterator

Return an iterator object. 

```iter()```

https://docs.python.org/3/library/functions.html#iter

Retrieve the next item from the iterator by calling its __next__() method. 

```next()```

Construct an iterator from those elements of iterable for which function returns true. 

```filter()```

Return True if all elements of the iterable are true (or if the iterable is empty). 

```all()```	

Return True if any element of the iterable is true. If the iterable is empty, return False. 

```any()```

Return a reverse iterator. 

```reversed()```

Return a new sorted list from the items in iterable.

```sorted()```

https://docs.python.org/3/library/functions.html#reversed
https://docs.python.org/3/library/functions.html#sorted

## Built-In Looping Functions- Data Sequence/Iterator

Return an enumerate object. iterable must be a sequence, an iterator, or some other object which supports iteration. 

```enumerate()```

https://docs.python.org/3/library/functions.html#enumerate

8.13. enum — Support for enumerations
https://docs.python.org/3/library/enum.html
https://docs.python.org/3/library/enum.html#module-contents
https://docs.python.org/3/library/enum.html#creating-an-enum
https://docs.python.org/3/library/enum.html#programmatic-access-to-enumeration-members-and-their-attributes
https://docs.python.org/3/library/enum.html#duplicating-enum-members-and-values
https://docs.python.org/3/library/enum.html#ensuring-unique-enumeration-values
https://docs.python.org/3/library/enum.html#using-automatic-values
https://docs.python.org/3/library/enum.html#iteration
https://docs.python.org/3/library/enum.html#comparisons
https://docs.python.org/3/library/enum.html#allowed-members-and-attributes-of-enumerations
https://docs.python.org/3/library/enum.html#restricted-subclassing-of-enumerations
https://docs.python.org/3/library/enum.html#pickling
https://docs.python.org/3/library/enum.html#functional-api
https://docs.python.org/3/library/enum.html#derived-enumerations
https://docs.python.org/3/library/enum.html#intenum
https://docs.python.org/3/library/enum.html#intflag
https://docs.python.org/3/library/enum.html#flag
https://docs.python.org/3/library/enum.html#others
https://docs.python.org/3/library/enum.html#interesting-examples
https://docs.python.org/3/library/enum.html#omitting-values
https://docs.python.org/3/library/enum.html#orderedenum
https://docs.python.org/3/library/enum.html#duplicatefreeenum
https://docs.python.org/3/library/enum.html#planet
https://docs.python.org/3/library/enum.html#timeperiod
https://docs.python.org/3/library/enum.html#how-are-enums-different
https://docs.python.org/3/library/enum.html#enum-classes
https://docs.python.org/3/library/enum.html#enum-members-aka-instances
https://docs.python.org/3/library/enum.html#finer-points

Make an iterator that aggregates elements from each of the iterables. Returns an iterator of tuples

```zip()```

https://docs.python.org/3/library/functions.html#zip

## for Statements

What it does
* iterates over the items of any sequence in the order in which they appear in the sequence
* when all iteration has been completed, the else statement, if present, is executed

https://docs.python.org/3/tutorial/controlflow.html#for-statements
https://docs.python.org/3/reference/compound_stmts.html#the-for-statement

## break and continue Statements (for or while Loops), and else Clauses on Loops

4.4. break and continue Statements, and else Clauses on Loops
https://docs.python.org/3/tutorial/controlflow.html#break-and-continue-statements-and-else-clauses-on-loops

"The break statement breaks out of the innermost enclosing for or while loop."

7.9. The break statement
https://docs.python.org/3/reference/simple_stmts.html#the-break-statement

"The continue statement continues with the next iteration of the (for or while) loop."

7.10. The continue statement
https://docs.python.org/3/reference/simple_stmts.html#the-continue-statement

## pass Statements

Nothing happens when the pass statement executes.

null operation
4.5. pass Statements
https://docs.python.org/3/tutorial/controlflow.html#pass-statements
7.4. The pass statement
https://docs.python.org/3/reference/simple_stmts.html#the-pass-statement

## range() Function (for Statement for Numbers)

What it does
* iterates over a sequence of numbers

How
* starts at 0 by default
* stops one number below the number passed to it

https://en.wikipedia.org/wiki/Increment_and_decrement_operators

https://docs.python.org/3/library/stdtypes.html#ranges

4.3. The range() Function
https://docs.python.org/3/tutorial/controlflow.html#the-range-function

## Built-In Functions- Range

Return a slice object representing the set of indices specified by range(start, stop, step). See itertools.islice() for an alternate version that returns an iterator.

```slice()```

https://docs.python.org/3.7/library/itertools.html#itertools.islice

## for Statement Alternatives

* list comprehension
* map function
* generator expressions

## List Comprehensions (range function)

What it does
* a more efficient way to do a for loop

Two Types of Listed Comprehensions
* List Comprehensions
* Nested List Comprehensions

5.1.3. List Comprehensions
https://docs.python.org/3/tutorial/datastructures.html#list-comprehensions

## Nested List Comprehensions

matrix?
5.1.4. Nested List Comprehensions
https://docs.python.org/3/tutorial/datastructures.html#nested-list-comprehensions

## Built-In Function- ```map()```

Return an iterator that applies function to every item of iterable, yielding the results. see itertools.starmap().

```map()```

https://docs.python.org/3/library/functions.html#map
https://docs.python.org/3/library/itertools.html#itertools.starmap

## Generators

https://docs.python.org/3/glossary.html#term-generator

Types
https://docs.python.org/3/library/stdtypes.html#iterator-types
https://docs.python.org/3/library/stdtypes.html#generator-types

Classes
9.8. Iterators
https://docs.python.org/3/tutorial/classes.html#iterators
9.9. Generators
https://docs.python.org/3/tutorial/classes.html#generators
9.10. Generator Expressions
https://docs.python.org/3/tutorial/classes.html#generator-expressions

## Generator Expression

https://docs.python.org/3/glossary.html#term-generator-expression

https://docs.python.org/3/reference/expressions.html#generator-expressions

## Asynchronous Generator

https://docs.python.org/3/reference/expressions.html#asynchronous-generator-functions
https://docs.python.org/3/reference/expressions.html#asynchronous-generator-iterator-methods

## Generator Iterator

https://docs.python.org/3/glossary.html#term-generator-iterator
https://docs.python.org/3/reference/expressions.html#generator-iterator-methods
https://docs.python.org/3/reference/expressions.html#examples

## yield Statements (used with a generator function or asynchronous generator function)

https://docs.python.org/3/reference/expressions.html#yield-expressions

7.7. The yield statement
https://docs.python.org/3/reference/simple_stmts.html#the-yield-statement

## Coroutines

async/await
Similar to generator iterator

https://docs.python.org/3/reference/datamodel.html#coroutines
https://docs.python.org/3/reference/compound_stmts.html#coroutines

https://docs.python.org/3/reference/expressions.html#await-expression

https://docs.python.org/3/reference/compound_stmts.html#coroutine-function-definition
https://docs.python.org/3/reference/compound_stmts.html#the-async-for-statement
https://docs.python.org/3/reference/compound_stmts.html#the-async-with-statement

Data Model
https://docs.python.org/3/reference/datamodel.html#awaitable-objects
https://docs.python.org/3/reference/datamodel.html#coroutine-objects
https://docs.python.org/3/reference/datamodel.html#asynchronous-iterators
https://docs.python.org/3/reference/datamodel.html#asynchronous-context-managers

## Built-In Looping Functions- Dictionary

dictionary views
"The objects returned by dict.keys(), dict.values() and dict.items() are view objects. They provide a dynamic view on the dictionary’s entries, which means that when the dictionary changes, the view reflects these changes."
https://docs.python.org/3/library/stdtypes.html#dictionary-view-objects

Dictionaries

```items()```

https://docs.python.org/3/library/stdtypes.html#dict.items

More dictionary helpers
* try statement
* get method
* dict.setdefault
* collections.defaultdict

Dictionary alternatives
https://docs.python.org/3/reference/compound_stmts.html#try
https://wiki.python.org/moin/KeyError

https://docs.python.org/3/library/stdtypes.html#dict.get

https://docs.python.org/3/library/stdtypes.html#dict.setdefault
https://docs.python.org/3/library/collections.html#collections.defaultdict

## Lambda Expressions

4.7.5. Lambda Expressions
https://docs.python.org/3/tutorial/controlflow.html#lambda-expressions
6.13. Lambdas
https://docs.python.org/3/reference/expressions.html#lambda

## with Statements

8.5. The with statement
https://docs.python.org/3/reference/compound_stmts.html#the-with-statement

https://docs.python.org/3/reference/compound_stmts.html#with

4.11. Context Manager Types
https://docs.python.org/3/library/stdtypes.html#context-manager-types

https://docs.python.org/3/reference/datamodel.html#context-managers

30.7. contextlib — Utilities for with-statement contexts

https://docs.python.org/3/library/contextlib.html
https://docs.python.org/3/library/contextlib.html#utilities
https://docs.python.org/3/library/contextlib.html#examples-and-recipes
https://docs.python.org/3/library/contextlib.html#supporting-a-variable-number-of-context-managers
https://docs.python.org/3/library/contextlib.html#catching-exceptions-from-enter-methods
https://docs.python.org/3/library/contextlib.html#cleaning-up-in-an-enter-implementation
https://docs.python.org/3/library/contextlib.html#replacing-any-use-of-try-finally-and-flag-variables
https://docs.python.org/3/library/contextlib.html#using-a-context-manager-as-a-function-decorator
https://docs.python.org/3/library/contextlib.html#single-use-reusable-and-reentrant-context-managers
https://docs.python.org/3/library/contextlib.html#reentrant-context-managers
https://docs.python.org/3/library/contextlib.html#reusable-context-managers

## Functional Programming: itertools, functools, and operator

"The functions fall into categories that perform object comparisons, logical operations, mathematical operations and sequence operations."

Functional programming modules
* itertools
* functools
* operator

10. Functional Programming Modules
10.1. itertools — Functions creating iterators for efficient looping
10.2. functools — Higher-order functions and operations on callable objects
10.3. operator — Standard operators as functions

https://docs.python.org/3/library/functional.html

https://docs.python.org/3/library/itertools.html
https://docs.python.org/3/library/itertools.html#itertool-functions
https://docs.python.org/3/library/itertools.html#itertools-recipes

https://docs.python.org/3/library/itertools.html#itertools.chain

https://docs.python.org/3/library/functools.html
https://docs.python.org/3/library/functools.html#partial-objects


## Object-Oriented Programming

### Built-In Object Methods

Return a new featureless object. object is a base for all classes. It has the methods that are common to all instances of Python classes. 

```object()```

Return a proxy object that delegates method calls to a parent or sibling class of type. This is useful for accessing inherited methods that have been overridden in a class. 

```super()```

https://docs.python.org/3/library/functions.html#super | 2. Built-in Functions — Python 3.6.3 documentation

### Class and Object `Is` Functions

Return true if the object argument is an instance of the classinfo argument, or of a (direct, indirect or virtual) subclass thereof. 

```isinstance()```

https://docs.python.org/3/library/numbers.html#implementing-the-arithmetic-operations

Return true if class is a subclass (direct, indirect or virtual) of classinfo. 

```issubclass()```

### Attributes and Properties

Object attributes

```delattr()```
```getattr()```
```__getattribute__()```
```hasattr()```
```setattr()```

https://en.wikipedia.org/wiki/Mutator_method
https://docs.python.org/3/library/functions.html#setattr
https://docs.python.org/3/library/functions.html#getattr
https://docs.python.org/3/library/functions.html#hasattr
https://docs.python.org/3/library/functions.html#delattr
https://en.wikipedia.org/wiki/Property_(programming)

Return a property attribute.
```property()```
