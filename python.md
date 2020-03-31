# Python

<!--
OS Automation
https://twitter.com/bketelsen/status/1238487322875871232

GitHub Actions- Hynek
https://hynek.me/articles/python-github-actions/
https://github.com/actions/virtual-environments/blob/master/images/linux/Ubuntu1804-README.md
https://twitter.com/hynek/status/1236227708746596353
https://github.com/Azure/actions

https://github.com/sdras/awesome-actions

cross linter - Google Search

CLI
https://github.com/google/python-fire/releases/tag/v0.2.0 | Release v0.2.0 · google/python-fire

https://pyformat.info/

https://www.youtube.com/watch?v=qt7TboNJGJg
-->

<!--
Pinax
https://pypi.org/project/django-utils/ | django-utils · PyPI
https://docs.python.org/3/library/distutils.html | distutils — Building and installing Python modules — Python 3.8.1 documentation

https://docs.python.org/3/distutils/setupscript.html | 2. Writing the Setup Script — Python 3.8.1 documentation
https://setuptools.readthedocs.io/en/latest/setuptools.html | Building and Distributing Packages with Setuptools — setuptools 45.0.0 documentation
https://en.wikipedia.org/wiki/Setuptools
https://github.com/pypa/wheel
-->

<!--
Radix
https://twitter.com/hynek/status/1189883958294654978

Very important!!!!!!!
https://github.com/python-leap/book | python-leap/book: Pythonic Application Architecture Patterns, the Book
https://twitter.com/hjwp/status/1124403310721753088 | Harry Percival on Twitter: "@KatiMichel @brandon_rhodes new book - https://t.co/F9aJA1zWZH feedback high or low level much appreciated!"

https://www.b-list.org/weblog/2017/apr/03/testing-django-apps/ | Let's talk about testing Django apps
https://lincolnloop.com/blog/using-setuppy-your-django-project/ | Using setup.py in Your (Django) Project | Lincoln Loop
https://www.ericholscher.com/blog/2009/jun/29/enable-setuppy-test-your-django-apps/ | Enable setup.py test in your Django apps — Eric Holscher - Surfing in Kansas

Tool Choices
https://simonwillison.net/2020/Feb/11/cheating-at-unit-tests-pytest-black/
This is a good starting point for getting Python, Django, Postgres running as a service, pytest, black, and pip caching rolling with GitHub Actions.
https://mobile.twitter.com/webology/status/1195163668440334337
https://mobile.twitter.com/brettsky/status/1223731773147766784
https://twitter.com/gvanrossum/status/1227126706089021440
https://twitter.com/mariatta/status/1227286873413799936
https://twitter.com/jonasrk/status/1227028183469449216
https://twitter.com/WillingCarol/status/1227331652046770176
https://twitter.com/jacobian/status/1150072802801848320 | jacobian on Twitter: "This is my standard setup too. It's lovely, probably prevents half or more of the silly mistakes I'm prone to making.… https://t.co/ADRHdOq6A3"
https://twitter.com/hawkieowl/status/1150038262540431361 | -mtune=hawk -march=owl on Twitter: "But, anyway. The Ideal Python Development environment for me uses attrs in the code, black and isort to autoformat, flake8/pyflakes to verify, and tox and @nedbat 's Coverage to test. And pytest, if you don't have a particular affinity for xUnit like me :P"

Tools Release
https://twitter.com/tiangolo/status/1208366425880059904 | Sebastián Ramírez on Twitter: "Let's make these guys Python Software Foundation fellows! @_tomchristie created DRF, Starlette, Uvicorn, MkDocs, HTTPX. @sethmlarson maintains urllib3, the most downloaded Python package daily, used by ...everything. https://t.co/CSzLlQ0PUM" / Twitter
https://github.com/tomwojcik/starlette-context | tomwojcik/starlette-context: Middleware for Starlette (and FastAPI) that allows you to store and access context data, like correlation id or metadata.
https://twitter.com/_tomchristie/status/1215240517962870784 | Tom Christie on Twitter: "Our latest release of HTTPX now has both sync &amp; async support again. 👍🎉 HTTPX 0.11 gives you: * A fully featured requests-like API. * Sync &amp; Async support. * Support for both asyncio and Trio. * HTTP/1.1 (both cases) and HTTP/2 (currently async only). https://t.co/BDO5YRdH35" / Twitter

PyPy
https://twitter.com/pypyproject/status/1209476917012897792 | The PyPy Project on Twitter: "Happy Holidays from the PyPy team! Matti just released PyPy 7.3 🎉🎉🎉! The highlight is manylinux2010 wheel support, also the default Linux builds are now portable and should run on many Linux variants https://t.co/eqCTWDgqoF" / Twitter

http://rahmonov.me/posts/write-python-framework-part-one/ | How to write a Python web framework. Part I.	

Django versus Flask
https://adamj.eu/tech/2019/04/03/django-versus-flask-with-single-file-applications/

Python security
https://github.com/guardrailsio/awesome-python-security | guardrailsio/awesome-python-security: Awesome Python Security resources 🕶🐍🔐

Python Language Server
https://blogs.msdn.microsoft.com/pythonengineering/2018/07/18/introducing-the-python-language-server/ | Introducing the Python Language Server – Python at Microsoft
https://microsoft.github.io/language-server-protocol/specification
https://github.com/Microsoft/python-language-server
https://github.com/palantir/python-language-server | palantir/python-language-server: An implementation of the Language Server Protocol for Python
-->

<!--
## Talks

Contributing- Important
https://github.com/python-attrs/attrs/blob/master/.github/CONTRIBUTING.rst

Not sure...
https://setuptools.readthedocs.io/en/latest/setuptools.html#declaring-extras-optional-features-with-their-own-dependencies

General
https://twitter.com/jacobian/status/1115362291099283456

https://github.com/python-attrs/attrs/blob/de84609505845edc0e05c2ff918a44085816e35e/tox.ini#L63-L71
http://mypy-lang.org/

Formatting and Stuff
https://github.com/python-attrs/attrs/blob/de84609505845edc0e05c2ff918a44085816e35e/pyproject.toml#L6-L7
https://treyhunner.com/2017/07/craft-your-python-like-poetry/

https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/setup.cfg#L20-L31
https://prettier.io/
https://github.com/python-attrs/attrs/blob/master/.pre-commit-config.yaml

Docs
https://www.sphinx-doc.org/en/master/
https://www.ericholscher.com/blog/2016/mar/15/dont-use-markdown-for-technical-docs/
https://readthedocs.org/
https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html
https://readthedocs.org/accounts/login/?next=/accounts/gold/
https://pypi.org/project/towncrier/
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/docs/conf.py#L37-L42
https://www.sphinx-doc.org/en/master/usage/extensions/autodoc.html
https://raw.githubusercontent.com/python-attrs/attrs/master/docs/api.rst
https://www.sphinx-doc.org/en/master/usage/extensions/doctest.html
https://docs.python.org/3/library/doctest.html
https://www.sphinx-doc.org/en/master/usage/extensions/intersphinx.html
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/docs/conf.py#L157
https://docs.python.org/3/library/logging.html#logging.getLogger
https://github.com/python-attrs/attrs/blob/de84609505845edc0e05c2ff918a44085816e35e/tox.ini#L47-L53
https://jml.io/pages/test-docstrings.html

Mariatta- build the bot
https://www.youtube.com/watch?v=_xdEAxLuj9Y

Hynek
Azure Pipelines
https://hynek.me/articles/simple-python-azure-pipelines/ | Python in Azure Pipelines, Step by Step · Homepage of Hynek Schlawack
https://docs.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops&tabs=yaml | Container Jobs in Azure Pipelines and TFS - Azure Pipelines | Microsoft Docs

Azure Piplines
https://azure.microsoft.com/en-us/services/devops/pipelines/
https://docs.microsoft.com/en-us/azure/devops/pipelines/migrate/from-travis?view=azure-devops
https://medium.com/@anthonypjshaw/azure-pipelines-with-python-by-example-aa65f4070634
https://github.com/asottile/azure-pipeline-templates

Packaging
https://hynek.me/articles/sharing-your-labor-of-love-pypi-quick-and-dirty/
https://docs.microsoft.com/en-us/azure/devops/pipelines/artifacts/pypi?view=azure-devops&tabs=yaml&viewFallbackFrom=vsts
https://www.youtube.com/watch?v=btqFjNDdTlE
https://docs.microsoft.com/en-us/azure/devops/pipelines/artifacts/pypi?view=azure-devops&tabs=yaml

https://github.com/joerick/cibuildwheel
https://github.com/explosion/wheelwright

https://github.com/python-attrs/attrs/blob/master/setup.py
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/src/attr/__init__.py#L21-L33
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/setup.py#L67-L79
https://github.com/sdispater/poetry/issues/1036
https://github.com/hynek/structlog/blob/master/CHANGELOG.rst
https://raw.githubusercontent.com/python-attrs/attrs/master/CHANGELOG.rst
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/setup.py#L84-L97
https://pypi.org/project/attrs/
https://github.com/hynek/structlog/commit/92f46e5ff2d014c8e7e6a11166165a3e6dc1288b
https://www.sphinx-doc.org/en/master/usage/builders/index.html#sphinx.builders.linkcheck.CheckExternalLinksBuilder
https://github.com/hynek/structlog/commit/1468a34661d2035198ff3eb925883a8b8d959919

http://calver.org/
SemVer Criticism
https://twitter.com/hynek/status/1235848177640542214
-->

## High Performance Python and Django and Trends

<!--
https://us.pycon.org/2020/schedule/talks/

List of Engineering Blogs
* [Awesome List of Engineering Blogs 1](https://github.com/kilimchoi/engineering-blogs)
* [Awesome List of Engineering Blogs 2](https://github.com/sumodirjo/engineering-blogs)

https://techyaks.com/python-year-tytop.html
-->

Python Success Stories
* [Python Success Stories](https://www.python.org/success-stories)

<!--
Carl Meyer talk
https://www.youtube.com/watch?v=lx5WQjXLlq8 | Carl Meyer about Django @ Instagram at Django: Under The Hood 2016 - YouTube
Talks

https://www.youtube.com/watch?v=ZYD9yyMh9Hk | Stephen Simmons, Neil Slinger python at massive scale - Google Search
https://www.youtube.com/watch?v=H4SS9yVWJYA | Jason Fried - Fighting the Good Fight: Python 3 in your organization - PyCon 2018 - YouTube

Python 3 at Facebook 
https://lwn.net/Articles/758159/
https://www.youtube.com/watch?v=H4SS9yVWJYA

https://engineering.linkedin.com/blog/2020/how-we-retired-python-2-and-improved-developer-happiness
https://blogs.dropbox.com/tech/2018/09/how-we-rolled-out-one-of-the-largest-python-3-migrations-ever/ | How we rolled out one of the largest Python 3 migrations ever | Dropbox Tech Blog
-->

## Python Syntax and Python Versus JavaScript

Programming Language Leveling Up and Comparisons- Python
* [Learn X in Y Minutes Python 3](https://learnxinyminutes.com/docs/python3)
* [Learn X in Y Minutes Python](https://learnxinyminutes.com/docs/python)
* [PLEAC - Programming Language Examples Alike Cookbook- Python](http://pleac.sourceforge.net/pleac_python.data)

Python and Python Syntax and Semantics
* [Python Wikipedia](https://en.wikipedia.org/wiki/Python_(programming_language))
* [Python Syntax and Semantics Wikipedia](http://en.wikipedia.org/wiki/Python_syntax_and_semantics) 
* [Python Programming Wikibook](http://en.wikibooks.org/wiki/Python_Programming) 
* [Python Programming Wikiversity](https://en.wikiversity.org/wiki/Python_Programming) 
* [Non-Programmers Tutorial for Python 3 Wikibook](https://en.wikibooks.org/wiki/Non-Programmer%27s_Tutorial_for_Python_3) 

## Python and JavaScript

One Pic
* [Python 3 in One Pic](http://coodict.github.io/python3-in-one-pic) and [Python 3 in One Pic GitHub](https://github.com/coodict/python3-in-one-pic)
* [JavaScript in One Pic GitHub](https://github.com/coodict/javascript-in-one-pic)

Python vs. JavaScript
* [Saya: Python 3 vs. JavaScript (ES2015)](https://sayazamurai.github.io/python-vs-javascript) and [Python 3 vs. JavaScript (ES2015) GitHub](https://github.com/sayazamurai/python-vs-javascript)
* [Ilya Shchurov: Python vs. JavaScript GitHub](https://ischurov.github.io/pythonvjs/show/lists-arrays/en)

## Programming Language Comparisons

Programming Language Comparisons
* [Comparison of Programming Languages Wikipedia](http://en.wikipedia.org/wiki/Comparison_of_programming_languages)
* [Programming Language Comparisons Wikipedia](https://en.wikipedia.org/wiki/Category:Programming_language_comparisons)
* [Comparison of Programming Languages (Syntax) Wikipedia](http://en.wikipedia.org/wiki/Comparison_of_programming_languages_(syntax))  
* [Comparison of Basic Instructions of Programming Languages Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_programming_languages_(basic_instructions)) 
* [Computer Programming/Hello world Wikibook](https://en.wikibooks.org/wiki/Computer_Programming/Hello_world)

Programming Language Leveling Up and Comparison Sites
* [Programming Levels](http://science.raphael.poss.name/programming-levels.html)    
* [Learn X in Y Minutes](https://learnxinyminutes.com)
* [Guess the Programming Language](http://tutorialzine.com/2014/06/guess-the-programming-language) 
* [PLEAC - Programming Language Examples Alike Cookbook](http://pleac.sourceforge.net)
* [Rosetta Code](http://rosettacode.org/wiki/Rosetta_Code)

<!--
https://en.wikipedia.org/wiki/Timeline_of_programming_languages

https://twitter.com/TimSweeneyEpic/status/1066533192998559744 | Tim Sweeney on Twitter: "Programming language families. Still contemplating how the whole space could be covered nicely by a single, reasonably-straightforward language.… https://t.co/OksZudfMJF"
-->

## Great Release Managers

<!--
People and Projects

Includes issues links
* [Python Packaging Key Projects](https://packaging.python.org/key_projects)
https://www.encode.io/projects/

https://twitter.com/PalletsTeam

https://github.com/orgs/pytest-dev/people
https://github.com/orgs/pypa/people
https://github.com/orgs/python/people
https://github.com/orgs/tox-dev/people
https://github.com/orgs/pre-commit/people
https://github.com/python/cpython/graphs/contributors
-->

### General Talks

<!--
Important talk
https://www.youtube.com/watch?v=iKAaNaVpJFM | Automating Code Quality: Next Level - YouTube
https://2018.pygotham.org/talks/automating-code-quality-next-level/

https://pyvideo.org/speaker/kyle-knapp.html
https://www.youtube.com/watch?v=G1lDk_WKXvY | Kyle Knapp - Automating Code Quality - PyCon 2018 - YouTube
https://speakerdeck.com/pycon2018/kyle-knapp-automating-code-quality
https://pyvideo.org/pycon-us-2018/automating-code-quality.html
PyGotham

Thea's talk
https://www.youtube.com/watch?v=-BHverY7IwU

Carl Meyer: Set your code free
https://www.youtube.com/watch?v=nHWRN5gCPSI&feature=player_embedded
https://github.com/oddbird/set-your-code-free-preso/blob/master/slides.rst
https://www.oddbird.net/talks/set-your-code-free/

https://speakerdeck.com/carljm
https://github.com/carljm/dotfiles
-->

### Projects

### Ned Batchelder

* [coverage.py GitHub](https://github.com/nedbat/coveragepy/)

### Hynek Schlawack

* [Hynek GitHub](https://github.com/hynek)
* [Hynek Talks](https://hynek.me/talks/)

<!--
https://hynek.me/talks/python-foss/
https://pyvideo.org/pygotham-2019/maintaining-a-python-project-when-its-not-your-job.html
https://speakerdeck.com/hynek/maintaining-a-python-project-when-its-not-your-job
https://www.google.com/search?q=hynek+schlawack+not+your+job&oq=hynek+schlawack+not+your+job&aqs=chrome.0.69i59j33.6804j0j7&sourceid=chrome&ie=UTF-8 | hynek schlawack not your job - Google Search

https://pyvideo.org/pycon-us-2018/how-to-write-deployment-friendly-applications.html
https://www.youtube.com/watch?v=wuCpCkrfeMs | Hynek Schlawack - How to Write Deployment-friendly Applications - PyCon 2018 - YouTube
-->

### Paul Ganssle

<!--
https://twitter.com/pganssle/status/1230848453321904130 | Paul Ganssle on Twitter: "Oh boy. Standard library time zone implementation is now passing a lot of tests. Still a bunch of TODO comments and tests to write but I think the API might be close to final. Looks like it's time to start in on the documentation.😬 #python #timezones #documentation" / Twitter
https://twitter.com/pganssle/status/1213826961182744576 | Paul Ganssle on Twitter: "I soft-launched this a few weeks back, but here is my most polished (i.e. not very) @rustlang project to date: metadata-backup, a tool for backing up your file system metadata. Contributions welcome! https://t.co/dg43qKxjFR" / Twitter
-->

### Anthony Sottile

Builds lots of productivity tools, linters, and code formatters

Sponsor Bio
* [Anthony Sponsor Bio](https://github.com/sponsors/asottile)

Regular Accounts
* [Anthony Sottile GitHub](https://github.com/asottile/)
* [Anthony Sottile Archive GitHub](https://github.com/asottile-archive)

Twitch-Related
* [Twitch](https://www.twitch.tv/anthonywritescode)
* [Twitch GitHub](https://github.com/anthonywritescode)
* [Twitch YouTube](https://www.youtube.com/channel/UC46xhU1EH7aywEgvA9syS3w/videos)
* [Anthony Sottile Twitter](https://twitter.com/codewithanthony)

Advent of Code
* [Advent of Code GitHub](https://github.com/anthonywritescode/aoc2019/)

Creator
* [pre-commit](https://pre-commit.com)
* [seed-isort-config GitHub](https://github.com/asottile/seed-isort-config)

Core Developer
* [pytest](http://pytest.org) and [pytest Docs](https://docs.pytest.org/)
* [Tox Read the Docs](https://tox.readthedocs.org)

Maintainer (maintain pyflakes as a member of the @PyCQA)
* [Flake8 GitHub](https://gitlab.com/pycqa/flake8) and [Flake8 Docs](http://flake8.pycqa.org)
* [Pyflakes GitHub](https://gitlab.com/pycqa/flake8)

pycodestyle
* [pycodestyle GitHub](https://github.com/PyCQA/pycodestyle)

<!--
https://github.com/PyCQA/pycodestyle/issues/466
-->

Special Projects
* [babi](https://github.com/asottile/babi)
* [babi-editor](https://github.com/babi-editor)

<!--
Tools

https://github.com/nedbat/coveragepy/issues/

virtualenv 20.0.0 is now released, a first major release of a new better implementation for the future
https://twitter.com/gjbernat/status/1226803593535279104
https://virtualenv.pypa.io/en/latest/changelog.html#v20-0-0-2020-02-10
https://github.com/pyenv/pyenv-update

PyTest
https://twitter.com/codewithanthony/status/1195477147537657856
https://twitter.com/nicoddemus/status/1195088740118618112
https://twitter.com/blueyed/status/1222578734676484096

PyTest
https://twitter.com/codewithanthony/status/1213573183879692289 | Anthony Sottile on Twitter: "#pytest 4.6.9 has been released! this marks the beginning of community supported 4.6 maintenance of python 2 / python 3.4 (core will still accept patches to 4.6 but will no longer be actively backporting to 4.6) -- long live python 2! more details here: https://t.co/6b7Ilkr8ko" / Twitter
-->

<!--
https://testandcode.com/104

Builds backported/forwardported pythons for ubuntu with @deadsnakes
https://twitter.com/codewithanthony/status/1242245981590007808
https://github.com/deadsnakes
https://launchpad.net/~deadsnakes/+archive/ubuntu/ppa

https://github.com/pre-commit/mirrors-autopep8/commit/5985fb24f71421cd14f9cda5d6c7a06fc30b321c
https://github.com/anthonywritescode/cfp/blob/master/lyftvenv.md

https://github.com/asottile/add-trailing-comma
https://github.com/asottile/all-repos
https://github.com/asottile/t
https://github.com/asottile/git-code-debt

Drop python 2 / python3.5 support in pre-commit
https://github.com/pre-commit/pre-commit/releases/tag/v2.0.0
https://github.com/pre-commit/pre-commit/issues/1260
https://github.com/pre-commit/pre-commit/pull/1277

https://pre-commit.com/#python
https://pre-commit.com/hooks.html

http://linter-runner.com
https://twitter.com/codewithanthony/status/1208048314987548673 | Anthony Sottile on Twitter: "@KatiMichel https://t.co/S6NBCRYnJj coming soon ;)" / Twitter
https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks | Git - Git Hooks

https://www.youtube.com/watch?v=XLRdSxlIIfc | Keep Your Code Clean Using pre-commit with Anthony Sottile - YouTube

https://www.reddit.com/r/Python/comments/8p578l/pyupgrade_automatically_rewrite_format_calls_to/
https://pypi.org/project/pyupgrade-docs/

https://github.com/asottile/pyupgrade/blob/997f4452c82848afdeda08ec3d2bef8b08d5ebe1/.travis.yml | pyupgrade/.travis.yml at 997f4452c82848afdeda08ec3d2bef8b08d5ebe1 · asottile/pyupgrade
https://github.com/asottile/pyupgrade/blob/34a269fd7650d264e4de7603157c10d0a9bb8211/azure-pipelines.yml#L23 | pyupgrade/azure-pipelines.yml at 34a269fd7650d264e4de7603157c10d0a9bb8211 · asottile/pyupgrade
https://github.com/search?l=YAML&o=desc&q=-+++env%3A+TOXENV%3Dpy36&s=indexed&type=Code | Search · - env: TOXENV=py36
https://tox.readthedocs.io/en/latest/config.html | tox configuration specification — tox 3.14.2.dev12 documentation

https://github.com/asottile/pyupgrade
https://twitter.com/nedbat/status/1212802879083315200 | Ned Batchelder on Twitter: "If you are looking to get rid of python-2/3 compatibility code, try https://t.co/yIDeMQxl0n (pro-tip: if you can’t remember where you saw some amazing code-munging thing, @codewithanthony’s GitHub is a good guess!)" / Twitter
-->

## Python 2 or 3, Python 2 EoL

Python 2 or 3
* [Python 2 or 3](https://wiki.python.org/moin/Python2orPython3)

Python 2 EOL Websites
* [Python 3 Readiness](https://tiran.github.io/py3readiness)
* [Python Readiness](https://pyreadiness.org)
* [Python 3 Wall of Superpowers](https://python3wos.appspot.com)
* [Python 3 Porting](http://python3porting.com)
* [Can I Use Python 3?](https://caniusepython3.com) and [Can I Use Python 3? GitHub](https://github.com/caniusepython3/caniusepython3.com)

<!--
https://github.com/encode/django-rest-framework/pull/6615 | Dropped Python 2 compatibility. by carltongibson · Pull Request #6615 · encode/django-rest-framework

https://github.blog/changelog/2020-02-27-github-actions-breaking-change-python-2-being-removed-from-all-virtual-environments/ | GitHub Actions Breaking Change: Python 2 being removed from all virtual environments - The GitHub Blog

https://github.com/marketplace/actions/upgrade-to-python-3 | Upgrade to Python 3 · Actions · GitHub Marketplace

https://python-modernize.readthedocs.io/en/latest/ | Python-Modernize — modernize 0.6.1 documentation
https://pypi.org/project/modernize/ | modernize · PyPI

Python 2 to 3
https://docs.python.org/3/howto/pyporting.html

Cheat Sheets
http://python-future.org/ | Easy, clean, reliable Python 2/3 compatibility — Python-Future documentation
http://python-future.org/automatic_conversion.html | Automatic conversion to Py2/3 — Python-Future documentation
http://python-future.org/compatible_idioms.html
https://python-future.org/quickstart.html
http://python-future.org/futurize.html#forwards-conversion-stage2
https://python-future.org/quickstart.html#installation
Python 3.1
http://ptgmedia.pearsoncmg.com/imprint_downloads/informit/promotions/python/python2python3.pdf
https://pybit.es/python-porting.html
http://sebastianraschka.com/Articles/2014_python_2_3_key_diff.html

https://python-future.org/futurize.html | futurize: Py2 to Py2/3 — Python-Future documentation
http://python-future.org/futurize_cheatsheet.html | futurize quick-start guide — Python-Future documentation
https://python-future.org/quickstart.html#to-convert-existing-python-2-code | Quick-start guide — Python-Future documentation
http://python-future.org/changelog.html#newobject-base-object-defines-fallback-py2-compatible-special-methods | Changes in previous versions — Python-Future documentation

six
https://pypi.org/project/six/ | six · PyPI
https://six.readthedocs.io/
https://github.com/benjaminp/six

django.utils.six
https://docs.djangoproject.com/en/2.2/_modules/django/utils/six/ | django.utils.six | Django documentation | Django
https://stackoverflow.com/questions/59193514/importerror-cannot-import-name-six-from-django-utils

Django
https://docs.djangoproject.com/en/3.0/releases/3.0/#removed-private-python-2-compatibility-apis | Django 3.0 release notes | Django documentation | Django
https://docs.djangoproject.com/en/3.0/releases/2.0/ | Django 2.0 release notes | Django documentation | Django

`from __future__ import`

New features
f-strings
type checking

Packages for upgrading
https://github.com/asottile/pyupgrade
https://twitter.com/codewithanthony/status/1211814531753795596 | Anthony Sottile on Twitter: "periodic reminder for those of you dropping #python 2 -- here's a utility which will help you automatically burn the bridges and _upgrade_ your syntax! https://t.co/JTmfuCvzAD" / Twitter
-->

## Package Tools and Testing

<!--
Pinax release docs
`python setup.py test`
https://github.com/pypa/setuptools/issues/931
https://github.com/pytest-dev/pytest/issues/5534
https://github.com/pypa/setuptools/issues/1684#issuecomment-508156856
https://github.com/pypa/setuptools/issues/1684

https://setuptools.readthedocs.io/en/latest/setuptools.html#configuring-setup-using-setup-cfg-files
https://github.com/pypa/sampleproject/blob/master/setup.cfg
-->

## Eldarion

Package Tools
* [django-appconf Read the Docs](https://django-appconf.readthedocs.io) and [django-appconf PyPI](https://pypi.org/project/django-appconf)

<!--
https://github.com/django-compressor/django-appconf | django-compressor/django-appconf: An app to handle configuration defaults of packaged Django apps gracefully
-->

Continuous Integration and Delivery
* [CircleCI](https://circleci.com)

Coverage
* [Codecov](https://codecov.io)
* [Coverage Read the Docs](http://coverage.readthedocs.org) and [Coverage Bitbucket](https://bitbucket.org/ned/coveragepy)

Testing Tools
* [Tox Read the Docs](https://tox.readthedocs.org)
* [Tox Parallel Mode](https://tox.readthedocs.io/en/latest/example/basic.html#parallel-mode)
* [Detox GitHub (Archived)](https://github.com/tox-dev/detox) and [Detox PyPi](https://pypi.python.org/pypi/detox)

<!--
https://docs.codecov.io/docs/python
https://codecov.io/#features | Codecov

"[Integration with coverage.py](https://docs.djangoproject.com/en/dev/topics/testing/advanced/#topics-testing-code-coverage)."
"[Running tests using tox](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/#running-tests-using-tox)"

https://github.com/codecov/example-python#testing-with-tox | codecov/example-python: Python coverage example
https://github.com/pallets/flask/blob/master/tox.ini
https://github.com/pganssle/tox-examples | pganssle/tox-examples

https://stackoverflow.com/questions/21991765/how-to-generate-coverage-from-setup-py | python - How to generate coverage from setup.py - Stack Overflow
https://github.com/codecov/example-python#how-to-generate-coverage-reports
"coverage.py is required to collect coverage metrics."
-->

tox Alternative (not used)
* [Nox](http://nox.thea.codes) and [Nox GitHub](https://github.com/theacodes/nox)

Import Sorting
* [isort](http://isort.readthedocs.io) and [isort GitHub](https://github.com/timothycrosley/isort)

Formatting
* [Flake8 GitHub](https://gitlab.com/pycqa/flake8) and [Flake8 Docs](http://flake8.pycqa.org)
* [doc8 GitHub](https://github.com/openstack/doc8)
* [pydocstyle GitHub](https://github.com/PyCQA/pydocstyle)
* [mccabe GitHub](https://github.com/PyCQA/mccabe)
* [Flake8 Quotes GitHub](https://github.com/zheller/flake8-quotes)

<!--
https://github.com/timothycrosley/isort/issues/694

?
https://pypi.org/project/pyflakes/
https://github.com/PyCQA/pyflakes
-->

Not used?
* [Factory Boy GitHub](https://github.com/FactoryBoy/factory_boy) and [Factory Boy PyPI](https://pypi.python.org/pypi/factory_boy)

Kubernetes
* [Kubernetes](https://kubernetes.io)

Webpack Versus Browserify
* [Vue](https://vuejs.org/)
* [Webpack](https://webpack.js.org)
* [Copy Webpack Plugin GitHub](https://github.com/webpack-contrib/copy-webpack-plugin)
* [Browserify](http://browserify.org)
* [Browsersync](https://www.browsersync.io/)


<!--
attrs, pre-commit, tox, nox, flake8, check-manifest, twine, isort, seed-isort-config, black, pytest-cov, codecov action, flake8-black

Not used- but could be?
* [attrs GitHub](https://github.com/python-attrs/attrs)
* [pytest-cov Read the Docs](https://pytest-cov.readthedocs.io)

https://github.com/pytest-dev/pytest-cov | pytest-dev/pytest-cov: Coverage plugin for pytest.
https://github.com/pytest-dev/pytest-flask | pytest-dev/pytest-flask: A set of pytest fixtures to test Flask applications
https://github.com/codecov/codecov-action | codecov/codecov-action: GitHub Action that uploads coverage to Codecov
https://pypi.org/project/flake8-black/ | flake8-black · PyPI
-->

<!--
http://fontawesome.io/ | Font Awesome, the iconic font and CSS toolkit
https://fontawesome.com | Font Awesome 5 | Font Awesome

Black and single quotes
https://github.com/peterjc/flake8-black | peterjc/flake8-black: flake8 plugin to run black for checking Python coding style
https://github.com/python/black/issues/118 | Single quotes option · Issue #118 · python/black

CI
https://circleci.com/blog/setting-up-continuous-integration-with-github/ | GitHub Continuous Integration - GitHub CI | CircleCI

https://circleci.com/docs/2.0/ | Welcome to CircleCI Documentation - CircleCI
https://circleci.com/docs/2.0/example-configs/ | Example Public Repos - CircleCI
https://circleci.com/docs/2.0/caching/ | Caching Dependencies - CircleCI
https://circleci.com/docs/2.0/env-vars/ | Using Environment Variables - CircleCI
https://circleci.com/docs/2.0/language-python/ | Configuring a Python Application on CircleCI - CircleCI
https://github.com/CircleCI-Public/circleci-demo-python-django | CircleCI-Public/circleci-demo-python-django: Example Django application running on CircleCI

https://coverage.readthedocs.io/en/coverage-5.0/config.html | Configuration files — Coverage.py 4.4.2 documentation

http://flake8.pycqa.org/en/3.1.1/user/ignoring-errors.html | Ignoring Errors with Flake8 — flake8 3.1.1 documentation

flake8 
noqa: E501
https://pypi.org/project/flake8-confusables/ | flake8-confusables · Warehouse (PyPI)
-->

## Code Formatting Tools

Code Formatting
* [Black GitHub](https://github.com/psf/black)
* [Black Online (Playground) GitHub](https://github.com/jpadilla/black-online)
* [Black Out GitHub](https://github.com/mariatta/black_out)
* [White GitHub](https://github.com/kennethreitz/white)
* [Google YAPF](https://github.com/google/yapf)

<!--
https://github.com/bots-for-humanity/black-out

https://black.now.sh/ | Black Playground

https://github.com/eventbrite/invoke-release | eventbrite/invoke-release: A set of command line tools that help software engineers release Python projects quickly, easily, and in a consistent manner.
https://github.com/twisted/incremental#updating | twisted/incremental: A library for versioning your Python projects.

https://www.youtube.com/watch?v=-BHverY7IwU
http://www.pyinvoke.org/
https://github.com/pypa/pip/blob/master/tasks/generate.py
-->

## Software Engineering

Software Project Management
* [Software Project Management Wikipedia](http://en.wikipedia.org/wiki/Software_project_management)

Software Engineering/Development 
* [Software Engineering Wikipedia](https://en.wikipedia.org/wiki/Software_engineering) 
* [History of Software Engineering Wikipedia](https://en.wikipedia.org/wiki/History_of_software_engineering) 
* [Outline of Software Engineering Wikipedia](https://en.wikipedia.org/wiki/Outline_of_software_engineering)
* [Guide to the Software Engineering Body of Knowledge](http://www.computer.org/web/swebok/v3) and [Guide to the Software Engineering Body of Knowledge Wikipedia](https://en.wikipedia.org/wiki/Software_Engineering_Body_of_Knowledge)
* [Software Development Wikipedia](http://en.wikipedia.org/wiki/Software_development) 

## Requirements and Planning

Requirements
* [Product Requirements Document Wikipedia](http://en.wikipedia.org/wiki/Product_requirements_document)
* [Requirement Wikipedia](https://en.wikipedia.org/wiki/Requirement)
* [Business Requirements Wikipedia](https://en.wikipedia.org/wiki/Business_requirements)
* [Functional Requirement Wikipedia](https://en.wikipedia.org/wiki/Functional_requirement)
* [Non-Functional Requirement Wikipedia](https://en.wikipedia.org/wiki/Non-functional_requirement)
* [Specification Wikipedia](https://en.wikipedia.org/wiki/Specification_(technical_standard))
* [Functional Specification Wikipedia](https://en.wikipedia.org/wiki/Functional_specification)
* [Requirement Analysis Wikipedia](https://en.wikipedia.org/wiki/Requirements_analysis)
* [Requirement Prioritization Wikipedia](https://en.wikipedia.org/wiki/Requirement_prioritization)
* [Requirement Management Wikipedia](http://en.wikipedia.org/wiki/Requirements_management)

<!--
Requirements baseline
https://en.wikipedia.org/wiki/Baseline_(configuration_management)
-->

Technical
* [Software Prototyping Wikipedia](http://en.wikipedia.org/wiki/Software_prototyping) 
* [Proof of Concept Wikipedia](https://en.wikipedia.org/wiki/Proof_of_concept)
* [Technology Roadmap Wikipedia](http://en.wikipedia.org/wiki/Technology_roadmap)
* [Solution Architecture Wikipedia](https://en.wikipedia.org/wiki/Solution_architecture)
* Objective, Assumption, Constraint

## Software Life Cycle and Release Management

Software Development Philosophies and Process
* [List of Software Development Philosophies Wikipedia](https://en.wikipedia.org/wiki/List_of_software_development_philosophies) 
* [Software Development Process (Series) Wikipedia](https://en.wikipedia.org/wiki/Software_development_process) 

Life Cycles
* [Product Life Cycle Management Wikipedia](https://en.wikipedia.org/wiki/Product_life-cycle_management_(marketing))
* [Systems Development Life Cycle Wikipedia](https://en.wikipedia.org/wiki/Systems_development_life_cycle)
* [Technology Adoption Life Cycle Wikipedia](https://en.wikipedia.org/wiki/Technology_adoption_life_cycle)

## Continuous Integration, Continuous Deployment, and Test Matrix

Continuousness
* [Continuous Integration Wikipedia](https://en.wikipedia.org/wiki/Continuous_integration)
* [Continuous Delivery Wikipedia](https://en.wikipedia.org/wiki/Continuous_delivery)

Continuous Integration Software
* [Continuous Integration Software Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_continuous_integration_software)

Automation
* [Build Automation Wikipedia](https://en.wikipedia.org/wiki/Build_automation)

Other Stuff
* [Code Coverage Wikipedia](https://en.wikipedia.org/wiki/Code_coverage)
* [Traceability Matrix Wikipedia](https://en.wikipedia.org/wiki/Traceability_matrix)

## GitHub- Release Tools

Tags and Releases
* [GitHub About Milestones](https://help.github.com/en/articles/about-milestones)
* [GitHub About Releases](https://help.github.com/articles/about-releases) and [GitHub Creating Releases](https://help.github.com/articles/creating-releases)
* [GitHub Working with Tags](https://help.github.com/articles/working-with-tags)

<!--
https://developer.github.com/v3/repos/releases/#create-a-release | Releases | GitHub Developer Guide
-->

## Release Management

Software Release Life Cycle
* [Software Release Life Cycle Wikipedia](https://en.wikipedia.org/wiki/Software_release_life_cycle)

Release Management
* [Release Management Wikipedia](https://en.wikipedia.org/wiki/Release_management)
* [Release Engineering Wikipedia](https://en.wikipedia.org/wiki/Release_engineering)
* [Release Versioning Wikipedia](https://en.wikipedia.org/wiki/Software_versioning)
* [Release Deployment Wikipedia](https://en.wikipedia.org/wiki/Software_deployment)
* [Rolling Release Wikipedia](https://en.wikipedia.org/wiki/Rolling_release)
* [Application Release Automation Wikipedia](https://en.wikipedia.org/wiki/Application_release_automation)

Software Versioning and Semver (See also: npm packages)
* [Software Versioning Wikipedia](https://en.wikipedia.org/wiki/Software_versioning)
* [Semver](http://semver.org) and [Semver GitHub](https://github.com/mojombo/semver) 
* [CalVer](https://calver.org)
* [ZeroVer](https://0ver.org)

<!--
SemVer
https://words.steveklabnik.com/what-s-next-for-semver | What’s next for SemVer

https://twitter.com/_ericelliott/status/1201639694800433152 | Eric Elliott on Twitter: "): Major.Minor.Patch :) Breaking.Feature.Fix https://t.co/jDFNzOZZDu #JavaScript" / Twitter
https://medium.com/javascript-scene/software-versions-are-broken-3d2dc0da0783 | Software Versions are Broken - JavaScript Scene - Medium
-->

## Useful Files

Shells
* [Comparison of Command Shells Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_command_shells)
* [Unix Shell Wikipedia](http://en.wikipedia.org/wiki/Unix_shell)  
* [Bash (Unix Shell) Wikipedia](http://en.wikipedia.org/wiki/Bash_(Unix_shell))  

Permissions
* [File System Permissions](https://en.wikipedia.org/wiki/File_system_permissions)

Rake and Make
* [Ruby Rake File GitHub](https://github.com/ruby/rake)
* [Make Wikipedia](https://en.wikipedia.org/wiki/Make_(software))
* [GNU Makefile](https://www.gnu.org/software/make) and [Makefile Wikipedia](https://en.wikipedia.org/wiki/Makefile)

Files
* [Manifest File Wikipedia](https://en.wikipedia.org/wiki/Manifest_file)

EditorConfig (tabs versus spaces, ect) .editorconfig
* [EditorConfig](http://editorconfig.org)
* [EditorConfig Plugins](http://editorconfig.org/#download)

Maintenance
* [Cron Wikipedia](https://en.wikipedia.org/wiki/Cron)
* [Lint](https://en.wikipedia.org/wiki/Lint_(software))

Markdown
* [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown) 

YAML
* [YAML](http://yaml.org) and [YAML Wikipedia](https://en.wikipedia.org/wiki/YAML)

Shebang File
* [Shebang File Wikipedia](https://en.wikipedia.org/wiki/Shebang_(Unix))

<!--
https://en.wikipedia.org/wiki/Shell_script

https://www.gnu.org/software/make/manual/make.pdf | make.pdf

Bash
https://www.gnu.org/software/bash/manual/bashref.html#What-is-Bash_003f | Bash Reference Manual
https://www.tldp.org/LDP/abs/html/ | Advanced Bash-Scripting Guide
https://www.tldp.org/LDP/Bash-Beginners-Guide/html/ | Bash Guide for Beginners
https://opensource.com/article/20/1/bash-scripts-aliases | My favorite Bash hacks | Opensource.com

Command line
https://hellowebbooks.com/news/command-line-zine-launch/ | First free zine on command line basics has launched today! - Hello Web Books

Bash versus Python
https://opensource.com/article/19/4/bash-vs-python
https://stackoverflow.com/questions/6908143/should-i-put-shebang-in-python-scripts-and-what-form-should-it-take

https://www.linuxjournal.com/content/understanding-bash-elements-programming

Dotfiles
https://github.com/paulirish/dotfiles | paulirish/dotfiles: paul's shell, git, etc config files. also homebrew, migration setup. good stuff.
https://github.com/Miserlou/dotfiles-osx | Miserlou/dotfiles-osx: Updated dotfiles. For me not you.
https://github.com/kennethreitz/dotfiles | kennethreitz/dotfiles: My personal dotfiles.
https://github.com/nnja/new-computer/blob/master/setup.sh#L253 | new-computer/setup.sh at master · nnja/new-computer
https://twitter.com/andrewgodwin/status/1180286950344818689 | Andrew Godwin on Twitter: "@simonw This is exactly what I do for my dotfiles. Recommend also having a script in the repo that makes the links for you." / Twitter
-->

## Automation

Python- Fabric
* [Fabric](http://www.fabfile.org), [Fabric PyPi](https://pypi.python.org/pypi/Fabric), and [Fabric GitHub](https://github.com/fabric/fabric) 

<!--
salt, ansible

http://docs.fabfile.org/en/1.13/api/contrib/django.html

https://www.digitalocean.com/community/tutorials/how-to-use-fabric-to-automate-administration-tasks-and-deployments
-->

## Python Profiling

<!--
https://knasmueller.net/measure-code-execution-time-accurately-in-python

Python Profiling 

Third Party Testing and Profiling

https://pypi.org/project/memory-profiler/ | memory-profiler · PyPI

https://engineering.instagram.com/profiling-cpython-at-instagram-89d4cbeeb898 | Profiling CPython at Instagram – Instagram Engineering

https://github.com/uber/pyflame | uber/pyflame: 🔥 Pyflame: A Ptracing Profiler For Python
https://zapier.com/engineering/profiling-python-boss/ | Profiling Python Like a Boss - The Zapier Engineering Blog | Zapier
https://www.pluralsight.com/guides/python/quick-profiling-in-python | Quick profiling in Python (Example) | hack.guides()
https://jvns.ca/blog/2017/12/17/how-do-ruby---python-profilers-work-/ | How do Ruby & Python profilers work? - Julia Evans
http://www.integralist.co.uk/posts/profiling-python/ | Profiling Python ⋆ Mark McDonnell
-->

<!--
https://medium.freecodecamp.org/django-performance-optimization-looking-for-the-bottlenecks-8583789e341b | Django Performance Optimization: The Search for Bottlenecks
-->

## General Python and Django Links

Python Official Tutorial
* [Python Official Tutorial](https://docs.python.org/3/tutorial/) 

Django Tutorials (Official, Mozilla Developer Network and SIBTC) 
* [Django Official Tutorial](https://docs.djangoproject.com/en/2.0/intro/tutorial01)

Django Install
* [Django Install](https://docs.djangoproject.com/en/dev/topics/install)

Python Style
* [PEP 0008 Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008) and [PEP 0008 Style Guide for Python Code .txt](https://hg.python.org/peps/file/tip/pep-0008.txt)
* [PEP 0257 Doc String Conventions](https://www.python.org/dev/peps/pep-0257)

Django Coding Style Guide
* [Django Coding Style Guide](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style)

Django JavaScript Style Guide
* [Django JavaScript Style Guide](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript)

Django Views
* [Class-Based Views](https://docs.djangoproject.com/en/dev/topics/class-based-views/)

Django ORM
* [Queries](https://docs.djangoproject.com/en/dev/topics/db/queries)

<!--
https://docs.djangoproject.com/en/2.2/ref/request-response/ | Request and response objects | Django documentation | Django
https://docs.djangoproject.com/en/2.2/_modules/django/http/request/ | django.http.request | Django documentation | Django

https://docs.djangoproject.com/en/dev/_modules/django/http/request/#HttpRequest
https://docs.djangoproject.com/en/dev/ref/request-response/#jsonresponse-objects

https://docs.djangoproject.com/en/2.1/ref/request-response/#django.http.HttpRequest.GET
https://docs.djangoproject.com/en/1.11/ref/request-response/#django.http.HttpRequest.POST
https://docs.djangoproject.com/en/1.11/ref/request-response/#django.http.QueryDict
-->

Python- Django- Rest Framework (Including Authentication and Generic Views)
* [Django Rest Framework](http://www.django-rest-framework.org) and [Django Rest Framework GitHub](https://github.com/encode/django-rest-framework) 
* [Django Rest Framework Authentication](http://www.django-rest-framework.org/api-guide/authentication)  
* [Django Rest Framework Generic Views](http://www.django-rest-framework.org/api-guide/generic-views)  

Django Architecture and Scaling
* [Shared-Nothing Architecture Wikipedia](https://en.wikipedia.org/wiki/Shared-nothing_architecture)
* [Does Django Scale?](https://docs.djangoproject.com/en/dev/faq/general/#does-django-scale)
* [Django Design Philosophies](https://docs.djangoproject.com/en/dev/misc/design-philosophies)

## Django Core Dev Security

<!--
https://docs.djangoproject.com/en/dev/releases/security/
https://docs.djangoproject.com/en/dev/internals/security/#how-django-discloses-security-issues

High
https://en.wikipedia.org/wiki/Arbitrary_code_execution
https://en.wikipedia.org/wiki/SQL_injection

Medium
* [Cross-Site Scripting Wikipedia](https://en.wikipedia.org/wiki/Cross-site_scripting)
https://en.wikipedia.org/wiki/Cross-site_request_forgery
https://en.wikipedia.org/wiki/Denial-of-service_attack
Broken authentication

Low
Sensitive data exposure
Broken session management
Unvalidated redirects/forwards
Issues requiring an uncommon configuration option

https://www.owasp.org/index.php/SQL_Injection
https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)
https://www.owasp.org/index.php/Denial_of_Service
-->

## Django Security

<!--
https://docs.djangoproject.com/en/2.1/ref/middleware/#django.middleware.security.SecurityMiddleware | Middleware | Django documentation | Django
https://docs.djangoproject.com/en/2.1/ref/middleware/#http-strict-transport-security | Middleware | Django documentation | Django
https://docs.djangoproject.com/en/2.1/ref/clickjacking/ | Clickjacking Protection | Django documentation | Django


https://en.wikipedia.org/wiki/Information_security

https://www.owasp.org/index.php/Category:Attack
-->

## Security

Security- General
* [Security- Computer Security Wikipedia](https://en.wikipedia.org/wiki/Security#Computer_security)
* [Computer Security Wikipedia](https://en.wikipedia.org/wiki/Computer_security)
* [Threat Model Wikipedia](https://en.wikipedia.org/wiki/Threat_model)
* [Penetration Test Wikipedia](https://en.wikipedia.org/wiki/Penetration_test)

OWASP
* [OWASP](https://www.owasp.org/index.php/Main_Page) and [OWASP GitHub](https://github.com/OWASP)
* [OWASP Cheat Sheet Series](https://www.owasp.org/index.php/OWASP_Cheat_Sheet_Series) and [OWASP Cheat Sheet Series GitHub](https://github.com/OWASP/CheatSheetSeries)

Top Ten
* [OWASP Top Ten Cheat Sheet GitHub](https://github.com/OWASP/Top10)

Types
* [Same Origin Policy Wikipedia](https://en.wikipedia.org/wiki/Same-origin_policy)
* [Content Security Policy Wikipedia](https://en.wikipedia.org/wiki/Content_Security_Policy)

Same Origin
* [Same-origin policy](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy)
* [Google HTTP access control (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)

Content Security Policy (CSP)
* [Google Content Security Policy (CSP)](https://developers.google.com/web/fundamentals/security/csp) and [Mozilla Content Security Policy (CSP)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)

Mixed Content
* [Google What Is Mixed Content?](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/what-is-mixed-content) and [Google Preventing Mixed Content](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/fixing-mixed-content)

<!--
https://en.wikipedia.org/wiki/Clickjacking
https://en.wikipedia.org/wiki/Code_injection

https://en.wikipedia.org/wiki/Computer_security_model
https://en.wikipedia.org/wiki/Operations_security | Operations security - Wikipedia

https://en.wikipedia.org/wiki/Fully_qualified_domain_name | Fully qualified domain name - Wikipedia

## Security- General
      
https://developers.google.com/web/fundamentals/security/

https://www.owasp.org/index.php/Top_10-2017_Top_10 | Top 10-2017 Top 10 - OWASP
https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf | OWASP Top 10 - 2017
https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project | Category:OWASP Top Ten Project - OWASP

https://www.owasp.org/index.php/OWASP_Serverless_Top_10_Project | OWASP Serverless Top 10 Project - OWASP
https://github.com/OWASP/DVSA | OWASP/DVSA: a Damn Vulnerable Serverless Application

Application Security Verification Standard
https://github.com/OWASP/ASVS/tree/master/4.0/en | ASVS/4.0/en at master · OWASP/ASVS

https://teamtreehouse.com/library/owasp-top-10-vulnerabilities | OWASP Top 10 Vulnerabilities Course

https://www.owasp.org/index.php/OWASP_Testing_Guide_v4_Table_of_Contents | OWASP Testing Guide v4 Table of Contents - OWASP

[Using CORS](https://www.html5rocks.com/en/tutorials/cors/)

https://www.owasp.org/index.php/Application_Threat_Modeling | Application Threat Modeling - OWASP
https://www.owasp.org/index.php/Injection_Prevention_Cheat_Sheet | Injection Prevention Cheat Sheet - OWASP
https://www.owasp.org/index.php/OWASP_SAMM_Project | OWASP SAMM Project - OWASP

https://www.owasp.org/index.php/HttpOnly | HttpOnly - OWASP
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF) | Cross-Site Request Forgery (CSRF) - OWASP
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)_Prevention_Cheat_Sheet | Cross-Site Request Forgery (CSRF) Prevention Cheat Sheet - OWASP

https://www.owasp.org/index.php/3rd_Party_Javascript_Management_Cheat_Sheet
https://www.owasp.org/index.php/AJAX_Security_Cheat_Sheet
-->


Django Performance and Optimization
* [Django Performance](https://docs.djangoproject.com/en/dev/topics/performance)
* [Django Database Access Optimization](https://docs.djangoproject.com/en/dev/topics/db/optimization)

Django Deployment
* [Deployment Checklist](https://docs.djangoproject.com/en/dev/howto/deployment/checklist)

## Performance

Python Time Complexity, Performance
* [Python Time Complexity](https://wiki.python.org/moin/TimeComplexity)
* [Python Speed](https://wiki.python.org/moin/PythonSpeed)
* [Python Performance Tips](https://wiki.python.org/moin/PythonSpeed/PerformanceTips)

Python Benchmarking and Profiling
* [profile](https://docs.python.org/3/library/profile.html)
* [timeit](https://docs.python.org/3/library/timeit.html)

Diagnostic tools
* hotshot module?
* cProfile module

<!--
http://scipy.github.io/old-wiki/pages/PerformancePython

27.4. The Python Profilers
https://docs.python.org/3/library/profile.html#module-pstats

https://docs.python.org/3/library/profile.html#introduction-to-the-profilers
https://docs.python.org/3/library/profile.html#instant-user-s-manual
https://docs.python.org/3/library/profile.html#what-is-deterministic-profiling
https://docs.python.org/3/library/profile.html#limitations
https://docs.python.org/3/library/profile.html#calibration
https://docs.python.org/3/library/profile.html#using-a-custom-timer

27.5. timeit — Measure execution time of small code snippets
https://docs.python.org/3/library/timeit.html#basic-examples
https://docs.python.org/3/library/timeit.html#python-interface
https://docs.python.org/3/library/timeit.html#command-line-interface
https://docs.python.org/3/library/timeit.html#examples

https://wiki.python.org/moin/PythonSpeed/Profiling
http://web.archive.org/web/20060506162444/http://wingware.com/doc/howtos/performance-profiling-python-code

10.10. Performance Measurement
https://docs.python.org/3/tutorial/stdlib.html#performance-measurement
10.11. Quality Control
https://docs.python.org/3/tutorial/stdlib.html#quality-control

https://numba.pydata.org/

https://en.wikipedia.org/wiki/Schwartzian_transform
https://wiki.python.org/moin/DecorateSortUndecorate

https://wiki.python.org/moin/ConcatenationTestCode

https://docs.python.org/3/library/sys.html#sys.setcheckinterval
-->

## Debugging

Debugging
* [Software Bug Wikipedia](https://en.wikipedia.org/wiki/Software_bug)
* [Debugger Wikipedia](https://en.wikipedia.org/wiki/Debugger)

## Types of Software Testing

Software Testing
* [Test Automation Wikipedia](https://en.wikipedia.org/wiki/Test_automation)
* [Software Testing Wikipedia](https://en.wikipedia.org/wiki/Software_testing)

Functional and Unit Testing
* [Functional Testing Wikipedia](https://en.wikipedia.org/wiki/Functional_testing)
* [Unit Testing Wikipedia](https://en.wikipedia.org/wiki/Unit_testing)

Other Types of Testing- Performance/Stress
* [Software Performance Testing Wikipedia](https://en.wikipedia.org/wiki/Software_performance_testing)
* [Regression Testing Wikipedia](https://en.wikipedia.org/wiki/Regression_testing)
* [Stress Testing Wikipedia](https://en.wikipedia.org/wiki/Stress_testing_(software))
* [Load Testing Wikipedia](https://en.wikipedia.org/wiki/Load_testing)

Other Types of Testing- Acceptance
* [Acceptance Testing Wikipedia](https://en.wikipedia.org/wiki/Acceptance_testing)
* [Operational Acceptance Testing Wikipedia](https://en.wikipedia.org/wiki/Operational_acceptance_testing)

Other Types of Testing
* [Agile Testing Wikipedia](https://en.wikipedia.org/wiki/Agile_testing)
* [System Integration Testing Wikipedia](https://en.wikipedia.org/wiki/System_integration_testing)
* [System Testing Wikipedia](https://en.wikipedia.org/wiki/System_testing)
* [Integration Testing Wikipedia](https://en.wikipedia.org/wiki/Integration_testing)
* [Smoke Testing Wikipedia](https://en.wikipedia.org/wiki/Smoke_testing_(software))
* [Mutation Testing Wikipedia](https://en.wikipedia.org/wiki/Mutation_testing)

## Django Testing

Django Testing- Official
* [Django Testing Overview](https://docs.djangoproject.com/en/dev/topics/testing/overview)
* [Django Testing](https://docs.djangoproject.com/en/dev/topics/testing)
* [Django Testing Tools](https://docs.djangoproject.com/en/dev/topics/testing/tools)
* [Django Testing Advanced Topics](https://docs.djangoproject.com/en/dev/topics/testing/advanced)

<!--
TestPyramid

"Write integration tests for all pieces of code where you either serialize or deserialize data. This happens more often than you might think. Think about:

Calls to your services' REST API
Reading from and writing to databases
Calling other application's APIs
Reading from and writing to queues
Writing to the filesystem"

https://docs.python.org/3/library/unittest.html#assert-methods
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertEqual | unittest — Unit testing framework — Python 3.8.1 documentation
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertNotEqual
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertRaises

https://docs.pytest.org/en/latest/assert.html#assert
https://www.mattcrampton.com/blog/a_list_of_all_python_assert_methods/
https://twitter.com/pytestdotorg/status/1101959314116210688 | pytest.org on Twitter: "Yes, memorize 30 methods' names and exactly how to call them....... Or learn the assert statement, pytest.raises, and the methods on the data structures you're already using. 🤷… https://t.co/wllbH3vDE3"
https://twitter.com/KokkasKostas/status/1100738165571244034 | Kostas Kokkas on Twitter: "List of assertions used in Python unittesting: https://t.co/BbtOvEKXQ7 #pytest #unittest #DataScience #DataAnalytics #python"

https://docs.djangoproject.com/en/2.2/topics/testing/tools/#testcase | Testing tools | Django documentation | Django
https://docs.python.org/3/library/unittest.html#unittest.TestCase | unittest — Unit testing framework — Python 3.8.1 documentation
https://docs.djangoproject.com/en/2.2/topics/testing/tools/#django.test.TransactionTestCase | Testing tools | Django documentation | Django

https://docs.djangoproject.com/en/3.0/topics/testing/advanced/#using-different-testing-frameworks | Advanced testing topics | Django documentation | Django
https://docs.djangoproject.com/en/3.0/topics/checks/ | System check framework | Django documentation | Django

https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript/#javascript-tests | JavaScript | Django documentation | Django
-->

## Python Testing

Python and Django Debugging
* [bdb](https://docs.python.org/3/library/bdb.html)
* [pdb](https://docs.python.org/3/library/pdb.html)

Python Testing Built-In Tools
* [unittest](https://docs.python.org/3/library/unittest.html)
* [unittest.mock](https://docs.python.org/3/library/unittest.mock.html)
* [doctest](https://docs.python.org/3/library/doctest.html)
* [mock](https://docs.python.org/dev/library/unittest.mock.html)

Terminology
* [Test Case Wikipedia](https://en.wikipedia.org/wiki/Test_case)
* [Mock Object Wikipedia](https://en.wikipedia.org/wiki/Mock_object)
* [Test Stub Wikipedia](https://en.wikipedia.org/wiki/Test_stub)
* [Test Fixture Wikipedia](https://en.wikipedia.org/wiki/Test_fixture)

<!--
Debugging
https://twitter.com/b0rk/status/1144011000208863239 | 🔎Julia Evans🔍 on Twitter: "amazing debugger features… "
https://twitter.com/b0rk/status/1145350304583622656 | 🔎Julia Evans🔍 on Twitter: "how I got better at debugging… "
https://jvns.ca/blog/2019/06/23/a-few-debugging-resources/ | What does debugging a program look like? - Julia Evans
https://twitter.com/b0rk/status/1143509975492374528 | 🔎Julia Evans🔍 on Twitter: "more assumptions to check while debugging (see https://t.co/nhLOmiVkJJ for more like this)… "
https://twitter.com/andrewgodwin/status/1147272951118483457

https://pythontesting.net/agile/test-first-programming/
http://www.extremeprogramming.org/rules/testfirst.html
https://martinfowler.com/bliki/SelfTestingCode.html
https://martinfowler.com/bliki/TestDrivenDevelopment.html
https://learntdd.in/concepts.html

https://en.wikipedia.org/wiki/Scenario_testing
https://martinfowler.com/articles/mocksArentStubs.html
https://thoughtbot.com/blog/i-mock-your-fixtures-too

state behavior versus behavior verification
https://en.wikipedia.org/wiki/Mock_object#Use_in_test-driven_development

Test automation
https://en.wikipedia.org/wiki/Headless_browser

https://martinfowler.com/bliki/PageObject.html
https://selenium-python.readthedocs.io/page-objects.html
https://github.com/SeleniumHQ/selenium/wiki/PageObjects
https://github.com/SeleniumHQ/selenium/wiki/Design-Patterns

https://pypi.org/project/selenium/ | selenium · PyPI
https://github.com/SeleniumHQ/selenium/tree/master/py/selenium/webdriver | selenium/py/selenium/webdriver at master · SeleniumHQ/selenium
-->

## Python and Django Testing and Debugging Tools- Most Relevant Third Party Testing Tools

pytest 
* [pytest](http://pytest.org) and [pytest Docs](https://docs.pytest.org/en/latest)

<!--
https://pythontesting.net/framework/pytest/pytest-introduction/

https://docs.pytest.org/en/latest/ | pytest: helps you write better programs — pytest documentation
https://docs.pytest.org/en/latest/contents.html#toc | Full pytest documentation — pytest documentation
https://docs.pytest.org/en/latest/reference.html | Reference — pytest documentation
https://docs.pytest.org/en/latest/goodpractices.html | Good Integration Practices — pytest documentation

https://docs.pytest.org/en/latest/getting-started.html | Installation and Getting Started — pytest documentation
https://docs.pytest.org/en/latest/unittest.html#unittest | unittest.TestCase Support — pytest documentation

https://docs.pytest.org/en/latest/example/parametrize.html
https://docs.pytest.org/en/latest/parametrize.html
-->

Django
* [pytest-django PyPi](https://pypi.python.org/pypi/pytest-django) and [pytest-django Read the Docs](http://pytest-django.readthedocs.org)

Selenium
* [Selenium](http://www.seleniumhq.org)
* [Selenium WebDriver](https://www.seleniumhq.org/projects/webdriver/)

PyLint
* [Pylint](https://www.pylint.org) and [Pylint GitHub](https://github.com/PyCQA/pylint)

Pylint Django
* [Pylint Django GitHub](https://github.com/PyCQA/pylint-django)

Django Test Plus
* [Django Test Plus](http://django-test-plus.readthedocs.io) and [Django Test Plus GitHub](https://github.com/revsys/django-test-plus)

Python- Django- Debug Toolbar an dPanel
* [Django Debug Toolbar PyPi](https://pypi.python.org/pypi/django-debug-toolbar) 
* [Django Debug Panel GitHub](https://github.com/recamshak/django-debug-panel) and [Django Debug Panel Chrome Web Store](https://chrome.google.com/webstore/detail/django-debug-panel/nbiajhhibgfgkjegbnflpdccejocmbbn)
* [Django Debug Toolbar Read the Docs](http://django-debug-toolbar.readthedocs.org) and [Django Debug Toolbar GitHub](https://github.com/jazzband/django-debug-toolbar)

<!--
https://github.com/behave/behave | behave/behave: BDD, Python style.
https://hypothesis.readthedocs.io/en/latest/
https://cucumber.io/ | Cucumber
https://github.com/cucumber/gherkin-python

https://www.revsys.com/tidbits/pytest-support-django-test-plus/ | pytest support for django-test-plus

https://django-test-plus.readthedocs.io/en/latest/usage.html | Usage — django-test-plus 1.0.9 documentation

https://testautomationu.applitools.com/
https://testautomationu.applitools.com/unit-testing/ | Overview
https://testautomationu.applitools.com/learningpaths.html?id=web-ui-python-path

Testing pyramid
https://automationpanda.com/2018/08/01/the-testing-pyramid/
https://automationpanda.com/bdd/
https://automationpanda.com/python/

https://www.packtpub.com/web-development/pytest-quick-start-guide
https://pragprog.com/book/bopytest/python-testing-with-pytest | Python Testing with pytest: Simple, Rapid, Effective, and Scalable by Brian Okken | The Pragmatic Bookshelf

https://github.com/augustogoulart/awesome-pytest | augustogoulart/awesome-pytest: A curated list of awesome pytest resources

http://pythontesting.net/start-here/
https://pythontesting.net/framework/pytest/pytest-introduction/
http://docs.python-guide.org/en/latest/writing/tests/ | Testing Your Code — The Hitchhiker's Guide to Python
-->

<!--
Beyond Unit Tests
https://www.youtube.com/watch?v=Z9ghRBEgnps&t=257s
https://github.com/AndyLPK247/djangocon-2019-web-ui-testing

https://automationpanda.com/2018/10/29/pygotham-2018-reflections/ | PyGotham 2018 Reflections | Automation Panda
https://2018.pygotham.org/talks/egad-how-do-we-start-writing-better-tests/ | Egad! How Do We Start Writing (Better) Tests? - PyGotham 2018
https://automationpanda.com/2018/08/02/egad-how-do-we-start-writing-better-tests/ | EGAD! How Do We Start Writing (Better) Tests? | Automation Panda
https://www.youtube.com/watch?v=z0XC0tGGFXI | Egad! How Do We Start Writing Better Tests? - YouTube

https://twitter.com/AutomationPanda/status/1141585091908575232 | “Pandy” Knight on Twitter: "Cool! Thanks. Let me know if you have questions.… "

* [Automation Panda](https://automationpanda.com)
https://automationpanda.com/2018/09/17/book-review-python-testing-with-pytest/ | Book Review: Python Testing with pytest | Automation Panda
https://github.com/AndyLPK247/python-testing-101 | AndyLPK247/python-testing-101: Example projects for the Python Testing 101 series from Automation Panda
https://automationpanda.com/2017/02/04/bdd-101-frameworks/ | BDD 101: Frameworks | Automation Panda

https://twitter.com/AutomationPanda | Automation Panda (@AutomationPanda) | Twitter

https://twitter.com/AutomationPanda/status/1097140065577431041
https://twitter.com/AutomationPanda/status/1048275359303708673
https://twitter.com/AutomationPanda/status/1023346925771345920
https://twitter.com/AutomationPanda/status/1061393338165837825

DjangoCon Keynote by Ana

https://pyvideo.org/pyohio-2019/adopt-a-pytest.html

https://www.hillelwayne.com/talks/beyond-unit-tests/
https://www.youtube.com/watch?v=MYucYon2-lk
-->

## Python and Django Testing and Debugging Tools- Less Relevant Third Party Testing Tools

Nose (Unit Test Extension)
* [Nose 2 Docs](https://docs.nose2.io) and [Nose 2 GitHub](https://github.com/nose-devs/nose2)

Django Nose
* [Django Nose GitHub](https://github.com/django-nose/django-nose)

## Python and Django Debugging and Testing

Testing
* [Test-Driven Development with Python Chapter 8- Testing Deployment Using a Staging Site](http://chimera.labs.oreilly.com/books/1234000000754/ch08.html#_tdd_and_the_danger_areas_of_deployment) 
* [Obey the Testing Goat! (Harry J.W. Percival)](https://www.obeythetestinggoat.com)

Django Testing
* [Obey the Testing Goat: Django Class-Based Views (CBVs)](https://www.obeythetestinggoat.com/book/appendix_Django_Class-Based_Views.html)

<!--
Python- Books- O'Reilly Test-Driven Development with Python and Selenium

https://www.obeythetestinggoat.com/book/appendix_bdd.html | Behaviour-Driven Development (BDD)
https://www.obeythetestinggoat.com/book/chapter_unit_test_first_view.html | Testing a Simple Home Page with Unit Tests
-->
