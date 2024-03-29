# Python and Django Trends

<!--
What is a Coroutine Anyway?
https://www.youtube.com/watch?v=GSiZkP7cI80
https://github.com/jreese/pycon

Static Types
https://twitter.com/rauchg/status/1217993541730725894
https://alexnixon.github.io/2020/01/14/static-types-are-dangerous.html
-->


<!--
https://twitter.com/newsycombinator/status/1465184263100407808 | Hacker News on Twitter: "CPython's main branch running in the browser with WebAssembly https://t.co/vd59knSJiL" / Twitter

https://twitter.com/ethanhs/status/1464308141105967104 | (2) ethantyping on Twitter: "Thanks to recent commits by @ChristianHeimes, I figured out the correct incantations to build CPython's main branch for the web! This is stock Python running *in the browser*. My scripts to build this are at https://t.co/UxhHLBupj4 Lots of work to fix things though... 👷 https://t.co/gIFlVNpNiX" / Twitter

C-extensions, HPy, EPython
https://github.com/pyhandle/hpy | pyhandle/hpy: HPy: a better API for Python
"The PEP summarizes the research work I'm doing on CPython C API since 2017 and the changes that me and others made since Python 3.7 towards an opaque C API. It is also a collaboration with developers of PyPy, HPy, Rust-CPython and many others! Thanks to everyone who helped me!"
https://twitter.com/VictorStinner/status/1248666328984059905
"HPy (https://github.com/pyhandle/hpy) is a joint project which is being developed by PyPy, CPython and Cython developers. It aims to design a better C API for writing #Python extensions"
https://twitter.com/trebor74hr/status/1252729526540472323
https://twitter.com/teoliphant/status/1203341184481054720 | Travis Oliphant on Twitter: "Given I've spent many years actually writing many popular C-extensions for Python, please take note of this strong recommendation! https://t.co/U5MPMTlOcp" / Twitter
https://twitter.com/teoliphant/status/1217611221396082695


## Browser, Extensions, Bindings


Cuda Python
https://developer.nvidia.com/cuda-toolkit


Python Browser
https://brython.info/
Traversy Media Brython tutorial
https://m.youtube.com/watch?feature=youtu.be&v=VJj-H4we71g
https://wxpython.org/ | Welcome to wxPython! | wxPython
https://github.com/pyodide/pyodide

Webassembly
https://github.com/iodide-project/pyodide | iodide-project/pyodide: The Python scientific stack, compiled to WebAssembly

Pyodide WASM backend
https://github.com/pyodide/pyodide/blob/89682dabfe32cb9f6508a18a5e838e349801675a/packages/matplotlib/src/wasm_backend.py
https://twitter.com/DynamicWebPaige/status/1454250209387577348 | 👩‍💻 Paige Bailey #BlackLivesMatter on Twitter: "Reading source is a healthy reminder that our entire Python OSS world is built out of LEGO by a scrappy contingent of brilliant, resourceful humans: https://t.co/EV0CHVZQOk "distutils has no cross-compilation story. This is a hack, which miraculously works, to get around that." https://t.co/W9udcIm8YA" / Twitter

Pyodide, WebAssembly
https://the-algorithms.com/ | The Algorithms
https://twitter.com/DynamicWebPaige/status/1452863201125625862 | 👩‍💻 Paige Bailey #BlackLivesMatter on Twitter: "🤔Oh, interesting! TIL that https://t.co/2aJizm5TLk, @Github's largest open-source algorithms library, lists the #Pyodide project as a dependency for its Python code samples (Pyodide = the Python data science stack in the browser, powered by WebAssembly). https://t.co/vO20DZXXXl https://t.co/loPOQpU5oe" / Twitter
https://github.com/TheAlgorithms/website/tree/8a0c439788c54b64ced9c468d56ec43a5d7b140e | TheAlgorithms/website at 8a0c439788c54b64ced9c468d56ec43a5d7b140e


PyOxidizer
A tool for roducing binaries that embed Python
https://github.com/indygreg/PyOxidizer

## Rust

Python- Rust Bindings
https://pyo3.rs/v0.12.3/ | Introduction - PyO3 user guide
https://github.com/PyO3/pyo3 | PyO3/pyo3: Rust bindings for the Python interpreter
https://github.com/PyO3/setuptools-rust | PyO3/setuptools-rust: Setuptools plugin for Rust support

## Python Extensions

https://pythonspeed.com/articles/rust-cython-python-extensions/ | Cython, Rust, and more: choosing a language for Python extensions

C-Extensions for Python
https://cython.org/

Assembly Extensions
https://tonybaloney.github.io/posts/extending-python-with-assembly.html | Writing Python Extensions in Assembly

## Python C API

Python C API
https://docs.python.org/3/c-api/stable.html | C API Stability — Python 3.10.0 documentation
https://pythoncapi.readthedocs.io/ | Design a new better C API for Python — pythoncapi 0.1 documentation
https://pythoncapi.readthedocs.io/runtime.html
https://github.com/Quansight-Labs/python-api-inspect/blob/master/inspect_api/inspect.py | python-api-inspect/inspect.py at master · Quansight-Labs/python-api-inspect

https://docs.python.org/3/c-api/stable.html | Stable Application Binary Interface — Python 3.9.5 documentation
https://docs.python.org/3/c-api/arg.html#other-objects | Parsing arguments and building values — Python 3.8.2 documentation

## C++ and Python

C++ and Python
https://github.com/boostorg/python | boostorg/python: Boost.org python module
-->


### Python on Other Platforms

Rust
* [Rust](https://www.rust-lang.org/)
* [Rust Roadmap 2019](https://blog.rust-lang.org/2019/04/23/roadmap.html)

Python Rust/WebAssembly
* [Rust-Python GitHub](https://github.com/RustPython/RustPython) and [Rust Python Demo](https://rustpython.github.io/demo)
* [PyBee Ouroboros GitHub (implementation of Python)](https://github.com/pybee/ouroboros)
* [Łukasz Langa Twitter Thread](https://twitter.com/llanga/status/1091974732017266688)
* [My Tweet](https://twitter.com/KatiMichel/status/1092140998325497856)
* [Jeff's Tweet](https://twitter.com/webology/status/1092147352813613057)

* [PyOxidizer GitHub](https://github.com/indygreg/PyOxidizer)

<!--
https://blog.rust-lang.org/2020/03/12/Rust-1.42.html

Rust
https://dropbox.tech/infrastructure/rewriting-the-heart-of-our-sync-engine
https://stackoverflow.blog/2020/01/20/what-is-rust-and-why-is-it-so-popular/
https://medium.com/@JoeKreydt/rusts-complexity-problem-a-warning-55c3a6484038

https://words.steveklabnik.com/a-sad-day-for-rust
https://github.com/fafhrd91/actix-web

WASM
https://webassembly.org/
https://emscripten.org/ | Main — Emscripten 1.39.0 documentation
asm.js
http://asmjs.org/
https://webassembly.studio/ | WebAssembly Studio

Why Python
https://www.youtube.com/watch?v=qTNJ7E8AnQI | Russel keith-magee - keynote - YouTube
Python Black Swans
https://www.youtube.com/watch?v=ftP5BQh1-YM | (1) Russell Keith-Magee - Keynote - PyCon 2019 - YouTube
Web Assembly
https://2019.pycon-au.org/talks/wasm-matter | PyCon AU 2019 | WASM matter?

https://pyfound.blogspot.com/2019/05/russell-keith-magee-python-on-other.html | Python Software Foundation News: Russell Keith-Magee: Python On Other Platforms

## Rust

Rust
https://hacks.mozilla.org/2016/11/rust-and-the-future-of-systems-programming/ | Rust and the Future of Systems Programming - Mozilla Hacks - the Web developer blog
https://slides.com/raiderrobert/rust-borrowing-pytn#/11 | Rust: Borrowing
https://bitbucket.org/blog/why-rust | Why we chose Rust as our programming language
https://drewdevault.com/2019/03/25/Rust-is-not-a-good-C-replacement.html | Rust is not a good C replacement | Drew DeVault’s Blog
https://developers.redhat.com/blog/2017/11/16/speed-python-using-rust/ | Speed up your Python using Rust - Red Hat Developer Blog

## PyOxidizer

PyOxidizer- Python and Rust
https://twitter.com/andrewgodwin/status/1143982061524418560 | Twitter
https://twitter.com/di_codes/status/1143973324961304576
https://gregoryszorc.com/blog/2019/06/24/building-standalone-python-applications-with-pyoxidizer/ | Gregory Szorc's Digital Home | Building Standalone Python Applications with PyOxidizer
https://twitter.com/indygreg/status/1143187250743668736 | indygreg on Twitter: "I'm excited to announce the initial release of PyOxidizer - a utility for producing standalone Python applications and which empowers Python and Rust to leverage each other! https://t.co/qZ5Wpjthkn"
https://pyoxidizer.readthedocs.io/en/latest/comparisons.html

## Pyodide

Pyodide/Web Assembly
https://github.com/iodide-project/pyodide | iodide-project/pyodide: The Python scientific stack, compiled to WebAssembly
https://hacks.mozilla.org/2019/04/pyodide-bringing-the-scientific-python-stack-to-the-browser/ | Pyodide: Bringing the scientific Python stack to the browser - Mozilla Hacks - the Web developer blog
https://github.com/wasmerio/python-ext-wasm | wasmerio/python-ext-wasm: 🐍🕸 Python extension to run WebAssembly binaries.
https://twitter.com/wasmerio/status/1146477876151115776 | Wasmer on Twitter: "🔥 This is BIG. Using Wasmer 0.5.2 you can run the #Python interpreter ported to #WebAssembly (based on Pyodide) $ wasmer self-update $ wapm install python https://t.co/Oj9RryDrs5… https://t.co/WYMPMDJbNN"
-->


### Python Gilectomy and Multi-Core

* [Gilectomy](https://github.com/larryhastings/gilectomy/)

<!--
Implementations
* [Python Alternate Implementations](https://docs.python.org/3/reference/introduction.html#alternate-implementations)
* [Intel® Python Distribution (GIL)](https://software.intel.com/en-us/distribution-for-python)

https://pythoncapi.readthedocs.io/roadmap.html | Roadmap for a new Python C API — pythoncapi 0.1 documentation
https://pythoncapi.readthedocs.io/runtime.html | Reorganize Python “runtime” — pythoncapi 0.1 documentation
https://mail.python.org/archives/list/capi-sig@python.org/message/VKKNX4ECZTCRGYMAJJA4VWPVXC257W62/ | Mailman 3 [capi-sig] Re: [capi-sig]How to access the various levels of runtime state (e.g. PyInterpreterState, _PyRuntimeState)? - capi-sig - python.org

Multi Core
https://twitter.com/ericsnowcrntly/status/1190339948286636032
https://github.com/ericsnowcurrently/multi-core-python | ericsnowcurrently/multi-core-python: Enabling CPython multi-core parallelism via subinterpreters.
https://twitter.com/dontusethiscode/status/1130240042457288705 | James Powell on Twitter: "Pure* Python sub-interpreters without all the hard work of @ericsnowcrntly's PEP-554 (https://t.co/w6aNg3SINI) (Don't actually do this… or do; it's none of my business.)… https://t.co/ZoYRyT58dI"

https://www.python.org/dev/peps/pep-0554/ | PEP 554 -- Multiple Interpreters in the Stdlib | Python.org
https://en.wikipedia.org/wiki/Communicating_sequential_processes | Communicating sequential processes - Wikipedia

https://twitter.com/raymondh/status/1100151553879470080 | Raymond Hettinger on Twitter: "#python 3.8 news: The second alpha release out today. Please try it out. One major feature that we've needed for a long time is shared memory for multiprocessing. Our story for multi-core just got a lot better ;-) Thank you Davin Potts! https://t.co/3GBUtiYCPn"

Larry Hastings Gilectomy
https://realpython.com/python-gil/ | What is the Python Global Interpreter Lock (GIL)? – Real Python
https://lwn.net/Articles/754577/
https://hackernoon.com/has-the-python-gil-been-slain-9440d28fa93d | Has the Python GIL been slain? – Hacker Noon
-->

### Python Sync and Async Tools

<!--
https://snarky.ca/how-the-heck-does-async-await-work-in-python-3-5/ | How the heck does async/await work in Python 3.5?

https://realpython.com/async-io-python/

https://twitter.com/judy2k/status/1189915326630256642
https://pgjones.dev/blog/flask-async-quart-sync-2019/
-->

ASGI (WSGI is for synchronous Python apps, ASGI is for both asynchronous and synchronous apps)
* [ASGI (Asynchronous Server Gateway Interface)](https://asgi.readthedocs.io)
* [ASGI 3.0](https://www.aeracode.org/2019/03/20/asgi-30/)
* [Hello ASGI](https://www.encode.io/articles/hello-asgi/)
* [ASGI Scope GitHub](https://github.com/simonw/asgi-scope/)

asgiref (ASGI in-memory channel layer)
* [asgiref GitHub](https://github.com/django/asgiref)

<!--
https://github.com/django/asgiref/commit/2d29f99cba65c25870aa90f74cbeb694ef7e7445 | Add a thread_sensitive mode to SyncToAsync · django/asgiref@2d29f99
https://github.com/django/asgiref/commit/85b80b071b946281bf7aa2440151740be51a8938 | Improved thread_sensitive implementation · django/asgiref@85b80b0
https://github.com/django/asgiref/blob/master/specs/www.rst
-->

Channels ASGI
* [Channels ASGI](https://channels.readthedocs.io/en/latest/asgi.html)

Uvicorn (ASGI Server); See also Daphne
* [Uvicorn](http://www.uvicorn.org) and [Uvicorn GitHub](https://github.com/encode/uvicorn)

Starlette (ASGI Framework)
* [Starlette](https://www.starlette.io) and [Starlette GitHub](https://github.com/encode/starlette)

<!--
Starlette
https://twitter.com/_tomchristie/status/1179780064927535104

https://github.com/tartiflette/tartiflette-starlette | tartiflette/tartiflette-starlette: ASGI support for the Tartiflette GraphQL engine
-->

asigram
* [asigram ASGI/Telegram Protocol Server GitHub](https://github.com/andrewgodwin/asgigram/)
* [Telegram APIs](https://core.telegram.org/)

API Star
* [API Star Docs](https://docs.apistar.com) and [API Star GitHub](https://github.com/encode/apistar)
* [API Star Discuss](https://discuss.apistar.org)

Tornado and Twisted
* [Tornado (asynchronous networking library)](https://www.tornadoweb.org) and [GitHub Tornado](https://github.com/tornadoweb/tornado)
* [Twisted](https://twistedmatrix.com) and [Twisted GitHub](https://github.com/twisted/twisted)
* [Amber Brown: "50,000,000 Twisted Downloads Can't Be Wrong"](https://atleastfornow.net/posts/py2-py3-twisted-downloads/)

Eventlet and Greenlet
* [Eventlet](https://eventlet.net)
* [Greenlet](https://greenlet.readthedocs.io)
* [gevent-socketio](https://learn-gevent-socketio.readthedocs.io)

<!--
https://trio.readthedocs.io/en/stable/ | Trio: a friendly Python library for async concurrency and I/O — Trio 0.13.0 documentation
https://github.com/python-trio/trio | python-trio/trio: Trio – a friendly Python library for async concurrency and I/O
https://docs.python.org/3/library/asyncio.html

https://github.com/florimondmanca/awesome-asgi | florimondmanca/awesome-asgi: A curated list of awesome ASGI servers, frameworks, apps, libraries, and other resources
https://github.com/timofurrer/awesome-asyncio | timofurrer/awesome-asyncio: A curated list of awesome Python asyncio frameworks, libraries, software and resources

https://learn-gevent-socketio.readthedocs.io/en/latest/general_concepts.html | General concepts: concurrency, parallelism, threads and processes — Real-time apps with gevent-socketio 0.1.0 documentation
-->

### Django Sync and Async Tools

<!--
https://lucumr.pocoo.org/2020/1/1/async-pressure/ | I'm not feeling the async pressure | Armin Ronacher's Thoughts and Writings

https://twitter.com/webKnjaZ/status/1231116234659373061 | Sviatoslove.py🐍 👨‍💻🏡:🇨🇿🇪🇺 @Ansible @RedHat on Twitter: ".@andrewgodwin: the timeline of how async appeared in #Python #PyConBY https://t.co/gqsdHJwRCd" / Twitter
-->

Async DEP
* [DEP 0009: Async-Capable Django](https://github.com/django/deps/blob/master/accepted/0009-async.rst)

Google Groups
* [Django Async DEP Mailing List](https://groups.google.com/forum/#!topic/django-developers/5CVsR9FSqmg)
* [Django Async Roadmap](https://groups.google.com/forum/#!topic/django-developers/Kw7-xV6TrSM)

Major Talks
* [Andrew Godwin: "Just Add Await: Retrofitting Async Into Django" (DjangoCon US 2019](https://www.youtube.com/watch?v=d9BAUBEyFgM)
* [Andrew Godwin: "Just Add Await: Retrofitting Async Into Django" (PyCon AU 2019](https://www.youtube.com/watch?v=oMHrDy62kgE)
* [Tom Christie: "Sketching out a Django Redesign" (DjangoCon Europe 2019)](https://www.youtube.com/watch?v=u8GSFEg5lnU)
* [Andrew Godwin: "Taking Django Async" (DjangoCon Europe 2018)](https://www.youtube.com/watch?v=-7taKQnndfo)
* [Andrew Godwin: "Taking Django Async" (PyCon 2018)](https://www.youtube.com/watch?v=-7taKQnndfo&t=783s)

<!--
https://twitter.com/hops_and_smoke/status/1176927059920089088 | Drew on Twitter: "Here's @glasnt introducing @andrewgodwin's talk about adding async to Django @djangocon https://t.co/YkOv7aRWpU" / Twitter

https://2019.pycon-au.org/talks/just-add-await-retrofitting-async-into-django | PyCon AU 2019 | Just Add Await: Retrofitting Async Into Django
https://speakerdeck.com/andrewgodwin/just-add-await-retrofitting-async-into-django?slide=94 | Just Add Await: Retrofitting Async Into Django - Speaker Deck

https://members.2019.djangocon.eu/conference/talk/GQKCWS/
-->

Async Added to Django 3.0
* [Andrew's Tweet](https://twitter.com/andrewgodwin/status/1141743503036149760)
* [PR: "Added ASGI handler and coroutine-safety"](https://github.com/django/django/pull/11209)
* [Django ASGI handler](https://github.com/django/django/blob/master/django/core/handlers/asgi.py)

<!--
https://github.com/django/django/compare/master...andrewgodwin:async_views | Comparing django:master...andrewgodwin:async_views · django/django
-->

Important Blog Posts
* [Andrew Godwin: "A Django Async Roadmap"](http://www.aeracode.org/2018/06/04/django-async-roadmap)
* [Andrew Godwin: "Python & Async Simplified"](https://www.aeracode.org/2018/02/19/python-async-simplified/)
* [Andrew Godwin: "Beyond Request-Response"](http://www.aeracode.org/2015/6/17/beyond-request-response/)

<!--
https://twitter.com/andrewgodwin/status/1153030952915890177
https://groups.google.com/forum/#!msg/django-developers/5CVsR9FSqmg/UiswdhLECAAJ
https://groups.google.com/forum/#!topic/django-developers/_314PGl3Ao0 | On ASGI... - Google Groups

https://twitter.com/andrewgodwin/status/1157170693508759553
https://code.djangoproject.com/wiki/AsyncProject

https://github.com/simonw/djng | simonw/ding: Turtles all the way down
https://twitter.com/andrewgodwin/status/1143026705033916417
https://simonwillison.net/2009/May/19/djng/?#turtles-all-the-way-down | djng—a Django powered microframework

https://twitter.com/andrewgodwin/status/1151714269987135488
https://twitter.com/simonw/status/1151832243242803203 | Simon Willison on Twitter: "Some beautifully commented code https://t.co/Opj8S4hCSd" / Twitter
-->

Django Async- General
* [Jacob Kaplan-Moss Tweet](https://twitter.com/jacobian/status/1126557544934182913)
* [Another Jacob Kaplan-Moss Tweet](https://twitter.com/jacobian/status/1176938038942781440)

<!--
https://twitter.com/_tomchristie/status/1003631550808887297 | Tom Christie on Twitter: "Really impressed and excited by @andrewgodwin proposal for an iterative approach to adding async support to Django. I think this is super-important for Django's long-term prospects, and if it's going to ever happen then this'd be the right tack for getting there.… https://t.co/DiILuVpbXZ"
https://twitter.com/ChatDjango/status/1217506839744651264 | Django Chat Podcast on Twitter: "Ep46 - Django's Async Future with @_tomchristie is now live! Tom is the creator of Django REST Framework, HTTPX, and a whole suite of new async Python web stack packages. https://t.co/f93I2V9BsJ" / Twitter
-->

Django Channels (Built on ASGI)
* [Channels](https://channels.readthedocs.io) and [Channels GitHub](https://github.com/django/channels)
* [Channels Examples GitHub](https://github.com/andrewgodwin/channels-examples)
* [Daphne (Django Channels HTTP/WebSocket Server)](https://github.com/django/daphne)

<!--
https://github.com/andrewgodwin/channels-examples/blob/master/multichat/chat/consumers.py
https://twitter.com/webology/status/1255226205206429701

https://twitter.com/_tomchristie/status/1230538726310322177 | Tom Christie on Twitter: "@andrewgodwin We'll probably *also* end up with some CBVs in Starlette that look super-similar to Channels implementations, tho it's nice to be able to demo the API at the plain-old function level to show what's going on." / Twitter

Channels
https://mobile.twitter.com/carltongibson/status/1207397901250564096

https://github.com/django/channels/releases/tag/2.0.0
https://github.com/django/channels/releases/tag/1.0.0
https://github.com/django/channels/releases/tag/0.1

https://channels.readthedocs.io/en/latest/releases/2.3.0.html | 2.3.0 Release Notes — Channels 2.3.0 documentation

Django Channels in Practice
https://pyvideo.org/pycon-us-2019/django-channels-in-practice.html
https://us.pycon.org/2019/speaker/profile/573/

https://www.youtube.com/watch?v=xEW8kWQqEew | Andrew Godwin about Channels at Django: Under The Hood 2016 - YouTube

https://speakerdeck.com/andrewgodwin/concurrency-to-channels | Concurrency to Channels // Speaker Deck
https://speakerdeck.com/andrewgodwin/a-brief-history-of-channels

https://www.aeracode.org/2018/02/02/channels-20/ | Channels 2.0 - Aeracode
http://www.aeracode.org/2017/7/11/towards-channels-20/

https://github.com/django/channels/commit/fb6b467c7a7bdd203e25851684742dc48ec1ea42 | Add auth and session support · django/channels@fb6b467

https://github.com/jacobian/demo-thing
https://blog.heroku.com/archives/2016/3/17/in_deep_with_django_channels_the_future_of_real_time_apps_in_django
-->

Django API Star
* [Django API Star](https://github.com/lucianoratamero/django_apistar)

<!--
https://github.com/encode/broadcaster | encode/broadcaster: Broadcast channels for async web apps. 📢

https://www.python.org/dev/peps/pep-3119/ | PEP 3119 -- Introducing Abstract Base Classes | Python.org
https://www.python.org/dev/peps/pep-0492/ | PEP 492 -- Coroutines with async and await syntax | Python.org

http://libuv.org/
https://github.com/libuv/libuv | libuv/libuv: Cross-platform asynchronous I/O

https://github.com/MagicStack/uvloop/releases/tag/v0.13.0 | Release v0.13.0 · MagicStack/uvloop
https://github.com/RobertoPrevato/BlackSheep | RobertoPrevato/BlackSheep: HTTP Server/Client microframework for Python asyncio, using Cython, uvloop, and httptools.

https://www.techempower.com/benchmarks/ | Round 17 results - TechEmpower Framework Benchmarks
https://github.com/TechEmpower/FrameworkBenchmarks | TechEmpower/FrameworkBenchmarks: Source for the TechEmpower Framework Benchmarks project

https://github.com/tomchristie?tab=repositories | tomchristie (Tom Christie) / Repositories

https://github.com/encode/requests-async
http://docs.python-requests.org/en/master/ | Requests: HTTP for Humans™ — Requests 2.21.0 documentation
https://github.com/encode/databases

https://aiohttp.readthedocs.io/en/stable/ | Welcome to AIOHTTP — aiohttp 3.4.4 documentation
https://github.com/aio-libs/aiohttp | aio-libs/aiohttp: Asynchronous HTTP client/server framework for asyncio and Python
https://github.com/aio-libs/aiohttp-demos | aio-libs/aiohttp-demos: Demos for aiohttp project
https://github.com/aio-libs/async-timeout | aio-libs/async-timeout: asyncio-compatible timeout class

https://github.com/encode/httpx

https://github.com/python-http/python-http.org
https://github.com/python-http/discussions | python-http/discussions: Public discussions for the Python HTTP Working Group
https://github.com/encode/httpcore | encode/httpcore
https://github.com/pirate/django-http2-middleware

https://github.com/encode/http3 | encode/http3: A next generation HTTP client, for Python 3. 🦋

HTTP/3
https://github.com/aiortc/aioquic | aiortc/aioquic: QUIC implementation in Python
https://twitter.com/_tomchristie/status/1131617638793269248 | Tom Christie on Twitter: "Really excited about the potential of this one. First steps towards HTTP/3 support for Python servers and clients.… "
-->

### Data Classes

Data Classes
* [PEP 557- Data Classes](https://www.python.org/dev/peps/pep-0557)

<!--
https://github.com/ericvsmith/dataclasses | ericvsmith/dataclasses

https://pypi.python.org/pypi/dataclasses | dataclasses 0.3 : Python Package Index

https://realpython.com/python-data-classes/
-->

### Python Walrus Operator and Assignment Expressions

<!--
https://twitter.com/emilyemorehouse/status/1184484468532404224 | Emily Morehouse-Valcarcel on Twitter: "Still pinching myself. ☺️ Assignment expressions have LANDED – go upgrade all the things to Python 3.8! https://t.co/xVHwWFapOU" / Twitter

https://www.youtube.com/watch?v=6uAvHOKofws | (1) Dustin Ingram - PEP 572: The Walrus Operator - PyCon 2019 - YouTube
https://www.youtube.com/watch?v=mHOgGuALfNc | PEP 572: The Walrus Operator (Dustin Ingram) - YouTube
https://dustingram.com/talks/2019/04/04/the-walrus-operator/ | PEP 572: The Walrus Operator - Dustin Ingram
-->
