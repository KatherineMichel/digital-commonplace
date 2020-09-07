# Python Doc Notes

## General Notes

<!--
https://codeinplace2020.github.io/faqs/7-Functions.pdf | 7-Functions

https://realpython.com/python-sockets/ | Socket Programming in Python (Guide) – Real Python
https://realpython.com/working-with-files-in-python/ | Working With Files in Python – Real Python
https://realpython.com/python-gui-with-wxpython/ | How to Build a Python GUI Application With wxPython – Real Python
https://www.pypy.org/ | PyPy

HTMl and CSS
https://developer.mozilla.org/en-US/docs/Web/HTML/Element | HTML elements reference - HTML: Hypertext Markup Language | MDN
https://developer.mozilla.org/en-US/docs/Web/CSS | CSS: Cascading Style Sheets | MDN

https://twitter.com/unclebobmartin/status/1010660993851117569 | Uncle Bob Martin on Twitter: "Programs are made up of Dijkstra’s three structures: Sequence, Selection, and Iteration. Each of these is based upon jumps. Sequential statements jump from the end of the first to be beginning of the second."

https://stackoverflow.com/questions/373419/whats-the-difference-between-passing-by-reference-vs-passing-by-value | language agnostic - What's the difference between passing by reference vs. passing by value? - Stack Overflow
https://developer.mozilla.org/en-US/docs/Glossary/Parameter | Parameter - MDN Web Docs Glossary: Definitions of Web-related terms | MDN
-->

## Best Practices and Common Tools

<!--
https://en.wikipedia.org/wiki/Decomposition | Decomposition - Wikipedia

https://en.wikipedia.org/wiki/Call_stack | Call stack - Wikipedia
frame object - Google Search
https://docs.python.org/3/library/inspect.html#the-interpreter-stack

https://en.wikipedia.org/wiki/Random-access_memory | Random-access memory - Wikipedia

https://en.wikipedia.org/wiki/Backward_compatibility | Backward compatibility - Wikipedia

https://en.wikipedia.org/wiki/Scope_(computer_science) | Scope (computer science) - Wikipedia
https://en.wikipedia.org/wiki/Namespace | Namespace - Wikipedia
https://en.wikipedia.org/wiki/Metaclass | Metaclass - Wikipedia

https://en.wikipedia.org/wiki/Snake_case | Snake case - Wikipedia

https://www.google.com/search?q=Extended-BNF+(EBNF)&oq=Extended-BNF+(EBNF)&aqs=chrome..69i57.234j0j7&sourceid=chrome&ie=UTF-8 | Extended-BNF (EBNF) - Google Search

http://pythontutor.com/visualize.html#mode=edit | Visualize Python, Java, JavaScript, C, C++, Ruby code execution

https://docs.python.org/3/c-api/
https://docs.python.org/3/c-api/stable.html | Stable Application Binary Interface — Python 3.8.3 documentation
https://docs.python.org/3.8/extending/extending.html

https://www.python.org/dev/peps/pep-0384/ | PEP 384 -- Defining a Stable ABI | Python.org

https://docs.python.org/3/glossary.html | Glossary — Python 3.8.3 documentation

https://docs.python.org/3/library/python.html
https://docs.python.org/3/py-modindex.html | Python Module Index — Python 3.8.3 documentation

https://docs.python.org/3/tutorial/modules.html#standard-modules | 6. Modules — Python 3.8.5 documentation
https://docs.python.org/3/library/functions.html#open | Built-in Functions — Python 3.8.5 documentation

https://docs.python.org/3/library/markup.html | Structured Markup Processing Tools — Python 3.8.3 documentation

Kenneth Reitz Advice to Me 
* Python Object Model, [Python Data Model Docs](https://docs.python.org/3/reference/datamodel.html)
* Python Magic Classes

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

Super
https://docs.python.org/2/library/functions.html#super | 2. Built-in Functions — Python 2.7.16 documentation

https://docs.python.org/3/library/dis.html | 404 Not Found
https://docs.python.org/3/library/dis.html#python-bytecode-instructions | dis — Disassembler for Python bytecode — Python 3.8.2rc1 documentation


https://www.python.org/dev/peps/pep-0008/#indentation | PEP 8 -- Style Guide for Python Code | Python.org

https://en.wikipedia.org/wiki/Self-documenting_code | Self-documenting code - Wikipedia

https://docs.python.org/3/library/doctest.html | doctest — Test interactive Python examples — Python 3.8.3 documentation
https://docs.python.org/3/tutorial/controlflow.html#documentation-strings | 4. More Control Flow Tools — Python 3.8.3 documentation


https://www.python.org/dev/peps/pep-0484/ | PEP 484 -- Type Hints | Python.org

https://docs.python.org/3.8/library/types.html | types — Dynamic type creation and names for built-in types — Python 3.8.3 documentation

https://docs.python.org/3/library/constants.html#None | Built-in Constants — Python 3.8.3 documentation

https://docs.python.org/3/library/exceptions.html#TypeError | Built-in Exceptions — Python 3.8.3 documentation
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypeError | TypeError - JavaScript | MDN
https://docs.python.org/3/library/exceptions.html#NameError | Built-in Exceptions — Python 3.8.3 documentation
https://docs.python.org/3/library/exceptions.html#ValueError | Built-in Exceptions — Python 3.8.3 documentation
https://eli.thegreenplace.net/2011/05/15/understanding-unboundlocalerror-in-python/ | Understanding UnboundLocalError in Python - Eli Bendersky's website


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

https://en.wikipedia.org/wiki/Increment_and_decrement_operators

https://en.wikipedia.org/wiki/George_Boole#Death | George Boole - Wikipedia
https://en.wikipedia.org/wiki/Pseudorandomness | Pseudorandomness - Wikipedia

https://en.wikipedia.org/wiki/Concatenation | Concatenation - Wikipedia

negative indexes python - Google Search

https://docs.python.org/3/library/os.html | os — Miscellaneous operating system interfaces — Python 3.8.5 documentation
https://docs.python.org/3/library/sys.html#module-sys | sys — System-specific parameters and functions — Python 3.8.5 documentation

https://docs.python.org/3/library/argparse.html | argparse — Parser for command-line options, arguments and sub-commands — Python 3.8.5 documentation
https://docs.python.org/3/howto/argparse.html | Argparse Tutorial — Python 3.8.5 documentation

Strings
https://docs.python.org/3.4/library/string.html | 6.1. string — Common string operations — Python 3.4.10 documentation
https://docs.python.org/3.3/library/stdtypes.html?highlight=split#str.split | 4. Built-in Types — Python 3.3.7 documentation

https://realpython.com/python-f-strings/ | Python 3's f-Strings: An Improved String Formatting Syntax (Guide) – Real Python
https://docs.python.org/3/reference/lexical_analysis.html#f-strings | 2. Lexical analysis — Python 3.8.3 documentation

https://docs.python.org/3.9/library/random.html | random — Generate pseudo-random numbers — Python 3.9.0a5 documentation
https://docs.python.org/3/library/math.html | math — Mathematical functions — Python 3.8.2 documentation

https://docs.python.org/3/library/fileformats.html | File Formats — Python 3.8.3 documentation
https://docs.python.org/3/tutorial/stdlib.html#file-wildcards | 10. Brief Tour of the Standard Library — Python 3.8.5 documentation

Regular expression
https://en.wikipedia.org/wiki/Regular_expression | Regular expression - Wikipedia
https://docs.python.org/3/library/re.html | re — Regular expression operations — Python 3.8.3 documentation
https://en.wikipedia.org/wiki/Regular_expression | Regular expression - Wikipedia

https://docs.python.org/3/library/pathlib.html | pathlib — Object-oriented filesystem paths — Python 3.8.3 documentation
https://docs.python.org/3/library/pathlib.html#pathlib.Path.replace | pathlib — Object-oriented filesystem paths — Python 3.8.5 documentation

urllib
https://docs.python.org/3/library/urllib.request.html | urllib.request — Extensible library for opening URLs — Python 3.8.3 documentation
https://docs.python.org/3/howto/urllib2.html | HOWTO Fetch Internet Resources Using The urllib Package — Python 3.8.3 documentation
https://docs.python.org/2/library/urllib.html#urllib.urlretrieve | 20.5. urllib — Open arbitrary resources by URL — Python 2.7.18 documentation
https://docs.python.org/3/library/urllib.parse.html | urllib.parse — Parse URLs into components — Python 3.8.3 documentation
-->

<!--
## Grammar

Some of this will be deprecated

1.2. Notation
https://docs.python.org/3/reference/introduction.html#notation

https://docs.python.org/3/tutorial/controlflow.html#intermezzo-coding-style


https://twitter.com/aaronchall/status/1114713624453554176

http://akaptur.com/blog/2014/03/16/reading-ebnf/ | Reading EBNF - Allison Kaptur
https://en.wikipedia.org/wiki/Extended_Backus%E2%80%93Naur_form | Extended Backus–Naur form - Wikipedia
https://en.wikipedia.org/wiki/Backus%E2%80%93Naur_form	
https://www.iso.org/standard/26153.html | ISO/IEC 14977:1996 - Information technology -- Syntactic metalanguage -- Extended BNF
https://standards.iso.org/ittf/PubliclyAvailableStandards/s026153_ISO_IEC_14977_1996(E).zip | Publicly Available Standards
-->

## Interpreter

2. Using the Python Interpreter
2.1. Invoking the Interpreter
2.1.1. Argument Passing
2.1.2. Interactive Mode
2.2. The Interpreter and Its Environment
2.2.1. Source Code Encoding

https://docs.python.org/3/tutorial/interpreter.html
https://docs.python.org/3/tutorial/interpreter.html#invoking-the-interpreter
https://docs.python.org/3/tutorial/interpreter.html#argument-passing
https://docs.python.org/3/using/cmdline.html#using-on-general

https://docs.python.org/3/tutorial/interpreter.html#interactive-mode
https://docs.python.org/3/tutorial/interpreter.html#the-interpreter-and-its-environment
https://docs.python.org/3/tutorial/interpreter.html#source-code-encoding

14. Interactive Input Editing and History Substitution
https://docs.python.org/3/tutorial/interactive.html#interactive-input-editing-and-history-substitution
14.1. Tab Completion and History Editing
https://docs.python.org/3/tutorial/interactive.html#tab-completion-and-history-editing
14.2. Alternatives to the Interactive Interpreter
https://docs.python.org/3/tutorial/interactive.html#alternatives-to-the-interactive-interpreter


31. Custom Python Interpreters
31.1. code — Interpreter base classes
31.2. codeop — Compile Python code

Not There
https://docs.python.org/3/library/custominterp.html#custom-python-interpreters
https://docs.python.org/3/library/code.html#module-code
https://docs.python.org/3/library/code.html#interactive-interpreter-objects
https://docs.python.org/3/library/code.html#interactive-console-objects
https://docs.python.org/3/library/codeop.html#module-codeop


## Packages and Importing

29.4. __main__ — Top-level script environment
5.7. Special considerations for __main__
https://docs.python.org/3/library/__main__.html
https://docs.python.org/3/reference/import.html#special-considerations-for-main

https://docs.python.org/3/installing/index.html

https://docs.python.org/3/distributing/index.html

Old
29.1. distutils — Building and installing Python modules
https://docs.python.org/3/library/distutils.html

https://docs.python.org/3/reference/simple_stmts.html#the-import-statement
https://docs.python.org/3/tutorial/modules.html
https://docs.python.org/3/tutorial/modules.html#packages
https://docs.python.org/3/library/modules.html
https://docs.python.org/3/library/distribution.html

https://docs.python.org/3/tutorial/modules.html#modules
https://docs.python.org/3/tutorial/modules.html#more-on-modules
https://docs.python.org/3/tutorial/modules.html#executing-modules-as-scripts
https://docs.python.org/3/tutorial/modules.html#the-module-search-path
https://docs.python.org/3/tutorial/modules.html#compiled-python-files
https://docs.python.org/3/tutorial/modules.html#packages
https://docs.python.org/3/tutorial/modules.html#importing-from-a-package
https://docs.python.org/3/tutorial/modules.html#intra-package-references
https://docs.python.org/3/tutorial/modules.html#packages-in-multiple-directories

https://docs.python.org/3/reference/import.html
https://docs.python.org/3/reference/import.html#importlib
https://docs.python.org/3/reference/import.html#packages

https://docs.python.org/3/reference/import.html#regular-packages
https://docs.python.org/3/reference/import.html#namespace-packages

https://docs.python.org/3/reference/import.html#searching

https://docs.python.org/3/reference/import.html#the-module-cache
https://docs.python.org/3/reference/import.html#finders-and-loaders
https://docs.python.org/3/reference/import.html#import-hooks
https://docs.python.org/3/reference/import.html#the-meta-path

https://docs.python.org/3/reference/import.html#loading

https://docs.python.org/3/reference/import.html#loaders
https://docs.python.org/3/reference/import.html#submodules
https://docs.python.org/3/reference/import.html#module-spec
https://docs.python.org/3/reference/import.html#import-related-module-attributes
https://docs.python.org/3/reference/import.html#module-path
https://docs.python.org/3/reference/import.html#module-reprs
https://docs.python.org/3/reference/import.html#cached-bytecode-invalidation

https://docs.python.org/3/reference/import.html#the-path-based-finder

https://docs.python.org/3/reference/import.html#path-entry-finders
https://docs.python.org/3/reference/import.html#path-entry-finder-protocol

https://docs.python.org/3/reference/import.html#replacing-the-standard-import-system
https://docs.python.org/3/reference/import.html#special-considerations-for-main

https://docs.python.org/3/reference/import.html#main-spec

5.8. Open issues
https://docs.python.org/3/reference/import.html#open-issues
5.9. References
https://docs.python.org/3/reference/import.html#references

https://docs.python.org/3/library/importlib.html
https://docs.python.org/3/library/importlib.html#introduction
https://docs.python.org/3/library/importlib.html#functions
https://docs.python.org/3/library/importlib.html#module-importlib.abc
https://docs.python.org/3/library/importlib.html#module-importlib.resources
https://docs.python.org/3/library/importlib.html#module-importlib.machinery
https://docs.python.org/3/library/importlib.html#module-importlib.util
https://docs.python.org/3/library/importlib.html#examples
https://docs.python.org/3/library/importlib.html#importing-programmatically
https://docs.python.org/3/library/importlib.html#checking-if-a-module-can-be-imported
https://docs.python.org/3/library/importlib.html#importing-a-source-file-directly
https://docs.python.org/3/library/importlib.html#setting-up-an-importer
https://docs.python.org/3/library/importlib.html#approximating-importlib-import-module

9. Top-level components
9.1. Complete Python programs
9.2. File input
9.3. Interactive input
9.4. Expression input

https://docs.python.org/3/reference/toplevel_components.html
https://docs.python.org/3/reference/toplevel_components.html#complete-python-programs
https://docs.python.org/3/reference/toplevel_components.html#file-input
https://docs.python.org/3/reference/toplevel_components.html#interactive-input
https://docs.python.org/3/reference/toplevel_components.html#expression-input

32. Importing Modules
32.2. pkgutil — Package extension utility
32.3. modulefinder — Find modules used by a script
32.4. runpy — Locating and executing Python modules
32.5. importlib — The implementation of import

https://docs.python.org/3/library/pkgutil.html
https://docs.python.org/3/library/modulefinder.html
https://docs.python.org/3/library/modulefinder.html#example-usage-of-modulefinder
https://docs.python.org/3/library/runpy.html

32.1. zipimport — Import modules from Zip archives
https://docs.python.org/3/library/zipimport.html
https://docs.python.org/3/library/zipimport.html#zipimporter-objects
https://docs.python.org/3/library/zipimport.html#examples

29.2. ensurepip — Bootstrapping the pip installer
https://docs.python.org/3/library/ensurepip.html
https://docs.python.org/3/library/ensurepip.html#command-line-interface
https://docs.python.org/3/library/ensurepip.html#module-api


## General Links

https://docs.python.org/3/glossary.html

https://docs.python.org/3/contents.html
https://docs.python.org/3/genindex.html
https://docs.python.org/3/py-modindex.html

https://docs.python.org/2/howto/doanddont.html

https://docs.python.org/3/reference/index.html
https://docs.python.org/3/reference/introduction.html

https://docs.python.org/3/library
https://docs.python.org/3/library/index.html
https://docs.python.org/3/library/intro.html

13. What Now?
https://docs.python.org/3/tutorial/whatnow.html#what-now

## Tutorial

3. An Informal Introduction to Python
https://docs.python.org/3/tutorial/introduction.html
https://docs.python.org/3/tutorial/introduction.html#an-informal-introduction-to-python
https://docs.python.org/3/tutorial/introduction.html#using-python-as-a-calculator
https://docs.python.org/3/tutorial/introduction.html#numbers
https://docs.python.org/3/tutorial/introduction.html#strings
https://docs.python.org/3/library/stdtypes.html#textseq
https://docs.python.org/3/library/stdtypes.html#string-methods
https://docs.python.org/3/reference/lexical_analysis.html#f-strings
Fibonacci series 
https://docs.python.org/3/tutorial/introduction.html#first-steps-towards-programming

1. Whetting Your Appetite
https://docs.python.org/3/tutorial/appetite.html

https://docs.python.org/3/tutorial/appendix.html
https://docs.python.org/3/tutorial/appendix.html#appendix

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

https://docs.python.org/3/tutorial/stdlib.html
10. Brief Tour of the Standard Library
https://docs.python.org/3/tutorial/stdlib.html#brief-tour-of-the-standard-library
11. Brief Tour of the Standard Library — Part II
https://docs.python.org/3/tutorial/stdlib2.html

10. Brief Tour of the Standard Library
https://docs.python.org/3/tutorial/stdlib.html#brief-tour-of-the-standard-library

10.1. Operating System Interface
https://docs.python.org/3/library/os.html#module-os
https://docs.python.org/3/tutorial/stdlib.html#operating-system-interface
https://docs.python.org/3/library/os.html#os.open
https://docs.python.org/3/library/os.path.html#module-os.path
https://docs.python.org/3/library/os.path.html#os.path.join
https://docs.python.org/3/library/shutil.html#module-shutil
10.2. File Wildcards
https://docs.python.org/3/tutorial/stdlib.html#file-wildcards
https://docs.python.org/3/library/glob.html#module-glob
10.3. Command Line Arguments
https://docs.python.org/3/tutorial/stdlib.html#command-line-arguments
https://docs.python.org/3/library/sys.html#module-sys

10.4. Error Output Redirection and Program Termination
https://docs.python.org/3/tutorial/stdlib.html#error-output-redirection-and-program-termination
https://docs.python.org/3/library/sys.html#module-sys
https://docs.python.org/3/library/sys.html#sys.argv
https://docs.python.org/3/library/sys.html#sys.path
10.5. String Pattern Matching
https://docs.python.org/3/tutorial/stdlib.html#string-pattern-matching
https://docs.python.org/3/library/re.html#module-re
10.6. Mathematics
https://docs.python.org/3/tutorial/stdlib.html#mathematics
https://docs.python.org/3/library/random.html#module-random
10.7. Internet Access
https://docs.python.org/3/tutorial/stdlib.html#internet-access
https://docs.python.org/3/library/urllib.request.html#module-urllib.request
https://docs.python.org/3/library/smtplib.html#module-smtplib
10.8. Dates and Times
https://docs.python.org/3/tutorial/stdlib.html#dates-and-times
https://docs.python.org/3/library/datetime.html#module-datetime
10.9. Data Compression
https://docs.python.org/3/tutorial/stdlib.html#data-compression
10.10. Performance Measurement
https://docs.python.org/3/tutorial/stdlib.html#performance-measurement
https://docs.python.org/3/library/profile.html#module-profile
https://docs.python.org/3/library/timeit.html#module-timeit
https://docs.python.org/3/library/profile.html#module-pstats
10.11. Quality Control
https://docs.python.org/3/tutorial/stdlib.html#quality-control
10.12. Batteries Included
https://docs.python.org/3/tutorial/stdlib.html#batteries-included
https://docs.python.org/3/library/xmlrpc.client.html#module-xmlrpc.client
https://docs.python.org/3/library/xmlrpc.server.html#module-xmlrpc.server
https://docs.python.org/3/library/email.html#module-email
https://docs.python.org/3/library/smtplib.html#module-smtplib
https://docs.python.org/3/library/poplib.html#module-poplib
https://docs.python.org/3/library/json.html#module-json
https://docs.python.org/3/library/csv.html#module-csv
https://docs.python.org/3/library/xml.etree.elementtree.html#module-xml.etree.ElementTree
https://docs.python.org/3/library/xml.dom.html#module-xml.dom
https://docs.python.org/3/library/xml.sax.html#module-xml.sax
https://docs.python.org/3/library/sqlite3.html#module-sqlite3

11. Brief Tour of the Standard Library — Part II
https://docs.python.org/3/tutorial/stdlib2.html#brief-tour-of-the-standard-library-part-ii

11.1. Output Formatting
https://docs.python.org/3/tutorial/stdlib2.html#output-formatting
https://docs.python.org/3/library/functions.html#repr
https://docs.python.org/3/library/pprint.html#module-pprint
11.2. Templating
https://docs.python.org/3/tutorial/stdlib2.html#templating
https://docs.python.org/3/library/string.html#module-string
https://docs.python.org/3/library/string.html#string.Template
11.3. Working with Binary Data Record Layouts
https://docs.python.org/3/tutorial/stdlib2.html#working-with-binary-data-record-layouts
11.4. Multi-threading
https://docs.python.org/3/tutorial/stdlib2.html#multi-threading
https://docs.python.org/3/library/threading.html#module-threading
https://docs.python.org/3/library/queue.html#module-queue
https://docs.python.org/3/library/queue.html#queue.Queue
11.5. Logging
https://docs.python.org/3/tutorial/stdlib2.html#logging
https://docs.python.org/3/library/logging.html#module-logging
11.6. Weak References
https://docs.python.org/3/tutorial/stdlib2.html#weak-references
https://docs.python.org/3/glossary.html#term-garbage-collection
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



## General Stuff

30.11. __future__ — Future statement definitions
https://docs.python.org/3/library/__future__.html
https://docs.python.org/3/reference/simple_stmts.html#future-statements

https://docs.python.org/3/reference/executionmodel.html
https://docs.python.org/3/library/functions.html#eval
https://docs.python.org/3/library/functions.html#exec

https://docs.python.org/3/reference/executionmodel.html#structure-of-a-program
https://docs.python.org/3/reference/executionmodel.html#naming-and-binding

https://docs.python.org/3/reference/executionmodel.html#binding-of-names
https://docs.python.org/3/reference/executionmodel.html#resolution-of-names
https://docs.python.org/3/reference/executionmodel.html#builtins-and-restricted-execution
https://docs.python.org/3/library/__main__.html#module-__main__

https://docs.python.org/3/reference/executionmodel.html#interaction-with-dynamic-features

https://docs.python.org/3/reference/executionmodel.html#exceptions

https://docs.python.org/3/library/functions.html#built-in-funcs
https://docs.python.org/3/library/constants.html#built-in-consts
https://docs.python.org/3/library/functions.html#open


https://docs.python.org/3/library/stdtypes.html#the-ellipsis-object

4.7.6. Documentation Strings
https://docs.python.org/3/tutorial/controlflow.html#documentation-strings

12.4. marshal — Internal Python object serialization
https://docs.python.org/3/library/marshal.html


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


## Python and Django Testing

27.2. pydoc — Documentation generator and online help system
https://docs.python.org/3/library/pydoc.html

27.3. doctest — Test interactive Python examples
https://docs.python.org/3/library/doctest.html
https://docs.python.org/3/library/doctest.html#simple-usage-checking-examples-in-docstrings
https://docs.python.org/3/library/doctest.html#simple-usage-checking-examples-in-a-text-file
https://docs.python.org/3/library/doctest.html#how-it-works
https://docs.python.org/3/library/doctest.html#which-docstrings-are-examined
https://docs.python.org/3/library/doctest.html#how-are-docstring-examples-recognized
https://docs.python.org/3/library/doctest.html#what-s-the-execution-context
https://docs.python.org/3/library/doctest.html#what-about-exceptions
https://docs.python.org/3/library/doctest.html#option-flags
https://docs.python.org/3/library/doctest.html#directives
https://docs.python.org/3/library/doctest.html#warnings
https://docs.python.org/3/library/doctest.html#basic-api
https://docs.python.org/3/library/doctest.html#unittest-api
https://docs.python.org/3/library/doctest.html#advanced-api
https://docs.python.org/3/library/doctest.html#doctest-objects
https://docs.python.org/3/library/doctest.html#example-objects
https://docs.python.org/3/library/doctest.html#doctestfinder-objects
https://docs.python.org/3/library/doctest.html#doctestparser-objects
https://docs.python.org/3/library/doctest.html#doctestrunner-objects
https://docs.python.org/3/library/doctest.html#outputchecker-objects
https://docs.python.org/3/library/doctest.html#debugging
https://docs.python.org/3/library/doctest.html#soapbox
-->

## Performance

36.11. resource — Resource usage information
https://docs.python.org/3/library/resource.html
https://docs.python.org/3/library/resource.html#resource-limits
https://docs.python.org/3/library/resource.html#resource-usage

## Debugging and Profiling

https://pypi.org/project/ipdb/ | ipdb · PyPI

28. Debugging and Profiling
28.3. pdb — The Python Debugger
28.1. bdb — Debugger framework
28.2. faulthandler — Dump the Python traceback
28.4. The Python Profilers
28.5. timeit — Measure execution time of small code snippets
28.6. trace — Trace or track Python statement execution
28.7. tracemalloc — Trace memory allocations

https://docs.python.org/3/library/debug.html

https://docs.python.org/3/library/pdb.html#debugger-commands

https://docs.python.org/3/library/faulthandler.html
https://docs.python.org/3/library/faulthandler.html#dumping-the-traceback
https://docs.python.org/3/library/faulthandler.html#fault-handler-state
https://docs.python.org/3/library/faulthandler.html#dumping-the-tracebacks-after-a-timeout
https://docs.python.org/3/library/faulthandler.html#dumping-the-traceback-on-a-user-signal
https://docs.python.org/3/library/faulthandler.html#issue-with-file-descriptors
https://docs.python.org/3/library/faulthandler.html#example

https://docs.python.org/3/library/profile.html
https://docs.python.org/3/library/profile.html#introduction-to-the-profilers
https://docs.python.org/3/library/profile.html#instant-user-s-manual
https://docs.python.org/3/library/profile.html#module-cProfile
https://docs.python.org/3/library/profile.html#the-stats-class
https://docs.python.org/3/library/profile.html#what-is-deterministic-profiling
https://docs.python.org/3/library/profile.html#limitations
https://docs.python.org/3/library/profile.html#calibration
https://docs.python.org/3/library/profile.html#using-a-custom-timer

https://docs.python.org/3/library/timeit.html
https://docs.python.org/3/library/timeit.html#basic-examples
https://docs.python.org/3/library/timeit.html#python-interface
https://docs.python.org/3/library/timeit.html#command-line-interface
https://docs.python.org/3/library/timeit.html#examples

https://docs.python.org/3/library/trace.html
https://docs.python.org/3/library/trace.html#command-line-usage
https://docs.python.org/3/library/trace.html#main-options
https://docs.python.org/3/library/trace.html#modifiers
https://docs.python.org/3/library/trace.html#filters
https://docs.python.org/3/library/trace.html#programmatic-interface

29.9. traceback — Print or retrieve a stack traceback
https://docs.python.org/3/library/traceback.html
https://docs.python.org/3/library/traceback.html#tracebackexception-objects
https://docs.python.org/3/library/traceback.html#stacksummary-objects
https://docs.python.org/3/library/traceback.html#framesummary-objects
https://docs.python.org/3/library/traceback.html#traceback-examples

https://docs.python.org/3/library/tracemalloc.html
https://docs.python.org/3/library/tracemalloc.html#examples
https://docs.python.org/3/library/tracemalloc.html#display-the-top-10
https://docs.python.org/3/library/tracemalloc.html#compute-differences
https://docs.python.org/3/library/tracemalloc.html#get-the-traceback-of-a-memory-block
https://docs.python.org/3/library/tracemalloc.html#pretty-top
https://docs.python.org/3/library/tracemalloc.html#api
https://docs.python.org/3/library/tracemalloc.html#functions
https://docs.python.org/3/library/tracemalloc.html#domainfilter
https://docs.python.org/3/library/tracemalloc.html#filter
https://docs.python.org/3/library/tracemalloc.html#frame
https://docs.python.org/3/library/tracemalloc.html#snapshot
https://docs.python.org/3/library/tracemalloc.html#statistic
https://docs.python.org/3/library/tracemalloc.html#statisticdiff
https://docs.python.org/3/library/tracemalloc.html#trace
https://docs.python.org/3/library/tracemalloc.html#traceback

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

https://docs.python.org/3/library/exceptions.html#warnings
https://docs.python.org/3/library/exceptions.html#exception-hierarchy

https://docs.python.org/3/library/exceptions.html#os-exceptions

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
-->

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
     
## Built-In Exceptions Hierarchy

The most common exceptions?

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
	   
## Logging

Logging HOWTO
https://docs.python.org/3/howto/logging.html

Logging Cookbook
https://docs.python.org/3/howto/logging-cookbook.html

11.5. Logging
https://docs.python.org/3/tutorial/stdlib2.html#logging

https://docs.python.org/3/library/logging.html
https://docs.python.org/3/library/logging.html#logger-objects
https://docs.python.org/3/library/logging.html#logging-levels
https://docs.python.org/3/library/logging.html#handler-objects
https://docs.python.org/3/library/logging.html#formatter-objects
https://docs.python.org/3/library/logging.html#filter-objects
https://docs.python.org/3/library/logging.html#logrecord-objects
https://docs.python.org/3/library/logging.html#logrecord-attributes
https://docs.python.org/3/library/logging.html#loggeradapter-objects
https://docs.python.org/3/library/logging.html#thread-safety
https://docs.python.org/3/library/logging.html#module-level-functions
https://docs.python.org/3/library/logging.html#module-level-attributes
https://docs.python.org/3/library/logging.html#integration-with-the-warnings-module

https://docs.python.org/3/library/logging.config.html
https://docs.python.org/3/library/logging.config.html#configuration-functions
https://docs.python.org/3/library/logging.config.html#configuration-dictionary-schema
https://docs.python.org/3/library/logging.config.html#dictionary-schema-details
https://docs.python.org/3/library/logging.config.html#incremental-configuration
https://docs.python.org/3/library/logging.config.html#object-connections
https://docs.python.org/3/library/logging.config.html#user-defined-objects
https://docs.python.org/3/library/logging.config.html#access-to-external-objects
https://docs.python.org/3/library/logging.config.html#access-to-internal-objects
https://docs.python.org/3/library/logging.config.html#import-resolution-and-custom-importers
https://docs.python.org/3/library/logging.config.html#configuration-file-format

https://docs.python.org/3/library/logging.handlers.html
https://docs.python.org/3/library/logging.handlers.html#streamhandler
https://docs.python.org/3/library/logging.handlers.html#filehandler
https://docs.python.org/3/library/logging.handlers.html#nullhandler
https://docs.python.org/3/library/logging.handlers.html#watchedfilehandler
https://docs.python.org/3/library/logging.handlers.html#baserotatinghandler
https://docs.python.org/3/library/logging.handlers.html#rotatingfilehandler
https://docs.python.org/3/library/logging.handlers.html#timedrotatingfilehandler
https://docs.python.org/3/library/logging.handlers.html#sockethandler
https://docs.python.org/3/library/logging.handlers.html#datagramhandler
https://docs.python.org/3/library/logging.handlers.html#sysloghandler
https://docs.python.org/3/library/logging.handlers.html#nteventloghandler
https://docs.python.org/3/library/logging.handlers.html#smtphandler
https://docs.python.org/3/library/logging.handlers.html#memoryhandler
https://docs.python.org/3/library/logging.handlers.html#httphandler
https://docs.python.org/3/library/logging.handlers.html#queuehandler
https://docs.python.org/3/library/logging.handlers.html#queuelistener


## virtualenv

12. Virtual Environments and Packages
12.1. Introduction
12.2. Creating Virtual Environments
12.3. Managing Packages with pip

29.3. venv — Creation of virtual environments

https://docs.python.org/3/library/venv.html

https://docs.python.org/3/tutorial/venv.html#virtual-environments-and-packages
https://docs.python.org/3/tutorial/venv.html#introduction
https://docs.python.org/3/tutorial/venv.html#creating-virtual-environments
https://docs.python.org/3/tutorial/venv.html#managing-packages-with-pip

https://docs.python.org/3/library/venv.html#api
https://docs.python.org/3/library/venv.html#an-example-of-extending-envbuilder

## 2 to 3- Deprecated

Automated Python 2 to 3 code translation
https://docs.python.org/3/library/2to3.html
https://docs.python.org/3/library/2to3.html#using-2to3
https://docs.python.org/3/library/2to3.html#fixers
https://docs.python.org/3/library/2to3.html#module-lib2to3




## Built-In Functions- Modules

This function is invoked by the import statement. It can be replaced (by importing the builtins module and assigning to builtins.__import__) in order to change semantics of the import statement, but doing so is strongly discouraged
```__import__()```


## Mapping Operators to Functions

Mapping Operators to Functions

"For backward compatibility, many of these have a variant with the double underscores kept."
https://docs.python.org/3/library/operator.html
https://docs.python.org/3/library/operator.html#module-operator
https://docs.python.org/3/library/operator.html#mapping-operators-to-functions
https://docs.python.org/3/library/operator.html#inplace-operators


## Formatting

8.12. reprlib — Alternate repr() implementation
https://docs.python.org/3/library/reprlib.html
https://docs.python.org/3/library/reprlib.html#repr-objects
https://docs.python.org/3/library/reprlib.html#subclassing-repr-objects

https://docs.python.org/3/tutorial/inputoutput.html#manual-string-formatting

7.1.1. Old string formatting
https://docs.python.org/3/tutorial/inputoutput.html#the-string-format-method
https://docs.python.org/3/tutorial/inputoutput.html#old-string-formatting
https://docs.python.org/3/library/stdtypes.html#printf-style-string-formatting

f-string
https://docs.python.org/3/whatsnew/3.6.html#whatsnew36-pep498
https://docs.python.org/3/glossary.html#term-f-string
https://docs.python.org/3/reference/lexical_analysis.html#f-strings
https://docs.python.org/3/tutorial/inputoutput.html#formatted-string-literals

8.11. pprint — Data pretty printer
https://docs.python.org/3/library/pprint.html
https://docs.python.org/3/library/pprint.html#prettyprinter-objects
https://docs.python.org/3/library/pprint.html#example

20. Structured Markup Processing Tools
https://docs.python.org/3/library/markup.html
20.1. html — HyperText Markup Language support
https://docs.python.org/3/library/html.html

7.1. Fancier Output Formatting
https://docs.python.org/3/tutorial/inputoutput.html#fancier-output-formatting

11.1. Output Formatting
https://docs.python.org/3/tutorial/stdlib2.html#output-formatting
10.4. Error Output Redirection and Program Termination
https://docs.python.org/3/tutorial/stdlib.html#error-output-redirection-and-program-termination

11.2. Templating
https://docs.python.org/3/tutorial/stdlib2.html#templating
11.3. Working with Binary Data Record Layouts
https://docs.python.org/3/tutorial/stdlib2.html#working-with-binary-data-record-layouts

34.1. formatter — Generic output formatting
https://docs.python.org/3/library/formatter.html
https://docs.python.org/3/library/formatter.html#the-formatter-interface
https://docs.python.org/3/library/formatter.html#formatter-implementations
https://docs.python.org/3/library/formatter.html#the-writer-interface
https://docs.python.org/3/library/formatter.html#writer-implementations

## Built-In Functions for Formatting and Printing

Convert a value to a “formatted” representation, as controlled by format_spec. 
```format()```

Return a string containing a printable representation of an object. 
```repr()```




<!--
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
-->

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


## Scope

Scope
* [Scope Wikipedia](https://en.wikipedia.org/wiki/Scope_(computer_science))

<!--
https://en.wikipedia.org/wiki/Scope_(computer_science)#Lexical_scope_vs._dynamic_scope
-->

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

<!--
Return a dictionary representing the current global symbol table. 
```globals()```

Update and return a dictionary representing the current local symbol table. 
```locals()```
-->


## Built-In Functions- ```eval()``` and ```exec()```

```eval()```

This function supports dynamic execution of Python code. 
```exec()```

Compile the source into a code or AST object. 
```compile()```

## Dataclasses

https://docs.python.org/3/library/dataclasses.html#module-level-decorators-classes-and-functions
https://docs.python.org/3/library/dataclasses.html#post-init-processing
https://docs.python.org/3/library/dataclasses.html#class-variables
https://docs.python.org/3/library/dataclasses.html#init-only-variables
https://docs.python.org/3/library/dataclasses.html#frozen-instances
https://docs.python.org/3/library/dataclasses.html#inheritance
https://docs.python.org/3/library/dataclasses.html#default-factory-functions
https://docs.python.org/3/library/dataclasses.html#mutable-default-values
https://docs.python.org/3/library/dataclasses.html#exceptions


## Print Data Structure and Ascertain Data Type

```python
print(data_structure)
print(type(data_structure))
```

## dir() and builtins

Without arguments, return the list of names in the current local scope. With an argument, attempt to return a list of valid attributes for that object.

```dir()```

dir() does not list the names of built-in functions and variables. Tthey are defined in the standard module builtins.

```python
>>> import builtins
>>> dir(builtins)
```

6.3. The dir() Function
https://docs.python.org/3/tutorial/modules.html#the-dir-function
https://docs.python.org/3/library/functions.html#dir

Return True if the object argument appears callable, False if not. 
```callable()```



## Utilities

10.3. Command Line Arguments
https://docs.python.org/3/tutorial/stdlib.html#command-line-arguments

16.5. getopt — C-style parser for command line options
Not There
https://docs.python.org/3/library/getopt.html

https://docs.python.org/3/library/allos.html

16.14. platform — Access to underlying platform’s identifying data
https://docs.python.org/3/library/platform.html
https://docs.python.org/3/library/platform.html#cross-platform
https://docs.python.org/3/library/platform.html#java-platform
https://docs.python.org/3/library/platform.html#windows-platform
https://docs.python.org/3/library/platform.html#mac-os-platform

10.1. Operating System Interface
https://docs.python.org/3/tutorial/stdlib.html#operating-system-interface

16.1. os — Miscellaneous operating system interfaces
https://docs.python.org/3/library/os.html
https://docs.python.org/3/library/os.html#file-names-command-line-arguments-and-environment-variables
https://docs.python.org/3/library/os.html#process-parameters
https://docs.python.org/3/library/os.html#file-object-creation
https://docs.python.org/3/library/os.html#file-descriptor-operations
https://docs.python.org/3/library/os.html#querying-the-size-of-a-terminal
https://docs.python.org/3/library/os.html#inheritance-of-file-descriptors
https://docs.python.org/3/library/os.html#files-and-directories
https://docs.python.org/3/library/os.html#linux-extended-attributes
https://docs.python.org/3/library/os.html#process-management
https://docs.python.org/3/library/os.html#interface-to-the-scheduler
https://docs.python.org/3/library/os.html#miscellaneous-system-information
https://docs.python.org/3/library/os.html#random-numbers

11.2. os.path — Common pathname manipulations
https://docs.python.org/3/library/os.path.html

29.1. sys — System-specific parameters and functions
https://docs.python.org/3/library/sys.html
https://docs.python.org/3/library/sys.html#sys.argv
https://docs.python.org/3/library/sys.html#sys.path
https://docs.python.org/3/library/sys.html#sys.stdin
https://docs.python.org/3/library/sys.html#sys.stdout
https://docs.python.org/3/library/sys.html#sys.stderr

30.2. sysconfig — Provide access to Python’s configuration information
https://docs.python.org/3/library/sysconfig.html
https://docs.python.org/3/library/sysconfig.html#configuration-variables
https://docs.python.org/3/library/sysconfig.html#installation-paths
https://docs.python.org/3/library/sysconfig.html#other-functions
https://docs.python.org/3/library/sysconfig.html#using-sysconfig-as-a-script

11.1. pathlib — Object-oriented filesystem paths
https://docs.python.org/3/library/pathlib.html

https://docs.python.org/3/library/pathlib.html#basic-use
https://docs.python.org/3/library/pathlib.html#pure-paths
https://docs.python.org/3/library/pathlib.html#general-properties
https://docs.python.org/3/library/pathlib.html#operators
https://docs.python.org/3/library/pathlib.html#accessing-individual-parts
https://docs.python.org/3/library/pathlib.html#methods-and-properties
https://docs.python.org/3/library/pathlib.html#concrete-paths
https://docs.python.org/3/library/pathlib.html#methods
chart
https://docs.python.org/3/library/pathlib.html#correspondence-to-tools-in-the-os-module

https://docs.python.org/3/howto/argparse.html

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

11.10. shutil — High-level file operations
https://docs.python.org/3/library/shutil.html
https://docs.python.org/3/library/shutil.html#directory-and-files-operations
https://docs.python.org/3/library/shutil.html#copytree-example
https://docs.python.org/3/library/shutil.html#rmtree-example
https://docs.python.org/3/library/shutil.html#archiving-operations
https://docs.python.org/3/library/shutil.html#archiving-example
https://docs.python.org/3/library/shutil.html#querying-the-size-of-the-output-terminal

HOWTO Fetch Internet Resources Using The urllib Package
https://docs.python.org/3/howto/urllib2.html

22.5. urllib — URL handling modules
22.6. urllib.request — Extensible library for opening URLs
22.7. urllib.response — Response classes used by urllib
22.8. urllib.parse — Parse URLs into components
22.9. urllib.error — Exception classes raised by urllib.request
22.10. urllib.robotparser — Parser for robots.txt

https://docs.python.org/3/library/urllib.html
https://docs.python.org/3/library/urllib.request.html
https://docs.python.org/3/library/urllib.request.html#request-objects
https://docs.python.org/3/library/urllib.request.html#openerdirector-objects
https://docs.python.org/3/library/urllib.request.html#basehandler-objects
https://docs.python.org/3/library/urllib.request.html#httpredirecthandler-objects
https://docs.python.org/3/library/urllib.request.html#httpcookieprocessor-objects
https://docs.python.org/3/library/urllib.request.html#proxyhandler-objects
https://docs.python.org/3/library/urllib.request.html#httppasswordmgr-objects
https://docs.python.org/3/library/urllib.request.html#httppasswordmgrwithpriorauth-objects
https://docs.python.org/3/library/urllib.request.html#abstractbasicauthhandler-objects
https://docs.python.org/3/library/urllib.request.html#httpbasicauthhandler-objects
https://docs.python.org/3/library/urllib.request.html#proxybasicauthhandler-objects
https://docs.python.org/3/library/urllib.request.html#abstractdigestauthhandler-objects
https://docs.python.org/3/library/urllib.request.html#httpdigestauthhandler-objects
https://docs.python.org/3/library/urllib.request.html#proxydigestauthhandler-objects
https://docs.python.org/3/library/urllib.request.html#httphandler-objects
https://docs.python.org/3/library/urllib.request.html#httpshandler-objects
https://docs.python.org/3/library/urllib.request.html#filehandler-objects
https://docs.python.org/3/library/urllib.request.html#datahandler-objects
https://docs.python.org/3/library/urllib.request.html#ftphandler-objects
https://docs.python.org/3/library/urllib.request.html#cacheftphandler-objects
https://docs.python.org/3/library/urllib.request.html#unknownhandler-objects
https://docs.python.org/3/library/urllib.request.html#httperrorprocessor-objects
https://docs.python.org/3/library/urllib.request.html#examples
https://docs.python.org/3/library/urllib.request.html#legacy-interface
https://docs.python.org/3/library/urllib.request.html#urllib-request-restrictions
https://docs.python.org/3/library/urllib.request.html#module-urllib.response

https://docs.python.org/3/library/urllib.parse.html
https://docs.python.org/3/library/urllib.parse.html#url-parsing
https://docs.python.org/3/library/urllib.parse.html#parsing-ascii-encoded-bytes
https://docs.python.org/3/library/urllib.parse.html#structured-parse-results
https://docs.python.org/3/library/urllib.parse.html#url-quoting

"The module has been designed to match the Internet RFC on Relative Uniform Resource Locators. It supports the following URL schemes: file, ftp, gopher, hdl, http, https, imap, mailto, mms, news, nntp, prospero, rsync, rtsp, rtspu, sftp, shttp, sip, sips, snews, svn, svn+ssh, telnet, wais, ws, wss."

https://docs.python.org/3/library/urllib.error.html#module-urllib.error
https://docs.python.org/3/library/urllib.robotparser.html#module-urllib.robotparser

16.2. io — Core tools for working with streams
https://docs.python.org/3/library/io.html
https://docs.python.org/3/library/io.html#overview
https://docs.python.org/3/library/io.html#text-i-o
https://docs.python.org/3/library/io.html#binary-i-o
https://docs.python.org/3/library/io.html#raw-i-o
https://docs.python.org/3/library/io.html#high-level-module-interface
https://docs.python.org/3/library/io.html#in-memory-streams
https://docs.python.org/3/library/io.html#class-hierarchy
https://docs.python.org/3/library/io.html#i-o-base-classes
https://docs.python.org/3/library/io.html#raw-file-i-o
https://docs.python.org/3/library/io.html#buffered-streams
https://docs.python.org/3/library/io.html#id1
https://docs.python.org/3/library/io.html#performance
https://docs.python.org/3/library/io.html#id2
https://docs.python.org/3/library/io.html#id3
https://docs.python.org/3/library/io.html#multi-threading
https://docs.python.org/3/library/io.html#reentrancy

16.3. time — Time access and conversions
https://docs.python.org/3/library/time.html
https://docs.python.org/3/library/time.html#functions
https://docs.python.org/3/library/time.html#clock-id-constants
https://docs.python.org/3/library/time.html#timezone-constants

8.1. datetime — Basic date and time types
https://docs.python.org/3/library/datetime.html
https://docs.python.org/3/library/datetime.html#available-types
https://docs.python.org/3/library/datetime.html#timedelta-objects
https://docs.python.org/3/library/datetime.html#date-objects
https://docs.python.org/3/library/datetime.html#datetime-objects
https://docs.python.org/3/library/datetime.html#time-objects
https://docs.python.org/3/library/datetime.html#tzinfo-objects
https://docs.python.org/3/library/datetime.html#timezone-objects
https://docs.python.org/3/library/datetime.html#strftime-and-strptime-behavior

8.2. calendar — General calendar-related functions
https://docs.python.org/3/library/calendar.html

6. Text Processing Services
https://docs.python.org/3/library/text.html

6.1. string — Common string operations
https://docs.python.org/3/library/string.html#module-string
https://docs.python.org/3/library/string.html#string-constants
https://docs.python.org/3/library/string.html#custom-string-formatting
https://docs.python.org/3/library/string.html#format-string-syntax
https://docs.python.org/3/library/string.html#format-specification-mini-language
https://docs.python.org/3/library/string.html#format-examples
https://docs.python.org/3/library/string.html#template-strings
https://docs.python.org/3/library/string.html#helper-functions

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

Unicode HOWTO
https://docs.python.org/3/howto/unicode.html

7. Input and Output
https://docs.python.org/3/tutorial/inputoutput.html
https://docs.python.org/3/tutorial/inputoutput.html#methods-of-file-objects
https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files
https://docs.python.org/3/library/functions.html#open

30.14. site — Site-specific configuration hook
https://docs.python.org/3/library/site.html
https://docs.python.org/3/library/site.html#readline-configuration
https://docs.python.org/3/library/site.html#module-contents

22.1. webbrowser — Convenient Web-browser controller

https://docs.python.org/3/library/webbrowser.html
https://docs.python.org/3/library/webbrowser.html#browser-controller-objects

22.11. http — HTTP modules
22.12. http.client — HTTP protocol client

22.22. http.server — HTTP servers
22.23. http.cookies — HTTP state management
22.24. http.cookiejar — Cookie handling for HTTP clients

https://docs.python.org/3/library/http.html

https://docs.python.org/3/library/http.html#http-status-codes

https://docs.python.org/3/library/http.client.html
https://docs.python.org/3/library/http.client.html#httpconnection-objects
https://docs.python.org/3/library/http.client.html#httpresponse-objects
https://docs.python.org/3/library/http.client.html#examples
https://docs.python.org/3/library/http.client.html#httpmessage-objects

https://docs.python.org/3/library/http.server.html
https://docs.python.org/3/library/http.cookies.html
https://docs.python.org/3/library/http.cookies.html#cookie-objects
https://docs.python.org/3/library/http.cookies.html#morsel-objects
https://docs.python.org/3/library/http.cookies.html#example
https://docs.python.org/3/library/http.cookiejar.html
https://docs.python.org/3/library/http.cookiejar.html#cookiejar-and-filecookiejar-objects
https://docs.python.org/3/library/http.cookiejar.html#filecookiejar-subclasses-and-co-operation-with-web-browsers
https://docs.python.org/3/library/http.cookiejar.html#cookiepolicy-objects
https://docs.python.org/3/library/http.cookiejar.html#defaultcookiepolicy-objects
https://docs.python.org/3/library/http.cookiejar.html#cookie-objects
https://docs.python.org/3/library/http.cookiejar.html#examples

20.1. email — An email and MIME handling package

https://docs.python.org/3/library/email.html
https://docs.python.org/3/library/email.message.html#module-email.message
https://docs.python.org/3/library/email.parser.html
https://docs.python.org/3/library/email.parser.html#feedparser-api
https://docs.python.org/3/library/email.parser.html#parser-api
https://docs.python.org/3/library/email.parser.html#additional-notes
https://docs.python.org/3/library/email.generator.html
https://docs.python.org/3/library/email.policy.html
https://docs.python.org/3/library/email.errors.html
https://docs.python.org/3/library/email.headerregistry.html
https://docs.python.org/3/library/email.contentmanager.html
https://docs.python.org/3/library/email.contentmanager.html
https://docs.python.org/3/library/email.examples.html#email-examples
https://docs.python.org/3/library/email.compat32-message.html
https://docs.python.org/3/library/email.mime.html
https://docs.python.org/3/library/email.header.html
https://docs.python.org/3/library/email.charset.html
https://docs.python.org/3/library/email.encoders.html
https://docs.python.org/3/library/email.util.html
https://docs.python.org/3/library/email.iterators.html

22.13. ftplib — FTP protocol client
22.14. poplib — POP3 protocol client
22.15. imaplib — IMAP4 protocol client
22.16. nntplib — NNTP protocol client
22.17. smtplib — SMTP protocol client
22.18. smtpd — SMTP Server
22.19. telnetlib — Telnet client
22.20. uuid — UUID objects according to RFC 4122

https://docs.python.org/3/library/ftplib.html
https://docs.python.org/3/library/ftplib.html#ftp-objects
https://docs.python.org/3/library/ftplib.html#ftp-tls-objects

https://docs.python.org/3/library/poplib.html
https://docs.python.org/3/library/poplib.html#pop3-objects
https://docs.python.org/3/library/poplib.html#pop3-example

https://docs.python.org/3/library/imaplib.html
https://docs.python.org/3/library/imaplib.html#imap4-objects
https://docs.python.org/3/library/imaplib.html#imap4-example

https://docs.python.org/3/library/nntplib.html
https://docs.python.org/3/library/nntplib.html#nntp-objects
https://docs.python.org/3/library/nntplib.html#attributes
https://docs.python.org/3/library/nntplib.html#methods
https://docs.python.org/3/library/nntplib.html#utility-functions

https://docs.python.org/3/library/smtplib.html
https://docs.python.org/3/library/smtplib.html#smtp-objects
https://docs.python.org/3/library/smtplib.html#smtp-example
https://docs.python.org/3/library/smtpd.html
https://docs.python.org/3/library/smtpd.html#smtpserver-objects
https://docs.python.org/3/library/smtpd.html#debuggingserver-objects
https://docs.python.org/3/library/smtpd.html#pureproxy-objects
https://docs.python.org/3/library/smtpd.html#mailmanproxy-objects
https://docs.python.org/3/library/smtpd.html#smtpchannel-objects

https://docs.python.org/3/library/telnetlib.html
https://docs.python.org/3/library/telnetlib.html#telnet-objects
https://docs.python.org/3/library/telnetlib.html#telnet-example

https://docs.python.org/3/library/uuid.html
https://docs.python.org/3/library/uuid.html#example

20.3. mailcap — Mailcap file handling
20.4. mailbox — Manipulate mailboxes in various formats

https://docs.python.org/3/library/mailcap.html

https://docs.python.org/3/library/mailbox.html
https://docs.python.org/3/library/mailbox.html#mailbox-objects
https://docs.python.org/3/library/mailbox.html#maildir
https://docs.python.org/3/library/mailbox.html#mbox
https://docs.python.org/3/library/mailbox.html#mh
https://docs.python.org/3/library/mailbox.html#babyl
https://docs.python.org/3/library/mailbox.html#mmdf
https://docs.python.org/3/library/mailbox.html#message-objects
https://docs.python.org/3/library/mailbox.html#maildirmessage
https://docs.python.org/3/library/mailbox.html#mboxmessage
https://docs.python.org/3/library/mailbox.html#babylmessage
https://docs.python.org/3/library/mailbox.html#mmdfmessage
https://docs.python.org/3/library/mailbox.html#exceptions
https://docs.python.org/3/library/mailbox.html#examples

21. Internet Protocols and Support

21.11. http — HTTP modules
19.2. json — JSON encoder and decoder
7.2.2. Saving structured data with json

https://docs.python.org/3/library/http.server.html
https://docs.python.org/3/library/http.html
https://docs.python.org/3/library/json.html
https://docs.python.org/3/tutorial/inputoutput.html#saving-structured-data-with-json

20.2. json — JSON encoder and decoder

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

21. Structured Markup Processing Tools
21.1. html — HyperText Markup Language support
21.2. html.parser — Simple HTML and XHTML parser
21.3. html.entities — Definitions of HTML general entities

https://docs.python.org/3/library/markup.html
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

11.4. stat — Interpreting stat() results
https://docs.python.org/3/library/stat.html

11.3. fileinput — Iterate over lines from multiple input streams
11.5. filecmp — File and Directory Comparisons
11.6. tempfile — Generate temporary files and directories
11.8. fnmatch — Unix filename pattern matching
11.9. linecache — Random access to text lines
11.11. macpath — Mac OS 9 path manipulation functions

https://docs.python.org/3/library/filesys.html

https://docs.python.org/3/library/fileinput.html

https://docs.python.org/3/library/filecmp.html
https://docs.python.org/3/library/filecmp.html#the-dircmp-class
https://docs.python.org/3/library/tempfile.html
https://docs.python.org/3/library/tempfile.html#examples
https://docs.python.org/3/library/tempfile.html#deprecated-functions-and-variables

https://docs.python.org/3/library/fnmatch.html
https://docs.python.org/3/library/linecache.html

https://docs.python.org/3/library/macpath.html

22.28. ipaddress — IPv4/IPv6 manipulation library
https://docs.python.org/3/library/ipaddress.html
https://docs.python.org/3/library/ipaddress.html#convenience-factory-functions
https://docs.python.org/3/library/ipaddress.html#ip-addresses
https://docs.python.org/3/library/ipaddress.html#address-objects
https://docs.python.org/3/library/ipaddress.html#conversion-to-strings-and-integers
https://docs.python.org/3/library/ipaddress.html#operators
https://docs.python.org/3/library/ipaddress.html#comparison-operators
https://docs.python.org/3/library/ipaddress.html#arithmetic-operators
https://docs.python.org/3/library/ipaddress.html#ip-network-definitions
https://docs.python.org/3/library/ipaddress.html#prefix-net-mask-and-host-mask
https://docs.python.org/3/library/ipaddress.html#network-objects
https://docs.python.org/3/library/ipaddress.html#id1
https://docs.python.org/3/library/ipaddress.html#logical-operators
https://docs.python.org/3/library/ipaddress.html#iteration
https://docs.python.org/3/library/ipaddress.html#interface-objects
https://docs.python.org/3/library/ipaddress.html#id2
https://docs.python.org/3/library/ipaddress.html#id3
https://docs.python.org/3/library/ipaddress.html#other-module-level-functions
https://docs.python.org/3/library/ipaddress.html#custom-exceptions

36.10. pipes — Interface to shell pipelines
https://docs.python.org/3/library/pipes.html
https://docs.python.org/3/library/pipes.html#template-objects

20.5. mimetypes — Map filenames to MIME types
20.6. base64 — Base16, Base32, Base64, Base85 Data Encodings
https://docs.python.org/3/library/mimetypes.html
https://docs.python.org/3/library/mimetypes.html#mimetypes-objects
https://docs.python.org/3/library/base64.html

7.2. codecs — Codec registry and base classes

https://docs.python.org/3/library/codecs.html
https://docs.python.org/3/library/codecs.html#codec-base-classes
https://docs.python.org/3/library/codecs.html#error-handlers
https://docs.python.org/3/library/codecs.html#stateless-encoding-and-decoding
https://docs.python.org/3/library/codecs.html#incremental-encoding-and-decoding
https://docs.python.org/3/library/codecs.html#incrementalencoder-objects
https://docs.python.org/3/library/codecs.html#incrementaldecoder-objects
https://docs.python.org/3/library/codecs.html#stream-encoding-and-decoding
https://docs.python.org/3/library/codecs.html#streamwriter-objects
https://docs.python.org/3/library/codecs.html#streamreader-objects
https://docs.python.org/3/library/codecs.html#streamreaderwriter-objects
https://docs.python.org/3/library/codecs.html#streamrecoder-objects
https://docs.python.org/3/library/codecs.html#encodings-and-unicode
https://docs.python.org/3/library/codecs.html#standard-encodings
https://docs.python.org/3/library/codecs.html#python-specific-encodings
https://docs.python.org/3/library/codecs.html#text-encodings
https://docs.python.org/3/library/codecs.html#binary-transforms
https://docs.python.org/3/library/codecs.html#text-transforms
https://docs.python.org/3/library/codecs.html#module-encodings.idna
https://docs.python.org/3/library/codecs.html#module-encodings.mbcs
https://docs.python.org/3/library/codecs.html#module-encodings.utf_8_sig

15. Cryptographic Services
15.1. hashlib — Secure hashes and message digests
15.2. hmac — Keyed-Hashing for Message Authentication
15.3. secrets — Generate secure random numbers for managing secrets

15. Cryptographic Services
https://docs.python.org/3/library/crypto.html

15.1. hashlib — Secure hashes and message digests
https://docs.python.org/3/library/hashlib.html

https://docs.python.org/3/library/hashlib.html#hash-algorithms
https://docs.python.org/3/library/hashlib.html#shake-variable-length-digests
https://docs.python.org/3/library/hashlib.html#key-derivation
https://docs.python.org/3/library/hashlib.html#blake2
https://docs.python.org/3/library/hashlib.html#creating-hash-objects
https://docs.python.org/3/library/hashlib.html#constants
https://docs.python.org/3/library/hashlib.html#examples
https://docs.python.org/3/library/hashlib.html#credits

https://docs.python.org/3/library/hmac.html

15.3. secrets — Generate secure random numbers for managing secrets
https://docs.python.org/3/library/secrets.html

https://docs.python.org/3/library/secrets.html#random-numbers
https://docs.python.org/3/library/secrets.html#generating-tokens
https://docs.python.org/3/library/secrets.html#how-many-bytes-should-tokens-use
https://docs.python.org/3/library/secrets.html#other-functions
https://docs.python.org/3/library/secrets.html#recipes-and-best-practices

24. Internationalization
24.1. gettext — Multilingual internationalization services
24.2. locale — Internationalization services

https://docs.python.org/3/library/i18n.html
https://docs.python.org/3/library/gettext.html

https://docs.python.org/3/library/gettext.html#gnu-gettext-api
https://docs.python.org/3/library/gettext.html#class-based-api
https://docs.python.org/3/library/gettext.html#the-nulltranslations-class
https://docs.python.org/3/library/gettext.html#the-gnutranslations-class
https://docs.python.org/3/library/gettext.html#solaris-message-catalog-support
https://docs.python.org/3/library/gettext.html#the-catalog-constructor
https://docs.python.org/3/library/gettext.html#internationalizing-your-programs-and-modules
https://docs.python.org/3/library/gettext.html#localizing-your-module
https://docs.python.org/3/library/gettext.html#localizing-your-application
https://docs.python.org/3/library/gettext.html#changing-languages-on-the-fly
https://docs.python.org/3/library/gettext.html#deferred-translations
https://docs.python.org/3/library/gettext.html#acknowledgements

23.2. locale — Internationalization services
https://docs.python.org/3/library/locale.html

https://docs.python.org/3/library/locale.html#background-details-hints-tips-and-caveats
https://docs.python.org/3/library/locale.html#for-extension-writers-and-programs-that-embed-python
https://docs.python.org/3/library/locale.html#access-to-message-catalogs

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

## Typing and Types

26.1. typing — Support for type hints
https://docs.python.org/3/library/typing.html
https://docs.python.org/3/library/typing.html#type-aliases
https://docs.python.org/3/library/typing.html#newtype
https://docs.python.org/3/library/typing.html#callable
https://docs.python.org/3/library/typing.html#generics
https://docs.python.org/3/library/typing.html#user-defined-generic-types
https://docs.python.org/3/library/typing.html#the-any-type
https://docs.python.org/3/library/typing.html#classes-functions-and-decorators

8.8. weakref — Weak references
https://docs.python.org/3/library/weakref.html
https://docs.python.org/3/library/weakref.html#weak-reference-objects
https://docs.python.org/3/library/weakref.html#example
https://docs.python.org/3/library/weakref.html#finalizer-objects
https://docs.python.org/3/library/weakref.html#comparing-finalizers-with-del-methods

11.6. Weak References
https://docs.python.org/3/tutorial/stdlib2.html#weak-references

8.9. types — Dynamic type creation and names for built-in types
https://docs.python.org/3/library/types.html
https://docs.python.org/3/library/types.html#dynamic-type-creation
https://docs.python.org/3/library/types.html#standard-interpreter-types
https://docs.python.org/3/library/types.html#additional-utility-classes-and-functions
https://docs.python.org/3/library/types.html#coroutine-utility-functions



## Concurrent Execution

18. contextvars — Context Variables
18.1. Context Variables
18.2. Manual Context Management
18.3. asyncio support

https://docs.python.org/3/library/contextvars.html
https://docs.python.org/3/library/contextvars.html#context-variables
https://docs.python.org/3/library/contextvars.html#manual-context-management
https://docs.python.org/3/library/contextvars.html#asyncio-support

17.6. sched — Event scheduler
17.7. queue — A synchronized queue class

17.8. _thread — Low-level threading API
17.9. _dummy_thread — Drop-in replacement for the _thread module
17.10. dummy_threading — Drop-in replacement for the threading module

17. Concurrent Execution
17.1. threading — Thread-based parallelism
17.2. multiprocessing — Process-based parallelism
17.3. The concurrent package
17.4. concurrent.futures — Launching parallel tasks
17.5. subprocess — Subprocess management

https://docs.python.org/3/library/sched.html
https://docs.python.org/3/library/sched.html#scheduler-objects

https://docs.python.org/3/library/queue.html
https://docs.python.org/3/library/queue.html#queue-objects
https://docs.python.org/3/library/queue.html#simplequeue-objects

https://docs.python.org/3/library/_thread.html
https://docs.python.org/3/library/_dummy_thread.html
https://docs.python.org/3/library/dummy_threading.html

https://docs.python.org/3/library/concurrency.html

https://docs.python.org/3/library/threading.html
https://docs.python.org/3/library/threading.html#thread-local-data
https://docs.python.org/3/library/threading.html#thread-objects
https://docs.python.org/3/library/threading.html#lock-objects
https://docs.python.org/3/library/threading.html#rlock-objects
https://docs.python.org/3/library/threading.html#condition-objects
https://docs.python.org/3/library/threading.html#semaphore-objects
https://docs.python.org/3/library/threading.html#semaphore-example
https://docs.python.org/3/library/threading.html#event-objects
https://docs.python.org/3/library/threading.html#timer-objects
https://docs.python.org/3/library/threading.html#barrier-objects
https://docs.python.org/3/library/threading.html#using-locks-conditions-and-semaphores-in-the-with-statement

https://docs.python.org/3/library/multiprocessing.html
https://docs.python.org/3/library/multiprocessing.html#introduction
https://docs.python.org/3/library/multiprocessing.html#the-process-class
https://docs.python.org/3/library/multiprocessing.html#contexts-and-start-methods
https://docs.python.org/3/library/multiprocessing.html#exchanging-objects-between-processes
https://docs.python.org/3/library/multiprocessing.html#synchronization-between-processes
https://docs.python.org/3/library/multiprocessing.html#sharing-state-between-processes
https://docs.python.org/3/library/multiprocessing.html#using-a-pool-of-workers
https://docs.python.org/3/library/multiprocessing.html#reference
https://docs.python.org/3/library/multiprocessing.html#process-and-exceptions
https://docs.python.org/3/library/multiprocessing.html#pipes-and-queues
https://docs.python.org/3/library/multiprocessing.html#miscellaneous
https://docs.python.org/3/library/multiprocessing.html#connection-objects
https://docs.python.org/3/library/multiprocessing.html#synchronization-primitives
https://docs.python.org/3/library/multiprocessing.html#shared-ctypes-objects
https://docs.python.org/3/library/multiprocessing.html#managers
https://docs.python.org/3/library/multiprocessing.html#proxy-objects
https://docs.python.org/3/library/multiprocessing.html#module-multiprocessing.pool
https://docs.python.org/3/library/multiprocessing.html#authentication-keys
https://docs.python.org/3/library/multiprocessing.html#logging
https://docs.python.org/3/library/multiprocessing.html#module-multiprocessing.dummy
https://docs.python.org/3/library/multiprocessing.html#programming-guidelines
https://docs.python.org/3/library/multiprocessing.html#all-start-methods
https://docs.python.org/3/library/multiprocessing.html#the-spawn-and-forkserver-start-methods
https://docs.python.org/3/library/multiprocessing.html#examples

https://docs.python.org/3/library/concurrent.html
https://docs.python.org/3/library/concurrent.futures.html
https://docs.python.org/3/library/concurrent.futures.html#executor-objects
https://docs.python.org/3/library/concurrent.futures.html#threadpoolexecutor
https://docs.python.org/3/library/concurrent.futures.html#threadpoolexecutor-example
https://docs.python.org/3/library/concurrent.futures.html#processpoolexecutor
https://docs.python.org/3/library/concurrent.futures.html#processpoolexecutor-example
https://docs.python.org/3/library/concurrent.futures.html#future-objects
https://docs.python.org/3/library/concurrent.futures.html#module-functions
https://docs.python.org/3/library/concurrent.futures.html#exception-classes

https://docs.python.org/3/library/subprocess.html
https://docs.python.org/3/library/subprocess.html#using-the-subprocess-module
https://docs.python.org/3/library/subprocess.html#frequently-used-arguments
https://docs.python.org/3/library/subprocess.html#popen-constructor
https://docs.python.org/3/library/subprocess.html#exceptions
https://docs.python.org/3/library/subprocess.html#security-considerations
https://docs.python.org/3/library/subprocess.html#popen-objects
https://docs.python.org/3/library/subprocess.html#windows-popen-helpers
https://docs.python.org/3/library/subprocess.html#windows-constants
https://docs.python.org/3/library/subprocess.html#older-high-level-api
https://docs.python.org/3/library/subprocess.html#replacing-older-functions-with-the-subprocess-module
https://docs.python.org/3/library/subprocess.html#replacing-bin-sh-shell-backquote
https://docs.python.org/3/library/subprocess.html#replacing-shell-pipeline
https://docs.python.org/3/library/subprocess.html#replacing-os-system
https://docs.python.org/3/library/subprocess.html#replacing-the-os-spawn-family
https://docs.python.org/3/library/subprocess.html#replacing-os-popen-os-popen2-os-popen3
https://docs.python.org/3/library/subprocess.html#replacing-functions-from-the-popen2-module
https://docs.python.org/3/library/subprocess.html#legacy-shell-invocation-functions
https://docs.python.org/3/library/subprocess.html#notes
https://docs.python.org/3/library/subprocess.html#converting-an-argument-sequence-to-a-string-on-windows

## Async

<!--
17. Concurrent Execution
17.1. threading — Thread-based parallelism
17.2. multiprocessing — Process-based parallelism
17.3. The concurrent package
17.4. concurrent.futures — Launching parallel tasks
17.5. subprocess — Subprocess management
17.6. sched — Event scheduler
17.7. queue — A synchronized queue class
17.8. _thread — Low-level threading API
17.9. _dummy_thread — Drop-in replacement for the _thread module
17.10. dummy_threading — Drop-in replacement for the threading module

19. Interprocess Communication and Networking
19.1. socket — Low-level networking interface
19.2. ssl — TLS/SSL wrapper for socket objects
19.3. select — Waiting for I/O completion
19.4. selectors — High-level I/O multiplexing
19.5. asyncio — Asynchronous I/O, event loop, coroutines and tasks
19.6. asyncore — Asynchronous socket handler
19.7. asynchat — Asynchronous socket command/response handler
19.8. signal — Set handlers for asynchronous events
19.9. mmap — Memory-mapped file support
-->

https://docs.python.org/3/library/asyncio.html
https://docs.python.org/3/tutorial/stdlib2.html#multi-threading
https://docs.python.org/3/library/multiprocessing.html

https://docs.python.org/3/library/ipc.html

https://docs.python.org/3/library/socket.html
https://docs.python.org/3/library/concurrency.html
https://docs.python.org/3/library/threading.html
https://docs.python.org/3/library/queue.html

General
18. Interprocess Communication and Networking

18.5. asyncio — Asynchronous I/O, event loop, coroutines and tasks

11.4. Multi-threading
17.2. multiprocessing — Process-based parallelism
https://docs.python.org/3/library/threading.html | threading — Thread-based parallelism — Python 3.7.2 documentation

17. Concurrent Execution
17.1. threading — Thread-based parallelism
17.7. queue — A synchronized queue class

17.3. The concurrent package
https://docs.python.org/3/library/concurrent.html
17.4. concurrent.futures — Launching parallel tasks
https://docs.python.org/3/library/concurrent.futures.html
17.5. subprocess — Subprocess management
https://docs.python.org/3/library/subprocess.html
17.6. sched — Event scheduler
https://docs.python.org/3/library/sched.html
17.8. dummy_threading — Drop-in replacement for the threading module
https://docs.python.org/3/library/dummy_threading.html
17.9. _thread — Low-level threading API
https://docs.python.org/3/library/_thread.html
17.10. _dummy_thread — Drop-in replacement for the _thread module
https://docs.python.org/3/library/_dummy_thread.html

Sockets

18.1. socket — Low-level networking interface
18.2. ssl — TLS/SSL wrapper for socket objects
https://docs.python.org/3/library/ssl.html

19.5. asyncio — Asynchronous I/O, event loop, coroutines and tasks
19.6. asyncore — Asynchronous socket handler
19.7. asynchat — Asynchronous socket command/response handler
19.8. signal — Set handlers for asynchronous events

https://docs.python.org/3/library/asyncio.html

https://docs.python.org/3/library/asyncio-eventloop.html#base-event-loop
https://docs.python.org/3/library/asyncio-eventloop.html#run-an-event-loop
https://docs.python.org/3/library/asyncio-eventloop.html#calls
https://docs.python.org/3/library/asyncio-eventloop.html#delayed-calls
https://docs.python.org/3/library/asyncio-eventloop.html#futures
https://docs.python.org/3/library/asyncio-eventloop.html#tasks
https://docs.python.org/3/library/asyncio-eventloop.html#creating-connections
https://docs.python.org/3/library/asyncio-eventloop.html#creating-listening-connections
https://docs.python.org/3/library/asyncio-eventloop.html#file-transferring
https://docs.python.org/3/library/asyncio-eventloop.html#tls-upgrade
https://docs.python.org/3/library/asyncio-eventloop.html#watch-file-descriptors
https://docs.python.org/3/library/asyncio-eventloop.html#low-level-socket-operations
https://docs.python.org/3/library/asyncio-eventloop.html#resolve-host-name
https://docs.python.org/3/library/asyncio-eventloop.html#connect-pipes
https://docs.python.org/3/library/asyncio-eventloop.html#unix-signals
https://docs.python.org/3/library/asyncio-eventloop.html#executor
https://docs.python.org/3/library/asyncio-eventloop.html#error-handling-api
https://docs.python.org/3/library/asyncio-eventloop.html#debug-mode
https://docs.python.org/3/library/asyncio-eventloop.html#server
https://docs.python.org/3/library/asyncio-eventloop.html#handle
https://docs.python.org/3/library/asyncio-eventloop.html#sendfilenotavailableerror
https://docs.python.org/3/library/asyncio-eventloop.html#event-loop-examples
https://docs.python.org/3/library/asyncio-eventloops.html#event-loops
https://docs.python.org/3/library/asyncio-eventloops.html#event-loop-functions
https://docs.python.org/3/library/asyncio-eventloops.html#available-event-loops
https://docs.python.org/3/library/asyncio-eventloops.html#platform-support
https://docs.python.org/3/library/asyncio-eventloops.html#event-loop-policies-and-the-default-policy
https://docs.python.org/3/library/asyncio-eventloops.html#event-loop-policy-interface
https://docs.python.org/3/library/asyncio-eventloops.html#access-to-the-global-loop-policy
https://docs.python.org/3/library/asyncio-eventloops.html#customizing-the-event-loop-policy
https://docs.python.org/3/library/asyncio-task.html#tasks-and-coroutines
https://docs.python.org/3/library/asyncio-task.html#coroutines
https://docs.python.org/3/library/asyncio-task.html#invalidstateerror
https://docs.python.org/3/library/asyncio-task.html#timeouterror
https://docs.python.org/3/library/asyncio-task.html#future
https://docs.python.org/3/library/asyncio-task.html#task
https://docs.python.org/3/library/asyncio-task.html#task-functions
https://docs.python.org/3/library/asyncio-protocol.html#transports-and-protocols-callback-based-api
https://docs.python.org/3/library/asyncio-protocol.html#transports
https://docs.python.org/3/library/asyncio-protocol.html#protocols
https://docs.python.org/3/library/asyncio-protocol.html#protocol-examples
https://docs.python.org/3/library/asyncio-stream.html#streams-coroutine-based-api
https://docs.python.org/3/library/asyncio-stream.html#stream-functions
https://docs.python.org/3/library/asyncio-stream.html#streamreader
https://docs.python.org/3/library/asyncio-stream.html#streamwriter
https://docs.python.org/3/library/asyncio-stream.html#streamreaderprotocol
https://docs.python.org/3/library/asyncio-stream.html#incompletereaderror
https://docs.python.org/3/library/asyncio-stream.html#limitoverrunerror
https://docs.python.org/3/library/asyncio-stream.html#stream-examples
https://docs.python.org/3/library/asyncio-stream.html#tcp-echo-client-using-streams
https://docs.python.org/3/library/asyncio-subprocess.html#subprocess
https://docs.python.org/3/library/asyncio-subprocess.html#windows-event-loop
https://docs.python.org/3/library/asyncio-subprocess.html#create-a-subprocess-high-level-api-using-process
https://docs.python.org/3/library/asyncio-subprocess.html#create-a-subprocess-low-level-api-using-subprocess-popen
https://docs.python.org/3/library/asyncio-subprocess.html#constants
https://docs.python.org/3/library/asyncio-subprocess.html#process
https://docs.python.org/3/library/asyncio-subprocess.html#subprocess-and-threads
https://docs.python.org/3/library/asyncio-subprocess.html#subprocess-examples
https://docs.python.org/3/library/asyncio-sync.html#synchronization-primitives
https://docs.python.org/3/library/asyncio-sync.html#lock
https://docs.python.org/3/library/asyncio-sync.html#event
https://docs.python.org/3/library/asyncio-sync.html#condition
https://docs.python.org/3/library/asyncio-sync.html#semaphore
https://docs.python.org/3/library/asyncio-sync.html#boundedsemaphore
https://docs.python.org/3/library/asyncio-sync.html#using-locks-conditions-and-semaphores-in-the-async-with-statement
https://docs.python.org/3/library/asyncio-queue.html#queues
https://docs.python.org/3/library/asyncio-queue.html#queue
https://docs.python.org/3/library/asyncio-queue.html#priorityqueue
https://docs.python.org/3/library/asyncio-queue.html#lifoqueue
https://docs.python.org/3/library/asyncio-queue.html#exceptions
https://docs.python.org/3/library/asyncio-dev.html#develop-with-asyncio
https://docs.python.org/3/library/asyncio-dev.html#debug-mode-of-asyncio
https://docs.python.org/3/library/asyncio-dev.html#cancellation
https://docs.python.org/3/library/asyncio-dev.html#concurrency-and-multithreading
https://docs.python.org/3/library/asyncio-dev.html#handle-blocking-functions-correctly
https://docs.python.org/3/library/asyncio-dev.html#logging
https://docs.python.org/3/library/asyncio-dev.html#detect-coroutine-objects-never-scheduled
https://docs.python.org/3/library/asyncio-dev.html#detect-exceptions-never-consumed
https://docs.python.org/3/library/asyncio-dev.html#chain-coroutines-correctly
https://docs.python.org/3/library/asyncio-dev.html#pending-task-destroyed
https://docs.python.org/3/library/asyncio-dev.html#close-transports-and-event-loops

https://docs.python.org/3/library/asyncore.html
https://docs.python.org/3/library/asyncore.html#asyncore-example-basic-http-client
https://docs.python.org/3/library/asyncore.html#asyncore-example-basic-echo-server

https://docs.python.org/3/library/asynchat.html
https://docs.python.org/3/library/asynchat.html#asynchat-example

https://docs.python.org/3/library/signal.html
https://docs.python.org/3/library/signal.html#general-rules
https://docs.python.org/3/library/signal.html#execution-of-python-signal-handlers
https://docs.python.org/3/library/signal.html#signals-and-threads
https://docs.python.org/3/library/signal.html#module-contents
https://docs.python.org/3/library/signal.html#example

## Sockets

Socket Programming HOWTO
https://docs.python.org/3/howto/sockets.html

19.1. socket — Low-level networking interface
https://docs.python.org/3/library/socket.html
https://docs.python.org/3/library/socket.html#socket-families
https://docs.python.org/3/library/socket.html#module-contents
https://docs.python.org/3/library/socket.html#exceptions
https://docs.python.org/3/library/socket.html#constants
https://docs.python.org/3/library/socket.html#functions
https://docs.python.org/3/library/socket.html#creating-sockets
https://docs.python.org/3/library/socket.html#socket-objects
https://docs.python.org/3/library/socket.html#notes-on-socket-timeouts
https://docs.python.org/3/library/socket.html#timeouts-and-the-connect-method
https://docs.python.org/3/library/socket.html#timeouts-and-the-accept-method
https://docs.python.org/3/library/socket.html#example

22.21. socketserver — A framework for network servers
https://docs.python.org/3/library/socketserver.html
https://docs.python.org/3/library/socketserver.html#server-creation-notes
https://docs.python.org/3/library/socketserver.html#server-objects
https://docs.python.org/3/library/socketserver.html#request-handler-objects
https://docs.python.org/3/library/socketserver.html#examples
https://docs.python.org/3/library/socketserver.html#socketserver-tcpserver-example
https://docs.python.org/3/library/socketserver.html#socketserver-udpserver-example
https://docs.python.org/3/library/socketserver.html#asynchronous-mixins

19.2. ssl — TLS/SSL wrapper for socket objects
https://docs.python.org/3/library/ssl.html
https://docs.python.org/3/library/ssl.html#functions-constants-and-exceptions
https://docs.python.org/3/library/ssl.html#socket-creation
https://docs.python.org/3/library/ssl.html#context-creation
https://docs.python.org/3/library/ssl.html#exceptions
https://docs.python.org/3/library/ssl.html#random-generation
https://docs.python.org/3/library/ssl.html#certificate-handling
https://docs.python.org/3/library/ssl.html#constants
https://docs.python.org/3/library/ssl.html#ssl-sockets
https://docs.python.org/3/library/ssl.html#ssl-contexts
https://docs.python.org/3/library/ssl.html#certificates
https://docs.python.org/3/library/ssl.html#certificate-chains
https://docs.python.org/3/library/ssl.html#ca-certificates
https://docs.python.org/3/library/ssl.html#combined-key-and-certificate
https://docs.python.org/3/library/ssl.html#self-signed-certificates
https://docs.python.org/3/library/ssl.html#examples
https://docs.python.org/3/library/ssl.html#testing-for-ssl-support
https://docs.python.org/3/library/ssl.html#client-side-operation
https://docs.python.org/3/library/ssl.html#server-side-operation
https://docs.python.org/3/library/ssl.html#notes-on-non-blocking-sockets
https://docs.python.org/3/library/ssl.html#memory-bio-support
https://docs.python.org/3/library/ssl.html#ssl-session
https://docs.python.org/3/library/ssl.html#security-considerations
https://docs.python.org/3/library/ssl.html#best-defaults
https://docs.python.org/3/library/ssl.html#manual-settings
https://docs.python.org/3/library/ssl.html#verifying-certificates
https://docs.python.org/3/library/ssl.html#multi-processing
https://docs.python.org/3/library/ssl.html#tls-1-3
https://docs.python.org/3/library/ssl.html#libressl-support

## The Python Glossary

BDFL
Zen of Python
2to3
Python 3000

https://docs.python.org/3/glossary.html#term-cpython
https://docs.python.org/3/glossary.html#term-pythonic

https://docs.python.org/3/glossary.html#term-idle
https://docs.python.org/3/glossary.html#term-virtual-environment

>>>
...

https://docs.python.org/3/glossary.html#term-docstring
https://docs.python.org/3/glossary.html#term-triple-quoted-string
https://docs.python.org/3/glossary.html#term-universal-newlines

https://docs.python.org/3/glossary.html#term-text-encoding
https://docs.python.org/3/glossary.html#term-text-file

https://docs.python.org/3/glossary.html#term-file-object
https://docs.python.org/3/glossary.html#term-file-like-object

https://docs.python.org/3/glossary.html#term-binary-file
https://docs.python.org/3/glossary.html#term-bytecode
bytes-like object

https://docs.python.org/3/glossary.html#term-interpreted
https://docs.python.org/3/glossary.html#term-interactive

GIL
https://docs.python.org/3/glossary.html#term-global-interpreter-lock

__future__
https://docs.python.org/3/glossary.html#term-future

https://docs.python.org/3/glossary.html#term-import-path
https://docs.python.org/3/glossary.html#term-importing
https://docs.python.org/3/glossary.html#term-importer

https://docs.python.org/3/glossary.html#term-finder
https://docs.python.org/3/glossary.html#term-loader
https://docs.python.org/3/glossary.html#term-meta-path-finder

interpreter shutdown

https://docs.python.org/3/glossary.html#term-garbage-collection

path entry
path entry finder
path entry hook
path based finder
https://docs.python.org/3/glossary.html#term-path-like-object

https://docs.python.org/3/glossary.html#term-package
https://docs.python.org/3/glossary.html#term-regular-package
https://docs.python.org/3/glossary.html#term-namespace
https://docs.python.org/3/glossary.html#term-namespace-package

https://docs.python.org/3/glossary.html#term-module
https://docs.python.org/3/glossary.html#term-module-spec

function
generic function

class
object

argument
keyword argument
positional argument
parameter

https://docs.python.org/3/glossary.html#term-method-resolution-order
MRO
method
attribute

https://docs.python.org/3/glossary.html#term-metaclass

expression
statement

mutable
immutable

contiguous

sequence
slice

https://docs.python.org/3/glossary.html#term-type
https://docs.python.org/3/glossary.html#term-duck-typing
https://docs.python.org/3/glossary.html#term-function-annotation
https://docs.python.org/3/glossary.html#term-variable-annotation

complex number
https://docs.python.org/3/glossary.html#term-floor-division

list
list comprehension

dictionary
dictionary view
mapping

iterable
iterator

named tuple

generator
generator iterator
generator expression

asynchronous iterable
asynchronous iterator

asynchronous generator
asynchronous generator iterator

https://docs.python.org/3/glossary.html#term-context-manager
https://docs.python.org/3/glossary.html#term-asynchronous-context-manager

abstract base class

https://docs.python.org/3/glossary.html#term-coroutine
https://docs.python.org/3/glossary.html#term-coroutine-function

f-string

EAFP
LBYL

annotation
https://docs.python.org/3/glossary.html#term-awaitable
class variable
coercion
decorator
descriptor
https://docs.python.org/3/glossary.html#term-extension-module
hash-based pyc
hashable
https://docs.python.org/3/glossary.html#term-key-function
lambda
meta path finder
nested scope
https://docs.python.org/3/glossary.html#term-new-style-class
PEP
https://docs.python.org/3/glossary.html#term-portion
https://docs.python.org/3/glossary.html#term-provisional-api
https://docs.python.org/3/glossary.html#term-provisional-package
https://docs.python.org/3/glossary.html#term-qualified-name
https://docs.python.org/3/glossary.html#term-reference-count
https://docs.python.org/3/glossary.html#term-slots
https://docs.python.org/3/glossary.html#term-single-dispatch
special method
struct sequence
type alias
type hint
https://docs.python.org/3/glossary.html#term-virtual-machine

## The Python General Index and Module Index- Priority

## The Python General Index and Module Index

https://docs.python.org/3/genindex.html
https://docs.python.org/3/py-modindex.html

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


## Less Common Utilities?

16.16. ctypes — A foreign function library for Python

https://docs.python.org/3/library/ctypes.html

21.4. XML Processing Modules
21.5. xml.etree.ElementTree — The ElementTree XML API
21.6. xml.dom — The Document Object Model API
21.7. xml.dom.minidom — Minimal DOM implementation
21.8. xml.dom.pulldom — Support for building partial DOM trees
21.9. xml.sax — Support for SAX2 parsers
21.10. xml.sax.handler — Base classes for SAX handlers
21.11. xml.sax.saxutils — SAX Utilities
21.12. xml.sax.xmlreader — Interface for XML parsers
21.13. xml.parsers.expat — Fast XML parsing using Expat

https://docs.python.org/3/library/xml.html
https://docs.python.org/3/library/xml.etree.elementtree.html
https://docs.python.org/3/library/xml.dom.html
https://docs.python.org/3/library/xml.sax.html
https://docs.python.org/3/library/pyexpat.html

22.25. xmlrpc — XMLRPC server and client modules
22.26. xmlrpc.client — XML-RPC client access
22.27. xmlrpc.server — Basic XML-RPC servers

https://docs.python.org/3/library/xmlrpc.html

12. Data Persistence
12.1. pickle — Python object serialization

https://docs.python.org/3/library/pickle.html
https://docs.python.org/3/library/pickletools.html

13. Data Compression and Archiving
13.1. zlib — Compression compatible with gzip
13.2. gzip — Support for gzip files
13.3. bz2 — Support for bzip2 compression
13.4. lzma — Compression using the LZMA algorithm
13.5. zipfile — Work with ZIP archives
13.6. tarfile — Read and write tar archive files

https://docs.python.org/3/library/zlib.html
https://docs.python.org/3/library/gzip.html
https://docs.python.org/3/library/bz2.html
https://docs.python.org/3/library/lzma.html
https://docs.python.org/3/library/zipfile.html
https://docs.python.org/3/library/tarfile.html

29.4. zipapp — Manage executable python zip archives

https://docs.python.org/3/library/zipapp.html

23. Multimedia Services
23.1. audioop — Manipulate raw audio data
23.2. aifc — Read and write AIFF and AIFC files
23.3. sunau — Read and write Sun AU files
23.4. wave — Read and write WAV files
23.5. chunk — Read IFF chunked data
23.6. colorsys — Conversions between color systems
23.7. imghdr — Determine the type of an image
23.8. sndhdr — Determine type of sound file
23.9. ossaudiodev — Access to OSS-compatible audio devices

https://docs.python.org/3/library/audioop.html
https://docs.python.org/3/library/aifc.html
https://docs.python.org/3/library/sunau.html
https://docs.python.org/3/library/wave.html
https://docs.python.org/3/library/chunk.html
https://docs.python.org/3/library/colorsys.html
https://docs.python.org/3/library/imghdr.html
https://docs.python.org/3/library/sndhdr.html
https://docs.python.org/3/library/ossaudiodev.html

20. Internet Data Handling
20.7. binhex — Encode and decode binhex4 files
20.8. binascii — Convert between binary and ASCII
20.9. quopri — Encode and decode MIME quoted-printable data
20.10. uu — Encode and decode uuencode files

https://docs.python.org/3/library/binhex.html
https://docs.python.org/3/library/binhex.html#notes
https://docs.python.org/3/library/binascii.html
https://docs.python.org/3/library/quopri.html
https://docs.python.org/3/library/uu.html

30.9. atexit — Exit handlers
https://docs.python.org/3/library/atexit.html
https://docs.python.org/3/library/atexit.html#atexit-example

6. Text Processing Services

6.3. difflib — Helpers for computing deltas
6.4. textwrap — Text wrapping and filling
6.5. unicodedata — Unicode Database
6.6. stringprep — Internet String Preparation
6.7. readline — GNU readline interface
6.8. rlcompleter — Completion function for GNU readline

https://docs.python.org/3/library/difflib.html
https://docs.python.org/3/library/textwrap.html
https://docs.python.org/3/library/unicodedata.html
https://docs.python.org/3/library/stringprep.html
https://docs.python.org/3/library/readline.html
https://docs.python.org/3/library/rlcompleter.html

36. Unix Specific Services
36.1. posix — The most common POSIX system calls
36.2. pwd — The password database
36.3. spwd — The shadow password database
36.4. grp — The group database
36.5. crypt — Function to check Unix passwords
36.6. termios — POSIX style tty control
36.7. tty — Terminal control functions
36.8. pty — Pseudo-terminal utilities
36.9. fcntl — The fcntl and ioctl system calls

36.12. nis — Interface to Sun’s NIS (Yellow Pages)
36.13. syslog — Unix syslog library routines

https://docs.python.org/3/library/posix.html
https://docs.python.org/3/library/pwd.html
https://docs.python.org/3/library/spwd.html
https://docs.python.org/3/library/grp.html
https://docs.python.org/3/library/crypt.html
https://docs.python.org/3/library/termios.html
https://docs.python.org/3/library/tty.html
https://docs.python.org/3/library/pty.html
https://docs.python.org/3/library/fcntl.html
	   
https://docs.python.org/3/library/nis.html
https://docs.python.org/3/library/syslog.html

14. File Formats
14.2. configparser — Configuration file parser
14.3. netrc — netrc file processing
14.4. xdrlib — Encode and decode XDR data
14.5. plistlib — Generate and parse Mac OS X .plist files

https://docs.python.org/3/library/configparser.html
https://docs.python.org/3/library/netrc.html
https://docs.python.org/3/library/xdrlib.html
https://docs.python.org/3/library/plistlib.html

7. Binary Data Services
7.1. struct — Interpret bytes as packed binary data

https://docs.python.org/3/library/binary.html
https://docs.python.org/3/library/struct.html

25. Program Frameworks
25.2. cmd — Support for line-oriented command interpreters
25.3. shlex — Simple lexical analysis

https://docs.python.org/3/library/cmd.html#module-cmd
https://docs.python.org/3/library/shlex.html#module-shlex

12. Data Persistence
12.2. copyreg — Register pickle support functions
12.3. shelve — Python object persistence
12.5. dbm — Interfaces to Unix “databases”

https://docs.python.org/3/library/persistence.html
https://docs.python.org/3/library/copyreg.html
https://docs.python.org/3/library/shelve.html
https://docs.python.org/3/library/dbm.html

16.9. getpass — Portable password input
16.10. curses — Terminal handling for character-cell displays
16.11. curses.textpad — Text input widget for curses programs
16.12. curses.ascii — Utilities for ASCII characters
16.13. curses.panel — A panel stack extension for curses
16.15. errno — Standard errno system symbols

https://docs.python.org/3/library/getpass.html
https://docs.python.org/3/library/curses.html
https://docs.python.org/3/library/curses.ascii.html
https://docs.python.org/3/library/curses.panel.html
https://docs.python.org/3/library/errno.html

19.3. select — Waiting for I/O completion
19.4. selectors — High-level I/O multiplexing
19.9. mmap — Memory-mapped file support

https://docs.python.org/3/library/select.html
https://docs.python.org/3/library/selectors.html
https://docs.python.org/3/library/mmap.html

35. MS Windows Specific Services
35.1. msilib — Read and write Microsoft Installer files
35.2. msvcrt — Useful routines from the MS VC++ runtime
35.3. winreg — Windows registry access
35.4. winsound — Sound-playing interface for Windows

https://docs.python.org/3/library/msilib.html
https://docs.python.org/3/library/msvcrt.html
https://docs.python.org/3/library/winreg.html
https://docs.python.org/3/library/winsound.html

26.5. IDLE
26.6. Other Graphical User Interface Packages

https://docs.python.org/3/library/idle.html
https://docs.python.org/3/library/othergui.html#other-graphical-user-interface-packages

26. Graphical User Interfaces with Tk
26.1. tkinter — Python interface to Tcl/Tk
26.2. tkinter.ttk — Tk themed widgets
26.3. tkinter.tix — Extension widgets for Tk
26.4. tkinter.scrolledtext — Scrolled Text Widget

https://docs.python.org/3/library/tk.html#graphical-user-interfaces-with-tk

25.1. turtle — Turtle graphics

https://docs.python.org/3/library/turtle.html
