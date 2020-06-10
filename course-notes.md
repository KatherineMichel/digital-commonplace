# Course Notes

## General Notes

<!--
HTMl and CSS
https://developer.mozilla.org/en-US/docs/Web/HTML/Element | HTML elements reference - HTML: Hypertext Markup Language | MDN
https://developer.mozilla.org/en-US/docs/Web/CSS | CSS: Cascading Style Sheets | MDN

https://twitter.com/unclebobmartin/status/1010660993851117569 | Uncle Bob Martin on Twitter: "Programs are made up of Dijkstra’s three structures: Sequence, Selection, and Iteration. Each of these is based upon jumps. Sequential statements jump from the end of the first to be beginning of the second."

https://www.python.org/dev/peps/pep-0008/#indentation | PEP 8 -- Style Guide for Python Code | Python.org

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


## CPython Internals Book

<!--
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

### Final Project

<!--
Stanford Reflections
https://twitter.com/faridaelchuzade/status/1266107357496578050 | Farida Elchuzade on Twitter: "We have come to the end of 'Code in Place' Program organized by great professors and leaders of Stanford University. I made a sketch-note to summarize the topics I learned during the 5-week program. Let me know your thoughts about the note😊 #codeinplace #sketchandcode https://t.co/94bbbijduq" / Twitter

Simba
https://us.edstem.org/courses/490/lessons/1236/slides/6413 | Code in Place – Lessons

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
