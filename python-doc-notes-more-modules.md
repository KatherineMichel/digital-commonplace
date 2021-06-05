# Python Doc Notes

## Best Practices and Common Tools

<!--
https://en.wikipedia.org/wiki/Pseudorandomness | Pseudorandomness - Wikipedia

https://twitter.com/aaronchall/status/1114713624453554176

https://docs.python.org/3/library/python.html

https://en.wikipedia.org/wiki/Call_stack | Call stack - Wikipedia
frame object - Google Search
https://docs.python.org/3/library/inspect.html#the-interpreter-stack

https://docs.python.org/3/c-api/
https://docs.python.org/3/c-api/stable.html | Stable Application Binary Interface — Python 3.8.3 documentation
https://docs.python.org/3.8/extending/extending.html

https://www.python.org/dev/peps/pep-0384/ | PEP 384 -- Defining a Stable ABI | Python.org

https://www.python.org/dev/peps/pep-0484/ | PEP 484 -- Type Hints | Python.org

https://docs.python.org/3.8/library/types.html | types — Dynamic type creation and names for built-in types — Python 3.8.3 documentation

https://en.wikipedia.org/wiki/Scope_(computer_science) | Scope (computer science) - Wikipedia
https://en.wikipedia.org/wiki/Namespace | Namespace - Wikipedia
https://en.wikipedia.org/wiki/Metaclass | Metaclass - Wikipedia
-->

Internal Use
https://docs.python.org/3/library/test.html
https://docs.python.org/3/library/test.html#writing-unit-tests-for-the-test-package
https://docs.python.org/3/library/test.html#running-tests-using-the-command-line-interface
https://docs.python.org/3/library/test.html#module-test.support
https://docs.python.org/3/library/test.html#module-test.support.script_helper



10.9. Data Compression
https://docs.python.org/3/tutorial/stdlib.html#data-compression

10.12. Batteries Included
https://docs.python.org/3/tutorial/stdlib.html#batteries-included
https://docs.python.org/3/library/xmlrpc.client.html#module-xmlrpc.client
https://docs.python.org/3/library/xmlrpc.server.html#module-xmlrpc.server
https://docs.python.org/3/library/email.html#module-email
https://docs.python.org/3/library/poplib.html#module-poplib

10.12. Batteries Included
10.7. Internet Access
https://docs.python.org/3/library/smtplib.html#module-smtplib

10.7. Internet Access
https://docs.python.org/3/tutorial/stdlib.html#internet-access

urllib
https://docs.python.org/2/library/urllib.html#urllib.urlretrieve | 20.5. urllib — Open arbitrary resources by URL — Python 2.7.18 documentation




## Internals

16.16. ctypes — A foreign function library for Python

"ctypes is a foreign function library for Python. It provides C compatible data types, and allows calling functions in DLLs or shared libraries. It can be used to wrap these libraries in pure Python."
https://docs.python.org/3/library/ctypes.html
https://docs.python.org/3/library/ctypes.html#ctypes-tutorial
https://docs.python.org/3/library/ctypes.html#loading-dynamic-link-libraries
https://docs.python.org/3/library/ctypes.html#accessing-functions-from-loaded-dlls
https://docs.python.org/3/library/ctypes.html#calling-functions
https://docs.python.org/3/library/ctypes.html#fundamental-data-types
https://docs.python.org/3/library/ctypes.html#calling-functions-continued
https://docs.python.org/3/library/ctypes.html#calling-functions-with-your-own-custom-data-types
https://docs.python.org/3/library/ctypes.html#specifying-the-required-argument-types-function-prototypes
https://docs.python.org/3/library/ctypes.html#return-types
https://docs.python.org/3/library/ctypes.html#passing-pointers-or-passing-parameters-by-reference
https://docs.python.org/3/library/ctypes.html#structures-and-unions
https://docs.python.org/3/library/ctypes.html#structure-union-alignment-and-byte-order
https://docs.python.org/3/library/ctypes.html#bit-fields-in-structures-and-unions
https://docs.python.org/3/library/ctypes.html#arrays
https://docs.python.org/3/library/ctypes.html#pointers
https://docs.python.org/3/library/ctypes.html#type-conversions
https://docs.python.org/3/library/ctypes.html#incomplete-types
https://docs.python.org/3/library/ctypes.html#callback-functions
https://docs.python.org/3/library/ctypes.html#accessing-values-exported-from-dlls
https://docs.python.org/3/library/ctypes.html#surprises
https://docs.python.org/3/library/ctypes.html#variable-sized-data-types
https://docs.python.org/3/library/ctypes.html#ctypes-reference
https://docs.python.org/3/library/ctypes.html#finding-shared-libraries
https://docs.python.org/3/library/ctypes.html#loading-shared-libraries
https://docs.python.org/3/library/ctypes.html#foreign-functions
https://docs.python.org/3/library/ctypes.html#function-prototypes
https://docs.python.org/3/library/ctypes.html#utility-functions
https://docs.python.org/3/library/ctypes.html#data-types
https://docs.python.org/3/library/ctypes.html#ctypes-fundamental-data-types-2

https://docs.python.org/3/library/ctypes.html#structured-data-types
https://docs.python.org/3/library/ctypes.html#arrays-and-pointers


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


pip
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


## Python and Django Testing

27.2. pydoc — Documentation generator and online help system
https://docs.python.org/3/library/pydoc.html
-->




<!--
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

8.11. pprint — Data pretty printer
https://docs.python.org/3/library/pprint.html
https://docs.python.org/3/library/pprint.html#prettyprinter-objects
https://docs.python.org/3/library/pprint.html#example

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


7. Input and Output
https://docs.python.org/3/tutorial/inputoutput.html
https://docs.python.org/3/tutorial/inputoutput.html#methods-of-file-objects
https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files
https://docs.python.org/3/library/functions.html#open

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

https://docs.python.org/3/glossary.html#term-garbage-collection

11.6. Weak References
https://docs.python.org/3/tutorial/stdlib2.html#weak-references

8.9. types — Dynamic type creation and names for built-in types
https://docs.python.org/3/library/types.html
https://docs.python.org/3/library/types.html#dynamic-type-creation
https://docs.python.org/3/library/types.html#standard-interpreter-types
https://docs.python.org/3/library/types.html#additional-utility-classes-and-functions
https://docs.python.org/3/library/types.html#coroutine-utility-functions




Template
36.10. pipes — Interface to shell pipelines
https://docs.python.org/3/library/pipes.html
https://docs.python.org/3/library/pipes.html#template-objects

14. File Formats
14.5. plistlib — Generate and parse Mac OS X .plist files
https://docs.python.org/3/library/plistlib.html



30.14. site — Site-specific configuration hook
https://docs.python.org/3/library/site.html
https://docs.python.org/3/library/site.html#readline-configuration
https://docs.python.org/3/library/site.html#module-contents


22.11. http — HTTP modules
22.12. http.client — HTTP protocol client

https://docs.python.org/3/library/http.html

"This module defines classes which implement the client side of the HTTP and HTTPS protocols. It is normally not used directly — the module urllib.request uses it to handle URLs that use HTTP and HTTPS."
https://docs.python.org/3/library/http.client.html
https://docs.python.org/3/library/http.client.html#httpconnection-objects
https://docs.python.org/3/library/http.client.html#httpresponse-objects
https://docs.python.org/3/library/http.client.html#examples
https://docs.python.org/3/library/http.client.html#httpmessage-objects

11.2. Templating
https://docs.python.org/3/tutorial/stdlib2.html#templating
https://docs.python.org/3/library/string.html#module-string
https://docs.python.org/3/library/string.html#string.Template


22.23. http.cookies — HTTP state management
22.24. http.cookiejar — Cookie handling for HTTP clients

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

https://stackoverflow.com/questions/2018026/what-are-the-differences-between-the-urllib-urllib2-urllib3-and-requests-modul

"The module has been designed to match the Internet RFC on Relative Uniform Resource Locators. It supports the following URL schemes: file, ftp, gopher, hdl, http, https, imap, mailto, mms, news, nntp, prospero, rsync, rtsp, rtspu, sftp, shttp, sip, sips, snews, svn, svn+ssh, telnet, wais, ws, wss."

22.5. urllib — URL handling modules
22.6. urllib.request — Extensible library for opening URLs
22.7. urllib.response — Response classes used by urllib
22.8. urllib.parse — Parse URLs into components

22.9. urllib.error — Exception classes raised by urllib.request
22.10. urllib.robotparser — Parser for robots.txt

https://docs.python.org/3/library/urllib.html
https://docs.python.org/3/library/urllib.request.html
https://docs.python.org/3/library/urllib.parse.html

HOWTO Fetch Internet Resources Using The urllib Package
https://docs.python.org/3/howto/urllib2.html

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

https://docs.python.org/3/library/urllib.error.html#module-urllib.error
https://docs.python.org/3/library/urllib.robotparser.html#module-urllib.robotparser

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
https://docs.python.org/3/library/xml.html#xml-vulnerabilities
https://docs.python.org/3/library/xml.html#the-defusedxml-and-defusedexpat-packages
https://docs.python.org/3/library/xml.etree.elementtree.html
https://docs.python.org/3/library/xml.etree.elementtree.html#tutorial
https://docs.python.org/3/library/xml.etree.elementtree.html#xml-tree-and-elements
https://docs.python.org/3/library/xml.etree.elementtree.html#parsing-xml
https://docs.python.org/3/library/xml.etree.elementtree.html#pull-api-for-non-blocking-parsing
https://docs.python.org/3/library/xml.etree.elementtree.html#finding-interesting-elements
https://docs.python.org/3/library/xml.etree.elementtree.html#modifying-an-xml-file
https://docs.python.org/3/library/xml.etree.elementtree.html#building-xml-documents
https://docs.python.org/3/library/xml.etree.elementtree.html#parsing-xml-with-namespaces
https://docs.python.org/3/library/xml.etree.elementtree.html#additional-resources
https://docs.python.org/3/library/xml.etree.elementtree.html#xpath-support
https://docs.python.org/3/library/xml.etree.elementtree.html#example
https://docs.python.org/3/library/xml.etree.elementtree.html#supported-xpath-syntax
https://docs.python.org/3/library/xml.etree.elementtree.html#reference
https://docs.python.org/3/library/xml.etree.elementtree.html#functions
https://docs.python.org/3/library/xml.etree.elementtree.html#element-objects
https://docs.python.org/3/library/xml.etree.elementtree.html#elementtree-objects
https://docs.python.org/3/library/xml.etree.elementtree.html#qname-objects
https://docs.python.org/3/library/xml.etree.elementtree.html#treebuilder-objects
https://docs.python.org/3/library/xml.etree.elementtree.html#xmlparser-objects
https://docs.python.org/3/library/xml.etree.elementtree.html#xmlpullparser-objects
https://docs.python.org/3/library/xml.etree.elementtree.html#exceptions

"xml.dom — The Document Object Model API"
https://docs.python.org/3/library/xml.dom.html
https://docs.python.org/3/library/xml.dom.html#module-contents
https://docs.python.org/3/library/xml.dom.html#objects-in-the-dom
https://docs.python.org/3/library/xml.dom.html#domimplementation-objects
https://docs.python.org/3/library/xml.dom.html#node-objects
https://docs.python.org/3/library/xml.dom.html#nodelist-objects
https://docs.python.org/3/library/xml.dom.html#documenttype-objects
https://docs.python.org/3/library/xml.dom.html#document-objects
https://docs.python.org/3/library/xml.dom.html#element-objects
https://docs.python.org/3/library/xml.dom.html#attr-objects
https://docs.python.org/3/library/xml.dom.html#namednodemap-objects
https://docs.python.org/3/library/xml.dom.html#comment-objects
https://docs.python.org/3/library/xml.dom.html#text-and-cdatasection-objects
https://docs.python.org/3/library/xml.dom.html#processinginstruction-objects
https://docs.python.org/3/library/xml.dom.html#exceptions
https://docs.python.org/3/library/xml.dom.html#conformance
https://docs.python.org/3/library/xml.dom.html#type-mapping
https://docs.python.org/3/library/xml.dom.html#accessor-methods
https://docs.python.org/3/library/xml.dom.minidom.html
https://docs.python.org/3/library/xml.dom.minidom.html#dom-objects
https://docs.python.org/3/library/xml.dom.minidom.html#dom-example
https://docs.python.org/3/library/xml.dom.minidom.html#minidom-and-the-dom-standard
https://docs.python.org/3/library/xml.dom.pulldom.html
https://docs.python.org/3/library/xml.dom.pulldom.html#domeventstream-objects

"The xml.sax package provides a number of modules which implement the Simple API for XML (SAX) interface for Python. The package itself provides the SAX exceptions and the convenience functions which will be most used by users of the SAX API."
https://docs.python.org/3/library/xml.sax.html
https://docs.python.org/3/library/xml.sax.html#saxexception-objects
https://docs.python.org/3/library/xml.sax.handler.html
https://docs.python.org/3/library/xml.sax.handler.html#contenthandler-objects
https://docs.python.org/3/library/xml.sax.handler.html#dtdhandler-objects
https://docs.python.org/3/library/xml.sax.handler.html#entityresolver-objects
https://docs.python.org/3/library/xml.sax.handler.html#errorhandler-objects
https://docs.python.org/3/library/xml.sax.utils.html
https://docs.python.org/3/library/xml.sax.reader.html
https://docs.python.org/3/library/xml.sax.reader.html#xmlreader-objects
https://docs.python.org/3/library/xml.sax.reader.html#incrementalparser-objects
https://docs.python.org/3/library/xml.sax.reader.html#locator-objects
https://docs.python.org/3/library/xml.sax.reader.html#inputsource-objects
https://docs.python.org/3/library/xml.sax.reader.html#the-attributes-interface
https://docs.python.org/3/library/xml.sax.reader.html#the-attributesns-interface

https://docs.python.org/3/library/pyexpat.html
https://docs.python.org/3/library/pyexpat.html#xmlparser-objects
https://docs.python.org/3/library/pyexpat.html#expaterror-exceptions
https://docs.python.org/3/library/pyexpat.html#example
https://docs.python.org/3/library/pyexpat.html#module-xml.parsers.expat.model
https://docs.python.org/3/library/pyexpat.html#module-xml.parsers.expat.errors

22.25. xmlrpc — XMLRPC server and client modules
22.26. xmlrpc.client — XML-RPC client access
22.27. xmlrpc.server — Basic XML-RPC servers

"XML-RPC is a Remote Procedure Call method that uses XML passed via HTTP as a transport. With it, a client can call methods with parameters on a remote server (the server is named by a URI) and get back structured data."
https://docs.python.org/3/library/xmlrpc.html
https://docs.python.org/3/library/xmlrpc.client.html
https://docs.python.org/3/library/xmlrpc.client.html#serverproxy-objects
https://docs.python.org/3/library/xmlrpc.client.html#datetime-objects
https://docs.python.org/3/library/xmlrpc.client.html#binary-objects
https://docs.python.org/3/library/xmlrpc.client.html#fault-objects
https://docs.python.org/3/library/xmlrpc.client.html#protocolerror-objects
https://docs.python.org/3/library/xmlrpc.client.html#multicall-objects
https://docs.python.org/3/library/xmlrpc.client.html#convenience-functions
https://docs.python.org/3/library/xmlrpc.client.html#example-of-client-usage
https://docs.python.org/3/library/xmlrpc.client.html#example-of-client-and-server-usage
https://docs.python.org/3/library/xmlrpc.server.html
https://docs.python.org/3/library/xmlrpc.server.html#simplexmlrpcserver-objects
https://docs.python.org/3/library/xmlrpc.server.html#simplexmlrpcserver-example
https://docs.python.org/3/library/xmlrpc.server.html#cgixmlrpcrequesthandler
https://docs.python.org/3/library/xmlrpc.server.html#documenting-xmlrpc-server
https://docs.python.org/3/library/xmlrpc.server.html#docxmlrpcserver-objects
https://docs.python.org/3/library/xmlrpc.server.html#doccgixmlrpcrequesthandler


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




20.1. email — An email and MIME handling package

22.13. ftplib — FTP protocol client
22.14. poplib — POP3 protocol client
22.15. imaplib — IMAP4 protocol client
22.16. nntplib — NNTP protocol client
22.17. smtplib — SMTP protocol client
22.18. smtpd — SMTP Server
22.19. telnetlib — Telnet client
22.20. uuid — UUID objects according to RFC 4122

20.5. mimetypes — Map filenames to MIME types
20.6. base64 — Base16, Base32, Base64, Base85 Data Encodings
7.2. codecs — Codec registry and base classes


14. File Formats
14.2. configparser — Configuration file parser
14.3. netrc — netrc file processing
14.4. xdrlib — Encode and decode XDR data
14.5. plistlib — Generate and parse Mac OS X .plist files

https://docs.python.org/3/library/configparser.html
https://docs.python.org/3/library/configparser.html#quick-start
https://docs.python.org/3/library/configparser.html#supported-datatypes
https://docs.python.org/3/library/configparser.html#fallback-values
https://docs.python.org/3/library/configparser.html#supported-ini-file-structure
https://docs.python.org/3/library/configparser.html#interpolation-of-values
https://docs.python.org/3/library/configparser.html#mapping-protocol-access
https://docs.python.org/3/library/configparser.html#customizing-parser-behaviour
https://docs.python.org/3/library/configparser.html#legacy-api-examples
https://docs.python.org/3/library/configparser.html#configparser-objects
https://docs.python.org/3/library/configparser.html#rawconfigparser-objects
https://docs.python.org/3/library/configparser.html#exceptions

https://docs.python.org/3/library/netrc.html
https://docs.python.org/3/library/netrc.html#netrc-objects

https://docs.python.org/3/library/xdrlib.html
https://docs.python.org/3/library/xdrlib.html#packer-objects
https://docs.python.org/3/library/xdrlib.html#unpacker-objects
https://docs.python.org/3/library/xdrlib.html#exceptions

https://docs.python.org/3/library/plistlib.html
https://docs.python.org/3/library/plistlib.html#examples

7. Binary Data Services
7.1. struct — Interpret bytes as packed binary data

https://docs.python.org/3/library/binary.html
https://docs.python.org/3/library/struct.html
https://docs.python.org/3/library/struct.html#functions-and-exceptions
https://docs.python.org/3/library/struct.html#format-strings
https://docs.python.org/3/library/struct.html#byte-order-size-and-alignment
https://docs.python.org/3/library/struct.html#format-characters
https://docs.python.org/3/library/struct.html#examples
https://docs.python.org/3/library/struct.html#classes


25. Program Frameworks
25.2. cmd — Support for line-oriented command interpreters
25.3. shlex — Simple lexical analysis

https://docs.python.org/3/library/cmd.html#module-cmd
https://docs.python.org/3/library/cmd.html#cmd-objects
https://docs.python.org/3/library/cmd.html#cmd-example

https://docs.python.org/3/library/shlex.html#module-shlex
https://docs.python.org/3/library/shlex.html#shlex-objects
https://docs.python.org/3/library/shlex.html#parsing-rules
https://docs.python.org/3/library/shlex.html#improved-compatibility-with-shells




16.10. curses — Terminal handling for character-cell displays
16.11. curses.textpad — Text input widget for curses programs
16.12. curses.ascii — Utilities for ASCII characters
16.13. curses.panel — A panel stack extension for curses

https://docs.python.org/3/library/curses.html
https://docs.python.org/3/library/curses.html#functions
https://docs.python.org/3/library/curses.html#window-objects
https://docs.python.org/3/library/curses.html#constants
https://docs.python.org/3/library/curses.html#module-curses.textpad
https://docs.python.org/3/library/curses.html#textbox-objects

https://docs.python.org/3/library/curses.ascii.html

https://docs.python.org/3/library/curses.panel.html
https://docs.python.org/3/library/curses.panel.html#functions
https://docs.python.org/3/library/curses.panel.html#panel-objects

## Tkinter

26. Graphical User Interfaces with Tk
26.1. tkinter — Python interface to Tcl/Tk
26.2. tkinter.ttk — Tk themed widgets
26.3. tkinter.tix — Extension widgets for Tk
26.4. tkinter.scrolledtext — Scrolled Text Widget

https://docs.python.org/3/library/tkinter.html
https://docs.python.org/3/library/tk.html#graphical-user-interfaces-with-tk
https://docs.python.org/3/library/tkinter.html#module-tkinter
https://docs.python.org/3/library/tkinter.html#tkinter-modules
https://docs.python.org/3/library/tkinter.html#tkinter-life-preserver
https://docs.python.org/3/library/tkinter.html#how-to-use-this-section
https://docs.python.org/3/library/tkinter.html#a-simple-hello-world-program
https://docs.python.org/3/library/tkinter.html#a-very-quick-look-at-tcl-tk
https://docs.python.org/3/library/tkinter.html#mapping-basic-tk-into-tkinter
https://docs.python.org/3/library/tkinter.html#how-tk-and-tkinter-are-related
https://docs.python.org/3/library/tkinter.html#handy-reference
https://docs.python.org/3/library/tkinter.html#setting-options
https://docs.python.org/3/library/tkinter.html#the-packer
https://docs.python.org/3/library/tkinter.html#packer-options
https://docs.python.org/3/library/tkinter.html#coupling-widget-variables
https://docs.python.org/3/library/tkinter.html#the-window-manager
https://docs.python.org/3/library/tkinter.html#tk-option-data-types
https://docs.python.org/3/library/tkinter.html#bindings-and-events
https://docs.python.org/3/library/tkinter.html#the-index-parameter
https://docs.python.org/3/library/tkinter.html#images
https://docs.python.org/3/library/tkinter.html#file-handlers
https://docs.python.org/3/library/tkinter.ttk.html#module-tkinter.ttk
https://docs.python.org/3/library/tkinter.ttk.html#using-ttk
https://docs.python.org/3/library/tkinter.ttk.html#ttk-widgets
https://docs.python.org/3/library/tkinter.ttk.html#widget
https://docs.python.org/3/library/tkinter.ttk.html#standard-options
https://docs.python.org/3/library/tkinter.ttk.html#scrollable-widget-options
https://docs.python.org/3/library/tkinter.ttk.html#label-options
https://docs.python.org/3/library/tkinter.ttk.html#compatibility-options
https://docs.python.org/3/library/tkinter.ttk.html#widget-states
https://docs.python.org/3/library/tkinter.ttk.html#ttk-widget
https://docs.python.org/3/library/tkinter.ttk.html#combobox
https://docs.python.org/3/library/tkinter.ttk.html#options
https://docs.python.org/3/library/tkinter.ttk.html#virtual-events
https://docs.python.org/3/library/tkinter.ttk.html#ttk-combobox
https://docs.python.org/3/library/tkinter.ttk.html#spinbox
https://docs.python.org/3/library/tkinter.ttk.html#id1
https://docs.python.org/3/library/tkinter.ttk.html#id2
https://docs.python.org/3/library/tkinter.ttk.html#ttk-spinbox
https://docs.python.org/3/library/tkinter.ttk.html#notebook
https://docs.python.org/3/library/tkinter.ttk.html#id3
https://docs.python.org/3/library/tkinter.ttk.html#tab-options
https://docs.python.org/3/library/tkinter.ttk.html#tab-identifiers
https://docs.python.org/3/library/tkinter.ttk.html#id4
https://docs.python.org/3/library/tkinter.ttk.html#ttk-notebook
https://docs.python.org/3/library/tkinter.ttk.html#progressbar
https://docs.python.org/3/library/tkinter.ttk.html#id5
https://docs.python.org/3/library/tkinter.ttk.html#ttk-progressbar
https://docs.python.org/3/library/tkinter.ttk.html#separator
https://docs.python.org/3/library/tkinter.ttk.html#id6
https://docs.python.org/3/library/tkinter.ttk.html#sizegrip
https://docs.python.org/3/library/tkinter.ttk.html#platform-specific-notes
https://docs.python.org/3/library/tkinter.ttk.html#bugs
https://docs.python.org/3/library/tkinter.ttk.html#treeview
https://docs.python.org/3/library/tkinter.ttk.html#id7
https://docs.python.org/3/library/tkinter.ttk.html#item-options
https://docs.python.org/3/library/tkinter.ttk.html#tag-options
https://docs.python.org/3/library/tkinter.ttk.html#column-identifiers
https://docs.python.org/3/library/tkinter.ttk.html#id8
https://docs.python.org/3/library/tkinter.ttk.html#ttk-treeview
https://docs.python.org/3/library/tkinter.ttk.html#ttk-styling
https://docs.python.org/3/library/tkinter.ttk.html#layouts
https://docs.python.org/3/library/tkinter.tix.html#module-tkinter.tix
https://docs.python.org/3/library/tkinter.tix.html#using-tix
https://docs.python.org/3/library/tkinter.tix.html#tix-widgets
https://docs.python.org/3/library/tkinter.tix.html#basic-widgets
https://docs.python.org/3/library/tkinter.tix.html#file-selectors
https://docs.python.org/3/library/tkinter.tix.html#hierarchical-listbox
https://docs.python.org/3/library/tkinter.tix.html#tabular-listbox
https://docs.python.org/3/library/tkinter.tix.html#manager-widgets
https://docs.python.org/3/library/tkinter.tix.html#image-types
https://docs.python.org/3/library/tkinter.tix.html#miscellaneous-widgets
https://docs.python.org/3/library/tkinter.tix.html#form-geometry-manager
https://docs.python.org/3/library/tkinter.tix.html#tix-commands
https://docs.python.org/3/library/tkinter.scrolledtext.html#module-tkinter.scrolledtext

25.1. turtle — Turtle graphics

https://docs.python.org/3/library/turtle.html
https://docs.python.org/3/library/turtle.html#introduction
https://docs.python.org/3/library/turtle.html#overview-of-available-turtle-and-screen-methods
https://docs.python.org/3/library/turtle.html#turtle-methods
https://docs.python.org/3/library/turtle.html#methods-of-turtlescreen-screen
https://docs.python.org/3/library/turtle.html#methods-of-rawturtle-turtle-and-corresponding-functions
https://docs.python.org/3/library/turtle.html#turtle-motion
https://docs.python.org/3/library/turtle.html#tell-turtle-s-state
https://docs.python.org/3/library/turtle.html#settings-for-measurement
https://docs.python.org/3/library/turtle.html#pen-control
https://docs.python.org/3/library/turtle.html#drawing-state
https://docs.python.org/3/library/turtle.html#turtle-state
https://docs.python.org/3/library/turtle.html#using-events
https://docs.python.org/3/library/turtle.html#special-turtle-methods
https://docs.python.org/3/library/turtle.html#compound-shapes
https://docs.python.org/3/library/turtle.html#methods-of-turtlescreen-screen-and-corresponding-functions
https://docs.python.org/3/library/turtle.html#window-control
https://docs.python.org/3/library/turtle.html#animation-control
https://docs.python.org/3/library/turtle.html#using-screen-events
https://docs.python.org/3/library/turtle.html#input-methods
https://docs.python.org/3/library/turtle.html#settings-and-special-methods
https://docs.python.org/3/library/turtle.html#methods-specific-to-screen-not-inherited-from-turtlescreen
https://docs.python.org/3/library/turtle.html#public-classes
https://docs.python.org/3/library/turtle.html#help-and-configuration
https://docs.python.org/3/library/turtle.html#how-to-use-help
https://docs.python.org/3/library/turtle.html#translation-of-docstrings-into-different-languages
https://docs.python.org/3/library/turtle.html#how-to-configure-screen-and-turtles
https://docs.python.org/3/library/turtle.html#module-turtledemo
https://docs.python.org/3/library/turtle.html#changes-since-python-2-6
https://docs.python.org/3/library/turtle.html#changes-since-python-3-0

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
https://docs.python.org/3/library/sunau.html#au-read-objects
https://docs.python.org/3/library/sunau.html#au-write-objects
https://docs.python.org/3/library/wave.html
https://docs.python.org/3/library/wave.html#wave-read-objects
https://docs.python.org/3/library/wave.html#wave-write-objects
https://docs.python.org/3/library/chunk.html
https://docs.python.org/3/library/colorsys.html
https://docs.python.org/3/library/imghdr.html
https://docs.python.org/3/library/sndhdr.html
https://docs.python.org/3/library/ossaudiodev.html
https://docs.python.org/3/library/ossaudiodev.html#audio-device-objects
https://docs.python.org/3/library/ossaudiodev.html#mixer-device-objects

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

6. Text Processing Services

6.3. difflib — Helpers for computing deltas
6.4. textwrap — Text wrapping and filling
6.5. unicodedata — Unicode Database
6.6. stringprep — Internet String Preparation
6.7. readline — GNU readline interface
6.8. rlcompleter — Completion function for GNU readline

https://docs.python.org/3/library/difflib.html
https://docs.python.org/3/library/difflib.html#sequencematcher-objects
https://docs.python.org/3/library/difflib.html#sequencematcher-examples
https://docs.python.org/3/library/difflib.html#differ-objects
https://docs.python.org/3/library/difflib.html#differ-example
https://docs.python.org/3/library/difflib.html#a-command-line-interface-to-difflib
https://docs.python.org/3/library/textwrap.html
https://docs.python.org/3/library/unicodedata.html
https://docs.python.org/3/library/stringprep.html
https://docs.python.org/3/library/readline.html
https://docs.python.org/3/library/readline.html#init-file
https://docs.python.org/3/library/readline.html#line-buffer
https://docs.python.org/3/library/readline.html#history-file
https://docs.python.org/3/library/readline.html#history-list
https://docs.python.org/3/library/readline.html#startup-hooks
https://docs.python.org/3/library/readline.html#completion
https://docs.python.org/3/library/readline.html#example
https://docs.python.org/3/library/rlcompleter.html
https://docs.python.org/3/library/rlcompleter.html#completer-objects

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

## Utilities

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

15.3. secrets — Generate secure random numbers for managing secrets
https://docs.python.org/3/library/secrets.html

https://docs.python.org/3/library/secrets.html#random-numbers
https://docs.python.org/3/library/secrets.html#generating-tokens
https://docs.python.org/3/library/secrets.html#how-many-bytes-should-tokens-use
https://docs.python.org/3/library/secrets.html#other-functions
https://docs.python.org/3/library/secrets.html#recipes-and-best-practices

15. Cryptographic Services
15.1. hashlib — Secure hashes and message digests
15.2. hmac — Keyed-Hashing for Message Authentication

https://docs.python.org/3/library/crypto.html
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

16.9. getpass — Portable password input
16.15. errno — Standard errno system symbols

https://docs.python.org/3/library/getpass.html
https://docs.python.org/3/library/errno.html

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
https://docs.python.org/3/library/posix.html#large-file-support
https://docs.python.org/3/library/posix.html#notable-module-contents
https://docs.python.org/3/library/pwd.html
https://docs.python.org/3/library/spwd.html
https://docs.python.org/3/library/grp.html
https://docs.python.org/3/library/crypt.html
https://docs.python.org/3/library/crypt.html#hashing-methods
https://docs.python.org/3/library/crypt.html#module-attributes
https://docs.python.org/3/library/crypt.html#module-functions
https://docs.python.org/3/library/crypt.html#examples
https://docs.python.org/3/library/termios.html
https://docs.python.org/3/library/termios.html#example
https://docs.python.org/3/library/tty.html
https://docs.python.org/3/library/pty.html
https://docs.python.org/3/library/pty.html#example
https://docs.python.org/3/library/fcntl.html
	   
https://docs.python.org/3/library/nis.html
https://docs.python.org/3/library/syslog.html
https://docs.python.org/3/library/syslog.html#examples
https://docs.python.org/3/library/syslog.html#simple-example

12. Data Persistence
12.1. pickle — Python object serialization

https://docs.python.org/3/library/pickle.html

https://docs.python.org/3/library/pickle.html#relationship-to-other-python-modules
https://docs.python.org/3/library/pickle.html#comparison-with-marshal
https://docs.python.org/3/library/pickle.html#comparison-with-json
https://docs.python.org/3/library/pickle.html#data-stream-format
https://docs.python.org/3/library/pickle.html#module-interface
https://docs.python.org/3/library/pickle.html#what-can-be-pickled-and-unpickled
https://docs.python.org/3/library/pickle.html#pickling-class-instances
https://docs.python.org/3/library/pickle.html#persistence-of-external-objects
https://docs.python.org/3/library/pickle.html#dispatch-tables
https://docs.python.org/3/library/pickle.html#handling-stateful-objects
https://docs.python.org/3/library/pickle.html#restricting-globals
https://docs.python.org/3/library/pickle.html#performance
https://docs.python.org/3/library/pickle.html#examples

https://docs.python.org/3/library/pickletools.html
https://docs.python.org/3/library/pickletools.html#command-line-usage
https://docs.python.org/3/library/pickletools.html#command-line-options
https://docs.python.org/3/library/pickletools.html#programmatic-interface

12. Data Persistence
https://docs.python.org/3/library/persistence.html

12.2. copyreg — Register pickle support functions
https://docs.python.org/3/library/copyreg.html
https://docs.python.org/3/library/copyreg.html#example

12.3. shelve — Python object persistence
https://docs.python.org/3/library/shelve.html
https://docs.python.org/3/library/shelve.html#restrictions
https://docs.python.org/3/library/shelve.html#example

12.5. dbm — Interfaces to Unix “databases”
https://docs.python.org/3/library/dbm.html
https://docs.python.org/3/library/dbm.html#module-dbm.gnu
https://docs.python.org/3/library/dbm.html#module-dbm.ndbm
https://docs.python.org/3/library/dbm.html#module-dbm.dumb

13. Data Compression and Archiving
13.1. zlib — Compression compatible with gzip
13.2. gzip — Support for gzip files
13.3. bz2 — Support for bzip2 compression
13.4. lzma — Compression using the LZMA algorithm
13.5. zipfile — Work with ZIP archives
13.6. tarfile — Read and write tar archive files

https://docs.python.org/3/library/zlib.html

https://docs.python.org/3/library/gzip.html
https://docs.python.org/3/library/gzip.html#examples-of-usage

https://docs.python.org/3/library/bz2.html
https://docs.python.org/3/library/bz2.html#de-compression-of-files
https://docs.python.org/3/library/bz2.html#incremental-de-compression
https://docs.python.org/3/library/bz2.html#one-shot-de-compression

https://docs.python.org/3/library/lzma.html
https://docs.python.org/3/library/lzma.html#reading-and-writing-compressed-files
https://docs.python.org/3/library/lzma.html#compressing-and-decompressing-data-in-memory
https://docs.python.org/3/library/lzma.html#miscellaneous
https://docs.python.org/3/library/lzma.html#specifying-custom-filter-chains
https://docs.python.org/3/library/lzma.html#examples

https://docs.python.org/3/library/zipfile.html
https://docs.python.org/3/library/zipfile.html#zipfile-objects
https://docs.python.org/3/library/zipfile.html#pyzipfile-objects
https://docs.python.org/3/library/zipfile.html#zipinfo-objects
https://docs.python.org/3/library/zipfile.html#command-line-interface
https://docs.python.org/3/library/zipfile.html#command-line-options

https://docs.python.org/3/library/tarfile.html
https://docs.python.org/3/library/tarfile.html#tarfile-objects
https://docs.python.org/3/library/tarfile.html#tarinfo-objects
https://docs.python.org/3/library/tarfile.html#command-line-interface
https://docs.python.org/3/library/tarfile.html#command-line-options
https://docs.python.org/3/library/tarfile.html#examples
https://docs.python.org/3/library/tarfile.html#supported-tar-formats
https://docs.python.org/3/library/tarfile.html#unicode-issues

29.4. zipapp — Manage executable python zip archives

https://docs.python.org/3/library/zipapp.html
https://docs.python.org/3/library/zipapp.html#basic-example
https://docs.python.org/3/library/zipapp.html#command-line-interface
https://docs.python.org/3/library/zipapp.html#python-api
https://docs.python.org/3/library/zipapp.html#examples
https://docs.python.org/3/library/zipapp.html#specifying-the-interpreter
https://docs.python.org/3/library/zipapp.html#creating-standalone-applications-with-zipapp
https://docs.python.org/3/library/zipapp.html#making-a-windows-executable
https://docs.python.org/3/library/zipapp.html#caveats
https://docs.python.org/3/library/zipapp.html#the-python-zip-application-archive-format

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

20.3. mailcap — Mailcap file handling
20.4. mailbox — Manipulate mailboxes in various formats

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

35. MS Windows Specific Services
35.1. msilib — Read and write Microsoft Installer files
35.2. msvcrt — Useful routines from the MS VC++ runtime
35.3. winreg — Windows registry access
35.4. winsound — Sound-playing interface for Windows

https://docs.python.org/3/library/msilib.html
https://docs.python.org/3/library/msilib.html#database-objects
https://docs.python.org/3/library/msilib.html#view-objects
https://docs.python.org/3/library/msilib.html#summary-information-objects
https://docs.python.org/3/library/msilib.html#record-objects
https://docs.python.org/3/library/msilib.html#errors
https://docs.python.org/3/library/msilib.html#cab-objects
https://docs.python.org/3/library/msilib.html#directory-objects
https://docs.python.org/3/library/msilib.html#features
https://docs.python.org/3/library/msilib.html#gui-classes
https://docs.python.org/3/library/msilib.html#precomputed-tables
https://docs.python.org/3/library/msvcrt.html
https://docs.python.org/3/library/msvcrt.html#file-operations
https://docs.python.org/3/library/msvcrt.html#console-i-o
https://docs.python.org/3/library/msvcrt.html#other-functions
https://docs.python.org/3/library/winreg.html
https://docs.python.org/3/library/winreg.html#functions
https://docs.python.org/3/library/winreg.html#constants
https://docs.python.org/3/library/winreg.html#hkey-constants
https://docs.python.org/3/library/winreg.html#access-rights
https://docs.python.org/3/library/winreg.html#bit-specific
https://docs.python.org/3/library/winreg.html#value-types
https://docs.python.org/3/library/winreg.html#registry-handle-objects
https://docs.python.org/3/library/winsound.html

26.5. IDLE
26.6. Other Graphical User Interface Packages

https://docs.python.org/3/library/idle.html
https://docs.python.org/3/library/idle.html#menus
https://docs.python.org/3/library/idle.html#file-menu-shell-and-editor
https://docs.python.org/3/library/idle.html#edit-menu-shell-and-editor
https://docs.python.org/3/library/idle.html#format-menu-editor-window-only
https://docs.python.org/3/library/idle.html#run-menu-editor-window-only
https://docs.python.org/3/library/idle.html#shell-menu-shell-window-only
https://docs.python.org/3/library/idle.html#debug-menu-shell-window-only
https://docs.python.org/3/library/idle.html#options-menu-shell-and-editor
https://docs.python.org/3/library/idle.html#window-menu-shell-and-editor
https://docs.python.org/3/library/idle.html#help-menu-shell-and-editor
https://docs.python.org/3/library/idle.html#context-menus
https://docs.python.org/3/library/idle.html#editing-and-navigation
https://docs.python.org/3/library/idle.html#automatic-indentation
https://docs.python.org/3/library/idle.html#completions
https://docs.python.org/3/library/idle.html#calltips
https://docs.python.org/3/library/idle.html#python-shell-window
https://docs.python.org/3/library/idle.html#text-colors
https://docs.python.org/3/library/idle.html#startup-and-code-execution
https://docs.python.org/3/library/idle.html#command-line-usage
https://docs.python.org/3/library/idle.html#startup-failure
https://docs.python.org/3/library/idle.html#idle-console-differences
https://docs.python.org/3/library/idle.html#developing-tkinter-applications
https://docs.python.org/3/library/idle.html#running-without-a-subprocess
https://docs.python.org/3/library/idle.html#help-and-preferences
https://docs.python.org/3/library/idle.html#additional-help-sources
https://docs.python.org/3/library/idle.html#setting-preferences
https://docs.python.org/3/library/idle.html#extensions
https://docs.python.org/3/library/othergui.html#other-graphical-user-interface-packages

## 2 to 3- Deprecated

Automated Python 2 to 3 code translation
https://docs.python.org/3/library/2to3.html
https://docs.python.org/3/library/2to3.html#using-2to3
https://docs.python.org/3/library/2to3.html#fixers
https://docs.python.org/3/library/2to3.html#module-lib2to3
