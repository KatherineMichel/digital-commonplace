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
https://en.wikipedia.org/wiki/Call_stack | Call stack - Wikipedia
frame object - Google Search
https://docs.python.org/3/library/inspect.html#the-interpreter-stack

https://docs.python.org/3/c-api/
https://docs.python.org/3/c-api/stable.html | Stable Application Binary Interface — Python 3.8.3 documentation
https://docs.python.org/3.8/extending/extending.html

https://www.python.org/dev/peps/pep-0384/ | PEP 384 -- Defining a Stable ABI | Python.org

https://en.wikipedia.org/wiki/Random-access_memory | Random-access memory - Wikipedia

https://en.wikipedia.org/wiki/Backward_compatibility | Backward compatibility - Wikipedia

https://en.wikipedia.org/wiki/Self-documenting_code | Self-documenting code - Wikipedia

http://pythontutor.com/visualize.html#mode=edit | Visualize Python, Java, JavaScript, C, C++, Ruby code execution

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

https://www.python.org/dev/peps/pep-0484/ | PEP 484 -- Type Hints | Python.org

https://docs.python.org/3.8/library/types.html | types — Dynamic type creation and names for built-in types — Python 3.8.3 documentation

https://docs.python.org/3/library/exceptions.html#TypeError | Built-in Exceptions — Python 3.8.3 documentation
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypeError | TypeError - JavaScript | MDN
https://docs.python.org/3/library/exceptions.html#NameError | Built-in Exceptions — Python 3.8.3 documentation
https://docs.python.org/3/library/exceptions.html#ValueError | Built-in Exceptions — Python 3.8.3 documentation
https://eli.thegreenplace.net/2011/05/15/understanding-unboundlocalerror-in-python/ | Understanding UnboundLocalError in Python - Eli Bendersky's website

https://docs.python.org/3/library/python.html

https://docs.python.org/3/tutorial/modules.html#standard-modules | 6. Modules — Python 3.8.5 documentation


negative indexes python - Google Search


https://docs.python.org/3/library/sys.html#module-sys | sys — System-specific parameters and functions — Python 3.8.5 documentation


https://docs.python.org/3/library/fileformats.html | File Formats — Python 3.8.3 documentation
https://docs.python.org/3/tutorial/stdlib.html#file-wildcards | 10. Brief Tour of the Standard Library — Python 3.8.5 documentation

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

<!--
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

Internal Use
https://docs.python.org/3/library/test.html
https://docs.python.org/3/library/test.html#writing-unit-tests-for-the-test-package
https://docs.python.org/3/library/test.html#running-tests-using-the-command-line-interface
https://docs.python.org/3/library/test.html#module-test.support
https://docs.python.org/3/library/test.html#module-test.support.script_helper

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

36.10. pipes — Interface to shell pipelines
https://docs.python.org/3/library/pipes.html
https://docs.python.org/3/library/pipes.html#template-objects


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



## The Python General Index and Module Index- Priority

## The Python General Index and Module Index

https://docs.python.org/3/genindex.html
https://docs.python.org/3/py-modindex.html

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


## 2 to 3- Deprecated

Automated Python 2 to 3 code translation
https://docs.python.org/3/library/2to3.html
https://docs.python.org/3/library/2to3.html#using-2to3
https://docs.python.org/3/library/2to3.html#fixers
https://docs.python.org/3/library/2to3.html#module-lib2to3


## I/O

16.2. io — Core tools for working with streams
https://docs.python.org/3/library/io.html

## Concurrent Execution

18. contextvars — Context Variables
18.1. Context Variables
18.2. Manual Context Management
18.3. asyncio support

https://docs.python.org/3/library/contextvars.html

## Async

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

https://docs.python.org/3/tutorial/stdlib2.html#multi-threading

https://docs.python.org/3/library/concurrency.html

https://docs.python.org/3/library/threading.html
https://docs.python.org/3/library/multiprocessing.html
https://docs.python.org/3/library/concurrent.html
https://docs.python.org/3/library/concurrent.futures.html
https://docs.python.org/3/library/subprocess.html

https://docs.python.org/3/library/sched.html

https://docs.python.org/3/library/queue.html

https://docs.python.org/3/library/_thread.html
https://docs.python.org/3/library/_dummy_thread.html
https://docs.python.org/3/library/dummy_threading.html

https://docs.python.org/3/library/ipc.html

Sockets

18.1. socket — Low-level networking interface
18.2. ssl — TLS/SSL wrapper for socket objects
https://docs.python.org/3/library/ssl.html

19.5. asyncio — Asynchronous I/O, event loop, coroutines and tasks
19.6. asyncore — Asynchronous socket handler
19.7. asynchat — Asynchronous socket command/response handler
19.8. signal — Set handlers for asynchronous events

https://docs.python.org/3/library/asyncio.html
https://docs.python.org/3/library/asyncore.html
https://docs.python.org/3/library/asynchat.html
https://docs.python.org/3/library/signal.html

## Sockets

Socket Programming HOWTO
https://docs.python.org/3/howto/sockets.html

19.1. socket — Low-level networking interface
https://docs.python.org/3/library/socket.html

22.21. socketserver — A framework for network servers
https://docs.python.org/3/library/socketserver.html

19.2. ssl — TLS/SSL wrapper for socket objects
https://docs.python.org/3/library/ssl.html


26. Graphical User Interfaces with Tk
26.1. tkinter — Python interface to Tcl/Tk
26.2. tkinter.ttk — Tk themed widgets
26.3. tkinter.tix — Extension widgets for Tk
26.4. tkinter.scrolledtext — Scrolled Text Widget

https://docs.python.org/3/library/tkinter.html
https://docs.python.org/3/library/tk.html#graphical-user-interfaces-with-tk

25.1. turtle — Turtle graphics

https://docs.python.org/3/library/turtle.html
