# The Python General Index and Module Index- Priority

a- priority
abc		Abstract base classes according to PEP 3119.
argparse	Command-line option and argument parsing library.
array		Space efficient arrays of uniformly typed numeric values.
ast		Abstract Syntax Tree classes and manipulation.
asynchat	Support for asynchronous command/response protocols.
asyncio		Asynchronous I/O, event loop, coroutines and tasks.
asyncore	A base class for developing asynchronous socket handling services.

b- priority
bdb		Debugger framework.
bisect		Array bisection algorithms for binary searching.
builtins	The module that provides the built-in namespace.

c- priority
calendar	Functions for working with calendars, including some emulation of the Unix cal program.
cgi		Helpers for running Python scripts via the Common Gateway Interface.
collections	Container datatypes
compileall	Tools for byte-compiling all Python source files in a directory tree.
concurrent	
cProfile	
ctypes		A foreign function library for Python.

d- priority
dataclasses	Generate special methods on user-defined classes.
datetime	Basic date and time types.
decimal		Implementation of the General Decimal Arithmetic Specification.
dis		Disassembler for Python bytecode.
distutils	Support for building and installing Python modules into an existing Python installation.
doctest		Test pieces of code within docstrings.

e- priority
email		Package supporting the parsing, manipulating, and generating email messages.
encodings	

f- priority
faulthandler	Dump the Python traceback.
fractions	Rational numbers.
functools	Higher-order functions and operations on callable objects.
 
g- priority
gc		Interface to the cycle-detecting garbage collector.
gettext		Multilingual internationalization services.
glob		Unix shell style pathname pattern expansion.

h- priority
heapq		Heap queue algorithm (a.k.a. priority queue).
html		Helpers for manipulating HTML.
http		HTTP status codes and messages
 
i- priority
inspect		Extract information and source code from live objects.
io		Core tools for working with streams.
itertools	Functions creating iterators for efficient looping.
 
j- priority
json		Encode and decode the JSON format.
 	
k- priority
keyword		Test whether a string is a keyword in Python.
 	
l- priority
lib2to3		the 2to3 library
locale		Internationalization services.
logging		Flexible event logging system for applications.

m- priority
marshal		Convert Python objects to streams of bytes and back (with different constraints).
math		Mathematical functions (sin() etc.).
multiprocessing	Process-based parallelism.
 
n- priority
numbers		Numeric abstract base classes (Complex, Real, Integral, etc.).
 
o- priority
operator	Functions corresponding to the standard operators.
os		Miscellaneous operating system interfaces.

p- priority
parser		Access parse trees for Python source code.
pathlib		Object-oriented filesystem paths
pdb		The Python debugger for interactive interpreters.
pipes (Unix)	A Python interface to Unix shell pipelines.
pkgutil		Utilities for the import system.
pprint		Data pretty printer.
profile		Python source profiler.
pstats		Statistics object for use with the profiler.
pydoc		Documentation generator and online help system.
 
q- priority
queue		A synchronized queue class.

r- priority
random		Generate pseudo-random numbers with various common distributions.
re		Regular expression operations.

s- priority
sched		General purpose event scheduler.
shutil		High-level file operations, including copying.
signal		Set handlers for asynchronous events.
site		Module responsible for site-specific configuration.
socket		Low-level networking interface.
socketserver	A framework for network servers.
sqlite3		A DB-API 2.0 implementation using SQLite 3.x.
ssl		TLS/SSL wrapper for socket objects
statistics	mathematical statistics functions
string		Common string operations.
subprocess	Subprocess management.
symbol		Constants representing internal nodes of the parse tree.
symtable	Interface to the compiler's internal symbol tables.
sys		Access system-specific parameters and functions.
sysconfig	Python's configuration information

t- priority
test		Regression tests package containing the testing suite for Python.
threading	Thread-based parallelism.
time		Time access and conversions.
timeit		Measure the execution time of small code snippets.
token		Constants representing terminal nodes of the parse tree.
tokenize	Lexical scanner for Python source code.
trace		Trace or track Python statement execution.
traceback	Print or retrieve a stack traceback.
tracemalloc	Trace memory allocations.
types		Names for built-in types.
typing		Support for type hints (see PEP 484).
 
u- priority
unicodedata	Access the Unicode Database.
unittest	Unit testing framework for Python.
urllib	

v- priority
venv		Creation of virtual environments.
 	
w- priority
warnings	Issue warning messages and control their disposition.
wsgiref		WSGI Utilities and Reference Implementation.
 
## The Python General Index and Module Index

https://docs.python.org/3/genindex.html
https://docs.python.org/3/py-modindex.html

__future__	Future statement definitions
__main__	The environment where the top-level script is run.
_dummy_thread	Drop-in replacement for the _thread module.
_thread	Low-level threading API.
 	
a	
aifc	Read and write audio files in AIFF or AIFC format.
atexit	Register and execute cleanup functions.
audioop	Manipulate raw audio data.
 	
b	
base64		RFC 3548: Base16, Base32, Base64 Data Encodings; Base85 and Ascii85
binascii	Tools for converting between binary and various ASCII-encoded binary representations.
binhex		Encode and decode files in binhex4 format.
bz2		Interfaces for bzip2 compression and decompression.
 	
c	
cgitb		Configurable traceback handler for CGI scripts.
chunk		Module to read IFF chunks.
cmath		Mathematical functions for complex numbers.
cmd		Build line-oriented command interpreters.
code		Facilities to implement read-eval-print loops.
codecs		Encode and decode data and streams.
codeop		Compile (possibly incomplete) Python code.
colorsys	Conversion functions between RGB and other color systems.
configparser	Configuration file parser.
contextlib	Utilities for with-statement contexts.
contextvars	Context Variables
copy		Shallow and deep copy operations.
copyreg		Register pickle support functions.
crypt (Unix)	The crypt() function used to check Unix passwords.
csv		Write and read tabular data to and from delimited files.
curses (Unix)	An interface to the curses library, providing portable terminal handling.
 
d	
dbm		Interfaces to various Unix "database" formats.
difflib		Helpers for computing differences between objects.
dummy_threading	Drop-in replacement for the threading module.

e	
ensurepip	Bootstrapping the "pip" installer into an existing Python installation or virtual environment.
enum		Implementation of an enumeration class.
errno		Standard errno system symbols.
 	
f	
fcntl (Unix)	The fcntl() and ioctl() system calls.
filecmp		Compare files efficiently.
fileinput	Loop over standard input or a list of files.
fnmatch		Unix shell style filename pattern matching.
formatter	Deprecated: Generic output formatter and device interface.
ftplib		FTP protocol client (requires sockets).

g	
getopt		Portable parser for command line options; support both short and long option names.
getpass		Portable reading of passwords and retrieval of the userid.
grp (Unix)	The group database (getgrnam() and friends).
gzip		Interfaces for gzip compression and decompression using file objects.
 	
h	
hashlib		Secure hash and message digest algorithms.
hmac		Keyed-Hashing for Message Authentication (HMAC) implementation
	
i	
imaplib		IMAP4 protocol client (requires sockets).
imghdr		Determine the type of image contained in a file or byte stream.
imp		Deprecated: Access the implementation of the import statement.
importlib	The implementation of the import machinery.
ipaddress	IPv4/IPv6 manipulation library.

l	
linecache	This module provides random access to individual lines from text files.
lzma		A Python wrapper for the liblzma compression library.
 	
m	
macpath		Mac OS 9 path manipulation functions.
mailbox		Manipulate mailboxes in various formats
mailcap		Mailcap file handling.
mimetypes	Mapping of filename extensions to MIME types.
mmap		Interface to memory-mapped files for Unix and Windows.
modulefinder	Find modules used by a script.
msilib (Windows)	Creation of Microsoft Installer files, and CAB files.
msvcrt (Windows)	Miscellaneous useful routines from the MS VC++ runtime.

n	
netrc	Loading of .netrc files.
nis (Unix)	Interface to Sun's NIS (Yellow Pages) library.
nntplib	NNTP protocol client (requires sockets).

o	
optparse	Deprecated: Command-line option parsing library.
ossaudiodev (Linux, FreeBSD)	Access to OSS-compatible audio devices.
 	
p	
pickle	Convert Python objects to streams of bytes and back.
pickletools	Contains extensive comments about the pickle protocols and pickle-machine opcodes, as well as some useful functions.
platform	Retrieves as much platform identifying data as possible.
plistlib	Generate and parse Mac OS X plist files.
poplib	POP3 protocol client (requires sockets).
posix (Unix)	The most common POSIX system calls (normally used via module os).
pty (Linux)	Pseudo-Terminal Handling for Linux.
pwd (Unix)	The password database (getpwnam() and friends).
py_compile	Generate byte-code files from Python source files.
pyclbr	Supports information extraction for a Python class browser.

q	
quopri	Encode and decode files using the MIME quoted-printable encoding.

r	
readline (Unix)		GNU readline support for Python.
reprlib			Alternate repr() implementation with size limits.
resource (Unix)		An interface to provide resource usage information on the current process.
rlcompleter		Python identifier completion, suitable for the GNU readline library.
runpy			Locate and run Python modules without importing them first.
 	
s	
secrets		Generate secure random numbers for managing secrets.
select		Wait for I/O completion on multiple streams.
selectors	High-level I/O multiplexing.
shelve		Python object persistence.
shlex		Simple lexical analysis for Unix shell-like languages.
smtpd		A SMTP server implementation in Python.
smtplib		SMTP protocol client (requires sockets).
sndhdr		Determine type of a sound file.
spwd (Unix)	The shadow password database (getspnam() and friends).
stat		Utilities for interpreting the results of os.stat(), os.lstat() and os.fstat().
stringprep	String preparation, as per RFC 3453
struct		Interpret bytes as packed binary data.
sunau		Provide an interface to the Sun AU sound format.
syslog (Unix)	An interface to the Unix syslog library routines.
 		
t	
tabnanny	Tool for detecting white space related problems in Python source files in a directory tree.
tarfile		Read and write tar-format archive files.
telnetlib	Telnet client class.
tempfile	Generate temporary files and directories.
termios (Unix)	POSIX style tty control.
textwrap	Text wrapping and filling
tkinter		Interface to Tcl/Tk for graphical user interfaces
tty (Unix)	Utility functions that perform common terminal control operations.
turtle		An educational framework for simple graphics applications
turtledemo	A viewer for example turtle scripts

u	
uu		Encode and decode files in uuencode format.
uuid		UUID objects (universally unique identifiers) according to RFC 4122
 		
w	
wave		Provide an interface to the WAV sound format.
weakref		Support for weak references and weak dictionaries.
webbrowser	Easy-to-use controller for Web browsers.
winreg (Windows)	Routines and objects for manipulating the Windows registry.
winsound (Windows)	Access to the sound-playing machinery for Windows.

x	
xdrlib		Encoders and decoders for the External Data Representation (XDR).
xml		Package containing XML processing modules
xmlrpc	
 	
z	
zipapp		Manage executable python zip archives
zipfile		Read and write ZIP-format archive files.
zipimport	support for importing Python modules from ZIP archives.
zlib		Low-level interface to compression and decompression routines compatible with gzip.

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

