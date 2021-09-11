# Tools- Python and Django Testing, Profiling, Deployment, and Security

<!--
## Testing

Testing
https://testautomationu.applitools.com/learningpaths.html | Learning Paths | Applitools
https://testautomationu.applitools.com/selenium-webdriver-python-tutorial/chapter2.html | Chapter 2 - Setting Up pytest
https://testautomationu.applitools.com/python-tutorial/chapter8.html | Chapter 8 - Classes

https://applitools.com/
https://applitools.com/blog/guide-to-test-automation-code-reviews/ | Guide to Conducting Test Automation Code Reviews - Automated Visual Testing | Applitools
https://applitools.com/products-eyes/ | Applitools Eyes > Automated Visual Testing | Applitools
https://eyes.applitools.com/app/test-results/00000251785171536301/?accountId=V09Xrww-9EGBGP0uZjJ6bw~~ | Applitools Eyes

https://twitter.com/ameter/status/1383626060609191940 | Ariel Meter on Twitter: "This course by @techgirl1908 is a MUST for every Test Lead. It will teach you how to stop an “I-want-everything-automated-with -X-tool” stakeholder and make all the right questions for a successful Automation strategy." / Twitter
https://twitter.com/techgirl1908/status/1382709959788523520 | Angie Jones on Twitter: "Stoked to announce we've just added a new Learning Path to @TestAutomationU: API Python🐍 And with that, a brand new course, API Testing in Python taught by @automationhacks🎉 All courses FREE as always❤️ Learning Path: https://t.co/oEMJH2AaJm Course: https://t.co/R6QS54Ac8I https://t.co/hmbzGwfaqh" / Twitter

Applitools
https://twitter.com/techgirl1908/status/1389327137690296322 | Angie Jones on Twitter: "LOL, ok so no one else says they didn't know... Python: https://t.co/K9Hi8R4xHl JS: https://t.co/xItuVb9MAh Java:https://t.co/eQ9rqO1Dp5 All free! 🤗" / Twitter

Java
https://angiejones.tech/free-java-course-test-automation/ | My FREE Java Course - Angie Jones
https://testautomationu.applitools.com/java-programming-course/ | Java Programming

Automation framework
https://robotframework.org/

App and browser testing
https://www.browserstack.com/
-->


<!--
tox
https://twitter.com/avallbona/status/1270755378654064641 | underdog on Twitter: "the --devenv command option https://t.co/l0ZU3C9vtP is a game changer feature, added recently by @codewithanthony #kudos" / Twitter

https://lukeplant.me.uk/blog/posts/test-smarter-not-harder/ | Test smarter, not harder - lukeplant.me.uk

https://pypi.org/project/pep8/ | pep8 · PyPI
https://launchpad.net/pyflakes/ | Pyflakes in Launchpad
https://pypi.org/project/flake8/ | flake8 · PyPI

Test plugins
https://github.com/pytest-dev/pytest-bdd | pytest-dev/pytest-bdd: BDD library for the py.test runner
https://pypi.python.org/pypi/pytest-xdist | pytest-xdist 1.20.1 : Python Package Index
https://talkpython.fm/episodes/show/267/15-amazing-pytest-plugins | Episode #267 15 amazing pytest plugins - [Talk Python To Me Podcast]

https://boto3.readthedocs.io/en/latest/index.html

state behavior versus behavior verification
https://en.wikipedia.org/wiki/Mock_object#Use_in_test-driven_development

"Write integration tests for all pieces of code where you either serialize or deserialize data. This happens more often than you might think. Think about:

Calls to your services' REST API
Reading from and writing to databases
Calling other application's APIs
Reading from and writing to queues
Writing to the filesystem"
-->


<!--
http://docs.python-guide.org/en/latest/writing/tests/ | Testing Your Code — The Hitchhiker's Guide to Python

https://www.hillelwayne.com/talks/beyond-unit-tests/
https://www.youtube.com/watch?v=MYucYon2-lk

https://pyvideo.org/pyohio-2019/adopt-a-pytest.html

DjangoCon Keynote by Ana
-->

<!--
https://pythontesting.net/framework/pytest/pytest-introduction/

https://pythontesting.net/agile/test-first-programming/
http://www.extremeprogramming.org/rules/testfirst.html
https://martinfowler.com/bliki/SelfTestingCode.html
https://martinfowler.com/bliki/TestDrivenDevelopment.html
https://learntdd.in/concepts.html

https://en.wikipedia.org/wiki/Scenario_testing
https://martinfowler.com/articles/mocksArentStubs.html
https://thoughtbot.com/blog/i-mock-your-fixtures-too
-->

<!--
https://hynek.me/articles/document-your-tests/

Django Testing
https://www.b-list.org/weblog/2017/apr/03/testing-django-apps/ | Let's talk about testing Django apps
https://lincolnloop.com/blog/using-setuppy-your-django-project/ | Using setup.py in Your (Django) Project | Lincoln Loop
https://www.ericholscher.com/blog/2009/jun/29/enable-setuppy-test-your-django-apps/ | Enable setup.py test in your Django apps — Eric Holscher - Surfing in Kansas
-->



## Python Debugger and doctests

Python Debugger
* [bdb](https://docs.python.org/3/library/bdb.html)
* [pdb](https://docs.python.org/3/library/pdb.html)

doctest
* [doctest](https://docs.python.org/3/library/doctest.html)

## Python Testing- unittest

Python Testing Built-In Tools
* [unittest](https://docs.python.org/3/library/unittest.html)
* [unittest.mock](https://docs.python.org/3/library/unittest.mock.html)

<!--
https://docs.python.org/3/library/unittest.html#unittest.TestCase | unittest — Unit testing framework — Python 3.8.1 documentation

https://docs.python.org/3/library/unittest.html#assert-methods
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertEqual | unittest — Unit testing framework — Python 3.8.1 documentation
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertNotEqual
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertRaises
-->

### Django Testing

Django Testing- Official
* [Django Testing Overview](https://docs.djangoproject.com/en/dev/topics/testing/overview)
* [Django Testing](https://docs.djangoproject.com/en/dev/topics/testing)
* [Django Testing Tools](https://docs.djangoproject.com/en/dev/topics/testing/tools)
* [Django Testing Advanced Topics](https://docs.djangoproject.com/en/dev/topics/testing/advanced)

<!--
Django raises built-in Python exceptions when appropriate.
https://docs.python.org/3/library/exceptions.html#built-in-exceptions

https://docs.djangoproject.com/en/3.0/topics/testing/advanced/#using-different-testing-frameworks | Advanced testing topics | Django documentation | Django
https://docs.djangoproject.com/en/2.2/topics/testing/tools/#testcase | Testing tools | Django documentation | Django


https://docs.djangoproject.com/en/2.2/topics/testing/tools/#django.test.TransactionTestCase | Testing tools | Django documentation | Django
https://docs.djangoproject.com/en/3.0/topics/checks/ | System check framework | Django documentation | Django


https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript/#javascript-tests | JavaScript | Django documentation | Django
-->

## Flask Testing

<!--
Flask
https://github.com/pallets/flask/ | pallets/flask: The Python micro framework for building web applications.
https://github.com/pytest-dev/pytest-flask | pytest-dev/pytest-flask: A set of pytest fixtures to test Flask applications
-->

## Big O Notation

* [Big O Cheat Sheet](http://www.bigocheatsheet.com)

## Django Deployment

Django Deployment
* [Deployment Checklist](https://docs.djangoproject.com/en/dev/howto/deployment/checklist)

## Django Performance, Optimization, Deployment

Django Performance and Optimization
* [Django Performance](https://docs.djangoproject.com/en/dev/topics/performance)
* [Django Database Access Optimization](https://docs.djangoproject.com/en/dev/topics/db/optimization)

<!--
Exceptions
https://docs.python.org/3/library/exceptions.html | Built-in Exceptions — Python 3.9.5 documentation

Assert
https://docs.python.org/3/reference/simple_stmts.html#the-assert-statement
-->

## Django Core Dev Security

* [Django Security](https://docs.djangoproject.com/en/dev/releases/security/)
* [How Django Discloses Security Issues](https://docs.djangoproject.com/en/dev/internals/security/#how-django-discloses-security-issues)

### Django Security

* [Clickjacking Protection](https://docs.djangoproject.com/en/dev/ref/clickjacking/)
* [HTTP Strict Transport Security](https://docs.djangoproject.com/en/dev/ref/middleware/#http-strict-transport-security)
* [Security Middleware](https://docs.djangoproject.com/en/dev/ref/middleware/#django.middleware.security.SecurityMiddleware)



<!--
## Test Automation University

https://testautomationu.applitools.com/ | Test Automation University | Applitools
https://testautomationu.applitools.com/unit-testing/ | Overview
https://testautomationu.applitools.com/python-tutorial/
https://testautomationu.applitools.com/learningpaths.html?id=web-ui-python-path
https://testautomationu.applitools.com/selenium-webdriver-python-tutorial/ | Selenium WebDriver with Python
-->

<!--
## Automation Panda

Testing pyramid
https://automationpanda.com/2018/08/01/the-testing-pyramid/

Sites
* [Automation Panda](https://automationpanda.com)
https://twitter.com/AutomationPanda | Automation Panda (@AutomationPanda) | Twitter
https://automationpanda.com/python/
https://automationpanda.com/2017/03/14/python-testing-101-pytest/ | Python Testing 101: pytest | Automation Panda
https://automationpanda.com/bdd/
https://automationpanda.com/tag/development/

https://automationpanda.com/2020/07/28/mentoring-software-testers/ | Mentoring Software Testers | Automation Panda
-->

<!--
## Pytest

https://testdriven.io/ | Test Driven Development Courses

Real Python
https://realpython.com/pytest-python-testing/ | Effective Python Testing With Pytest – Real Python
https://realpython.com/pytest-python-testing/#fixtures-managing-state-and-dependencies | Effective Python Testing With Pytest – Real Python
https://realpython.com/lessons/assertions-and-tryexcept/ | Assertions and Try/Except – Real Python
https://dbader.org/blog/python-assert-tutorial | Assert Statements in Python – dbader.org

Django/pytest
https://realpython.com/django-pytest-fixtures/ | How to Provide Test Fixtures for Django Models in Pytest – Real Python

Brian Okken
http://pythontesting.net/start-here/

Recommended!
https://pragprog.com/book/bopytest/python-testing-with-pytest | Python Testing with pytest: Simple, Rapid, Effective, and Scalable by Brian Okken | The Pragmatic Bookshelf
-->

<!--
Talks

Automation Panda

Beyond Unit Tests
https://www.youtube.com/watch?v=Z9ghRBEgnps&t=257s
https://github.com/AndyLPK247/djangocon-2019-web-ui-testing

https://2018.pygotham.org/talks/egad-how-do-we-start-writing-better-tests/ | Egad! How Do We Start Writing (Better) Tests? - PyGotham 2018
https://automationpanda.com/2018/08/02/egad-how-do-we-start-writing-better-tests/ | EGAD! How Do We Start Writing (Better) Tests? | Automation Panda
https://www.youtube.com/watch?v=z0XC0tGGFXI | Egad! How Do We Start Writing Better Tests? - YouTube
https://twitter.com/AutomationPanda/status/1048275359303708673

https://github.com/AndyLPK247/python-testing-101 | AndyLPK247/python-testing-101: Example projects for the Python Testing 101 series from Automation Panda

https://twitter.com/AutomationPanda/status/1141585091908575232 | “Pandy” Knight on Twitter: "Cool! Thanks. Let me know if you have questions.… "

https://twitter.com/AutomationPanda/status/1023346925771345920
BDD
https://twitter.com/AutomationPanda/status/1061393338165837825
-->

## Debugging

Debugging
* [Software Bug Wikipedia](https://en.wikipedia.org/wiki/Software_bug)
* [Debugger Wikipedia](https://en.wikipedia.org/wiki/Debugger)

## Important Testing Terminology

Important
* [Functional Testing Wikipedia](https://en.wikipedia.org/wiki/Functional_testing)
* [Unit Testing Wikipedia](https://en.wikipedia.org/wiki/Unit_testing)
* [Software Performance Testing Wikipedia](https://en.wikipedia.org/wiki/Software_performance_testing)
* [Regression Testing Wikipedia](https://en.wikipedia.org/wiki/Regression_testing)

* [Test Case Wikipedia](https://en.wikipedia.org/wiki/Test_case)
* [Mock Object Wikipedia](https://en.wikipedia.org/wiki/Mock_object)
* [Test Stub Wikipedia](https://en.wikipedia.org/wiki/Test_stub)
* [Test Fixture Wikipedia](https://en.wikipedia.org/wiki/Test_fixture)

## Types of Software Testing

Software Testing
* [Test Automation Wikipedia](https://en.wikipedia.org/wiki/Test_automation)
* [Software Testing Wikipedia](https://en.wikipedia.org/wiki/Software_testing)

Other Types of Testing- Performance/Stress
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

Other Types of Testing
* [Software Performance Testing Wikipedia](https://en.wikipedia.org/wiki/Software_performance_testing)

<!--
https://en.wikipedia.org/wiki/Behavior-driven_development
-->


## pytest

pytest 
* [pytest](http://pytest.org) and [pytest Docs](https://docs.pytest.org/en/latest)

<!--
pytest-selenium (plugin)
https://pytest-selenium.readthedocs.io/en/latest/user_guide.html

https://github.com/seleniumbase/SeleniumBase | seleniumbase/SeleniumBase: ✅ Automate & test 10x faster with Selenium & pytest. Batteries included.

https://pytest-selenium.readthedocs.io/en/latest/user_guide.html


https://github.com/pytest-dev/pytest | pytest-dev/pytest: The pytest framework makes it easy to write small tests, yet scales to support complex functional testing

https://docs.pytest.org/en/latest/ | pytest: helps you write better programs — pytest documentation

https://docs.pytest.org/en/latest/contents.html#toc | Full pytest documentation — pytest documentation
https://docs.pytest.org/en/latest/reference.html | Reference — pytest documentation
https://docs.pytest.org/en/latest/getting-started.html | Installation and Getting Started — pytest documentation

https://docs.pytest.org/en/latest/goodpractices.html | Good Integration Practices — pytest documentation
https://docs.pytest.org/en/latest/unittest.html#unittest | unittest.TestCase Support — pytest documentation

https://docs.pytest.org/en/latest/example/parametrize.html
https://docs.pytest.org/en/latest/parametrize.html

https://docs.pytest.org/en/latest/assert.html#assert

Assert
https://www.mattcrampton.com/blog/a_list_of_all_python_assert_methods/
https://twitter.com/pytestdotorg/status/1101959314116210688 | pytest.org on Twitter: "Yes, memorize 30 methods' names and exactly how to call them....... Or learn the assert statement, pytest.raises, and the methods on the data structures you're already using. 🤷… https://t.co/wllbH3vDE3"
https://twitter.com/KokkasKostas/status/1100738165571244034 | Kostas Kokkas on Twitter: "List of assertions used in Python unittesting: https://t.co/BbtOvEKXQ7 #pytest #unittest #DataScience #DataAnalytics #python"
-->

<!--
pytest

pytest Books
https://automationpanda.com/2018/09/17/book-review-python-testing-with-pytest/ | Book Review: Python Testing with pytest | Automation Panda
https://www.packtpub.com/web-development/pytest-quick-start-guide

https://github.com/augustogoulart/awesome-pytest | augustogoulart/awesome-pytest: A curated list of awesome pytest resources

Test Anything Protocol
https://en.wikipedia.org/wiki/Test_Anything_Protocol
https://twitter.com/mblayman/status/1222200715570970624 | Matt Layman on Twitter: "I released a new version of pytest-tap today that let's you use the Test Anything Protocol (TAP) for #pytest. This version drops support for Python 2. https://t.co/Mm7fKz0Gfg" / Twitter
-->


## Django Testing

Django
* [pytest-django PyPi](https://pypi.python.org/pypi/pytest-django) and [pytest-django Read the Docs](http://pytest-django.readthedocs.org)

Django Test Plus
* [Django Test Plus](http://django-test-plus.readthedocs.io) and [Django Test Plus GitHub](https://github.com/revsys/django-test-plus)

<!--
DRF Testing
https://www.django-rest-framework.org/api-guide/testing/ | Testing - Django REST framework
-->

<!--
django-selenium
https://pypi.org/project/django-selenium/


pytest-django (plugin)
https://pytest-django.readthedocs.io/en/latest/database.html | Database creation/re-use — pytest-django documentation
https://readthedocs.org/projects/pytest-django/downloads/pdf/latest/

pytest fixture
django-test-plus
https://www.revsys.com/tidbits/pytest-support-django-test-plus/ | pytest support for django-test-plus

django-test-plus
https://django-test-plus.readthedocs.io/en/latest/usage.html | Usage — django-test-plus 1.0.9 documentation
https://django-test-plus.readthedocs.io/en/latest/usage.html#testing-drf-views
-->


<!--
Automation Panda

Property
https://hypothesis.readthedocs.io/en/latest/
https://github.com/HypothesisWorks/hypothesis| HypothesisWorks/hypothesis: Hypothesis is a powerful, flexible, and easy to use library for property-based testing.

BDD
https://automationpanda.com/2017/02/04/bdd-101-frameworks/ | BDD 101: Frameworks | Automation Panda
https://github.com/behave/behave | behave/behave: BDD, Python style.
https://cucumber.io/ | Cucumber
https://github.com/cucumber/gherkin-python
-->

<!--
Other Tools

https://pypi.org/project/pytest-freezegun/ | pytest-freezegun · PyPI
https://github.com/spulec/freezegun | spulec/freezegun: Let your Python tests travel through time

https://factoryboy.readthedocs.io/en/latest/ | factory_boy — Factory Boy latest documentation
https://faker.readthedocs.io/en/master/providers/faker.providers.address.html | faker.providers.address — Faker 4.1.2 documentation
https://faker.readthedocs.io/en/master/ | Welcome to Faker’s documentation! — Faker 4.1.2 documentation
https://pypi.org/project/django-faker/ | django-faker · PyPI
-->

## Selenium

* [Selenium](http://www.seleniumhq.org)
* [Selenium WebDriver](https://www.seleniumhq.org/projects/webdriver/)

<!--
Test automation
https://en.wikipedia.org/wiki/Headless_browser

https://martinfowler.com/bliki/PageObject.html
https://selenium-python.readthedocs.io/page-objects.html
https://github.com/SeleniumHQ/selenium/wiki/PageObjects
https://github.com/SeleniumHQ/selenium/wiki/Design-Patterns

https://pypi.org/project/selenium/ | selenium · PyPI
https://github.com/SeleniumHQ/selenium/tree/master/py/selenium/webdriver | selenium/py/selenium/webdriver at master · SeleniumHQ/selenium
-->

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

https://www.obeythetestinggoat.com/using-the-built-in-views-and-forms-for-new-user-registration-in-django.html | Obey the Testing Goat!
-->

## Python and Django Testing and Debugging Tools- Most Relevant Third Party Testing Tools (Besides pytest and Selenium)

PyLint
* [Pylint](https://www.pylint.org) and [Pylint GitHub](https://github.com/PyCQA/pylint)

Pylint Django
* [Pylint Django GitHub](https://github.com/PyCQA/pylint-django)

Python- Django- Debug Toolbar and Panel
* [Django Debug Toolbar PyPi](https://pypi.python.org/pypi/django-debug-toolbar) 
* [Django Debug Panel GitHub](https://github.com/recamshak/django-debug-panel) and [Django Debug Panel Chrome Web Store](https://chrome.google.com/webstore/detail/django-debug-panel/nbiajhhibgfgkjegbnflpdccejocmbbn)
* [Django Debug Toolbar Read the Docs](http://django-debug-toolbar.readthedocs.org) and [Django Debug Toolbar GitHub](https://github.com/jazzband/django-debug-toolbar)

## Python and Django Testing and Debugging Tools- Less Relevant Third Party Testing Tools

Nose (Unit Test Extension)
* [Nose 2 Docs](https://docs.nose2.io) and [Nose 2 GitHub](https://github.com/nose-devs/nose2)

Django Nose
* [Django Nose GitHub](https://github.com/django-nose/django-nose)


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
Tools matrix
https://www.integralist.co.uk/posts/profiling-python/


27.4. The Python Profilers
https://docs.python.org/3/library/profile.html#module-pstats
https://docs.python.org/3/library/profile.html#pstats.Stats

https://github.com/pyutils/line_profiler
https://docs.python.org/3/library/tracemalloc.html

10.10. Performance Measurement
https://docs.python.org/3/tutorial/stdlib.html#performance-measurement
10.11. Quality Control
https://docs.python.org/3/tutorial/stdlib.html#quality-control


https://wiki.python.org/moin/PythonSpeed/Profiling
http://web.archive.org/web/20060506162444/http://wingware.com/doc/howtos/performance-profiling-python-code

https://en.wikipedia.org/wiki/Schwartzian_transform
https://wiki.python.org/moin/DecorateSortUndecorate
https://wiki.python.org/moin/ConcatenationTestCode

https://numba.pydata.org/
http://scipy.github.io/old-wiki/pages/PerformancePython

https://docs.python.org/3/library/sys.html#sys.setcheckinterval
-->


## Time Complexity and Optimization- Improvement Methods

Improvement Methods
* [Profiling Wikipedia](https://en.wikipedia.org/wiki/Profiling_(computer_programming))
* [Performance Tuning Wikipedia](https://en.wikipedia.org/wiki/Performance_tuning)
* [Logging Wikipedia](https://en.wikipedia.org/wiki/Logging)
* [Telemetry Wikipedia](https://en.wikipedia.org/wiki/Telemetry)

Improvement Methods
* [Big O Notation Wikipedia](https://en.wikipedia.org/wiki/Big_O_notation)
* [Dynamic Program Analysis Wikipedia](https://en.wikipedia.org/wiki/Dynamic_program_analysis)
* [McCabe's Cyclomatic Complexity Wikipedia](https://en.wikipedia.org/wiki/Cyclomatic_complexity)

<!--
https://en.wikipedia.org/wiki/Dynamic_program_analysis

https://en.wikipedia.org/wiki/Benchmark_(computing) | Benchmark (computing) - Wikipedia


https://twitter.com/simonw/status/1262970529746612224 | Simon Willison on Twitter: "Activity Monitor on my Mac shows Python running 438.9% CPU (SHA256 hashing 40,000 files using 5 threads) so it's definitely running across multiple cores. And the program seems to complete about 4x faster. So if, like me, you've mostly avoided threads in Python give them a go!" / Twitter

Profiling
https://www.youtube.com/watch?v=ey_P64E34g0&feature=youtu.be
https://github.com/asottile/importtime-waterfall/
har http timing

https://www.blog.pythonlibrary.org/2020/04/14/an-overview-of-profiling-tools-for-python/

https://jvns.ca/blog/2017/12/17/how-do-ruby---python-profilers-work-/ | How do Ruby & Python profilers work? - Julia Evans

Nice README!
https://github.com/open-telemetry/opentelemetry-python | open-telemetry/opentelemetry-python: The OpenTelemetry Python Client
https://opentelemetry-python.readthedocs.io/en/stable/getting-started.html
https://github.com/jaegertracing/jaeger
https://github.com/jaegertracing/jaeger-client-python
https://prometheus.io/

https://github.com/joerick/pyinstrument | joerick/pyinstrument: 🚴 Call stack profiler for Python. Shows you why your code is slow!


https://knasmueller.net/measure-code-execution-time-accurately-in-python

Tools
https://pypi.org/project/memory-profiler/ | memory-profiler · PyPI

https://engineering.instagram.com/profiling-cpython-at-instagram-89d4cbeeb898 | Profiling CPython at Instagram – Instagram Engineering

https://zapier.com/engineering/profiling-python-boss/ | Profiling Python Like a Boss - The Zapier Engineering Blog | Zapier


https://medium.freecodecamp.org/django-performance-optimization-looking-for-the-bottlenecks-8583789e341b | Django Performance Optimization: The Search for Bottlenecks

https://blogs.msdn.microsoft.com/ie/2010/09/14/performance-what-common-benchmarks-measure/ | Performance: What Common Benchmarks Measure – IEBlog
-->


<!--
lines of code (loc) versus complexity

https://en.wikipedia.org/wiki/Time_complexity#Sub-linear_time

https://en.wikipedia.org/wiki/Mathematical_optimization
https://en.wikipedia.org/wiki/Computational_complexity_theory

https://en.wikipedia.org/wiki/Category:Analysis_of_algorithms
https://en.wikipedia.org/wiki/Analysis_of_algorithms
https://en.wikipedia.org/wiki/Analysis_of_algorithms#Evaluating_run-time_complexity

https://en.wikipedia.org/wiki/Sorting_algorithm#Comparison_of_algorithms
https://en.wikipedia.org/wiki/Computational_complexity_of_mathematical_operations#Arithmetic_functions
-->

## General Big O Rules

Concepts- Time and Space Complexity
* [Time Complexity Wikipedia](https://en.wikipedia.org/wiki/Time_complexity)
* [Space Complexity Wikipedia](https://en.wikipedia.org/wiki/Space_complexity)

Big O Notation
* [Big O Notation Order of Common Functions Wikipedia](https://en.wikipedia.org/wiki/Big_O_notation#Orders_of_common_functions)
* [Best, Worst, and Average Case Wikipedia](https://en.wikipedia.org/wiki/Best,_worst_and_average_case)
* [Computational Complexity of Mathematical Operations Wikipedia](https://en.wikipedia.org/wiki/Computational_complexity_of_mathematical_operations)
* [Big O Cheat Sheet](http://www.bigocheatsheet.com)

Linear versus Constant Time
* [Logarithmic Time O(log n) Wikipedia](https://en.wikipedia.org/wiki/Time_complexity#Logarithmic_time)
* [Constant Time O(1) Wikipedia](https://en.wikipedia.org/wiki/Time_complexity#Constant_time)
* [Linear Time O(n) Wikipedia](https://en.wikipedia.org/wiki/Time_complexity#Linear_time)

Big O Notation- Terminology
* [Exponentiation Wikipedia](https://en.wikipedia.org/wiki/Exponentiation)
* [Logarithm Wikipedia](https://en.wikipedia.org/wiki/Logarithm)
* [Order of Magnitude Wikipedia](https://en.wikipedia.org/wiki/Order_of_magnitude)

<!--
https://github.com/ro31337/bigoposter/blob/master/bigoposter.pdf

https://en.wikipedia.org/wiki/Asymptotic_analysis

https://simple.wikipedia.org/wiki/Space-time_tradeoff | Space-time tradeoff - Simple English Wikipedia, the free encyclopedia
https://www.geeksforgeeks.org/g-fact-86/ | What does 'Space Complexity' mean? - GeeksforGeeks

https://www.youtube.com/watch?v=duvZ-2UK0fc

https://nedbatchelder.com/text/bigo.html
Python Complexities
https://nedbatchelder.com/text/bigo/bigo.html#13
The Graph
https://nedbatchelder.com/text/bigo/bigo.html#12
Small Numbers
https://nedbatchelder.com/text/bigo/bigo.html#17

Trade-Offs
https://nedbatchelder.com/text/bigo/bigo.html#14
Slow/Fast
https://nedbatchelder.com/text/bigo/bigo.html#15
More Possibilities
https://nedbatchelder.com/text/bigo/bigo.html#16

https://nedbatchelder.com/text/slowsgrows.html
https://nedbatchelder.com/blog/201710/how_code_slows_as_data_grows.html

https://drive.google.com/drive/u/0/folders/0B9l0_ldK09SOfjE3R1c2LTcxSU8xSGxXNkJpOF9iQ0JMV1NLUDhnUmlXVm50R0tLTGFUeEE | Big-O Cheat Sheet - Google Drive
https://docs.google.com/spreadsheets/d/1hyxEEFvF5zBcpC3ALPVPyE8kJ1Soiwd4jpwKjHgzG6o/edit#gid=0 | Big-O cheatsheet - Google Sheets
https://www.youtube.com/watch?v=V6mKVRU1evU | Big O Notations - YouTube

https://www.khanacademy.org/computing/computer-science/algorithms/asymptotic-notation/a/big-big-omega-notation | (2) Big-Ω (Big-Omega) notation (article) | Khan Academy
https://www.khanacademy.org/computing/computer-science/algorithms/asymptotic-notation/a/big-big-theta-notation | Big-θ (Big-Theta) notation (article) | Khan Academy
https://www.khanacademy.org/computing/computer-science/algorithms/asymptotic-notation/a/big-o-notation | Big-O notation (article) | Algorithms | Khan Academy
-->

<!--
Analysis of Algorithms
https://www.geeksforgeeks.org/fundamentals-of-algorithms/#AnalysisofAlgorithms
-->

## Third Party Load Balancing, Task Queue/Job Queue, Distributed Message Passing, Caching

* [NGINX](https://www.nginx.com/)
* [Celery](http://www.celeryproject.org) and [Celery GitHub](https://github.com/celery/celery)  
* [Celery and Django](http://docs.celeryproject.org/en/2.5/django/first-steps-with-django.html) 
* [RQ (Redis Queue)](http://python-rq.org/)
* [RabbitMQ](https://www.rabbitmq.com/)
* [Redis](https://redis.io/)
* [Memcached](https://memcached.org/)

<!--
https://en.wikipedia.org/wiki/MQTT | MQTT - Wikipedia

https://realpython.com/asynchronous-tasks-with-django-and-celery/ | Asynchronous Tasks With Django and Celery – Real Python
https://www.fullstackpython.com/task-queues.html
-->

## Azure

<!--
https://twitter.com/anthonypjshaw/status/1270205981616529408 | Anthony Shaw 🐍 on Twitter: "If you use @AzureDevOps Pipelines and @pytestdotorg please can you try pytest-azurepipelines==1.0.0rc3 it has loads of changes including embedding code coverage into the Pipelines UI from https://t.co/NjlLN1tfOD I need more testers! https://t.co/Mza0ke6UiS https://t.co/0FiABgr3l5" / Twitter

https://github.com/Azure/azure-quickstart-templates
https://twitter.com/di_codes/status/1295793468762136576

https://tonybaloney.github.io/posts/django-on-azure-beyond-hello-world.html | Django on Azure - beyond "hello world"

Hynek- Azure Pipelines
Publish Python packages in Azure Pipelines
https://docs.microsoft.com/en-us/azure/devops/pipelines/artifacts/pypi?view=azure-devops&tabs=yaml&viewFallbackFrom=vsts
https://docs.microsoft.com/en-us/azure/devops/pipelines/artifacts/pypi?view=azure-devops&tabs=yaml
https://hynek.me/articles/simple-python-azure-pipelines/ | Python in Azure Pipelines, Step by Step · Homepage of Hynek Schlawack
https://docs.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops&tabs=yaml | Container Jobs in Azure Pipelines and TFS - Azure Pipelines | Microsoft Docs

Azure Piplines
https://azure.microsoft.com/en-us/services/devops/pipelines/
https://docs.microsoft.com/en-us/azure/devops/pipelines/migrate/from-travis?view=azure-devops
https://medium.com/@anthonypjshaw/azure-pipelines-with-python-by-example-aa65f4070634
https://github.com/asottile/azure-pipeline-templates

https://github.com/trallard/pycon2020-azure-functions | trallard/pycon2020-azure-functions: ⚡️ 🏻‍♀️ Sponsored tutorial content for PyCon 2020
-->

## Hosts, Containers, Serverless, Functions, Pipelines

Containers
* [Kubernetes](http://kubernetes.io) and [Kubernetes Docs](https://kubernetes.io/docs/home)
* [Docker](https://www.docker.com) and [Docker Docs](https://docs.docker.com)
* ["Getting Started with Docker for Mac"](https://docs.docker.com/docker-for-mac)

AWS- Lambda
* [AWS Lambda](http://aws.amazon.com/lambda) and [AWS Lambda Documentation](http://docs.aws.amazon.com/lambda/latest/dg/welcome.html) 
* [AWS API Gateway](https://aws.amazon.com/api-gateway/)
* [Serverless GitHub](https://github.com/serverless/serverless) 
* [Zappa GitHub](https://github.com/Miserlou/Zappa)

Additional Serverless
* [Google Cloud Functions](https://cloud.google.com/functions/docs)
* [Firebase Functions](https://firebase.google.com/features/functions)
* [Azure Functions](https://azure.microsoft.com/en-us/services/functions) and [Azure Functions GitHub](https://github.com/Azure/Azure-Functions)

<!--
https://developers.google.com/actions/templates/first-app | Templates  |  Actions on Google  |  Google Developers

Google Cloud

https://twitter.com/di_codes/status/1215368211211923456 | Dustin Ingram on Twitter: "Happy to announce the release of a Function Framework for Python via @GoogleOSS. 🎉 It lets you run a Cloud Function locally for development or deploy it to other services (like Cloud Run)... without having to change your function at all. More details: https://t.co/87xrnAdvg3" / Twitter
https://dev.to/googlecloud/portable-cloud-functions-with-the-python-functions-framework-a6a | Portable Cloud Functions with the Python Functions Framework - DEV Community 👩‍💻👨‍💻

Google Cloud Django/Python
https://github.com/GoogleCloudPlatform/django-cloud-deploy | GoogleCloudPlatform/django-cloud-deploy: Easier deployment of Django applications in the cloud.
https://github.com/GoogleCloudPlatform/python-docs-samples | GoogleCloudPlatform/python-docs-samples: Code samples used on cloud.google.com

https://twitter.com/glasnt/status/1208096663887216641 | Katie McLaughlin ✨ on Twitter: "@jacobian Yes, just to avoid raw secrets. Berglas is a helper/wrapper for Cloud KMS" / Twitter

https://github.com/Miserlou/lambda-packages | Miserlou/lambda-packages: Various popular python libraries, pre-compiled to be compatible with AWS Lambda
https://github.com/Miserlou/zappa-django-utils | Miserlou/zappa-django-utils: A handy Django application to supercharge your Zappa deployments.

https://blog.zappa.io/posts/s3sqlite-a-serverless-relational-database

https://serverless.com
https://github.com/serverless/site
https://github.com/serverless/examples | serverless/examples: Serverless Examples – A collection of boilerplates and examples of serverless architectures built with the Serverless Framework and AWS Lambda

https://aws.amazon.com/step-functions/ | AWS Step Functions – Coordinate Microservices using Visual Workflows
http://docs.aws.amazon.com/lambda/latest/dg/concurrent-executions.html | Lambda Function Concurrent Executions - AWS Lambda
https://cloud.google.com/functions/docs/ | Google Cloud Functions Documentation  |  Cloud Functions  |  Google Cloud Platform
    
https://github.com/awslabs/chalice
https://github.com/apex/apex
https://github.com/apex/up | apex/up: Deploy infinitely scalable serverless apps, apis, and sites in seconds.
-->

## Automation

Terraform
* [Terraform](https://www.terraform.io) and [Terraform Module Registry](https://registry.terraform.io)

Python- Fabric
* [Fabric](http://www.fabfile.org), [Fabric PyPi](https://pypi.python.org/pypi/Fabric), and [Fabric GitHub](https://github.com/fabric/fabric) 

<!--
salt, ansible

http://docs.fabfile.org/en/1.13/api/contrib/django.html

https://www.digitalocean.com/community/tutorials/how-to-use-fabric-to-automate-administration-tasks-and-deployments
-->

## Security Model

Security- General
* [Security- Computer Security Wikipedia](https://en.wikipedia.org/wiki/Security#Computer_security)
* [Computer Security Wikipedia](https://en.wikipedia.org/wiki/Computer_security)
* [Information Security Wikipedia](https://en.wikipedia.org/wiki/Information_security)
* [Threat Model Wikipedia](https://en.wikipedia.org/wiki/Threat_model)
* [Penetration Test Wikipedia](https://en.wikipedia.org/wiki/Penetration_test)

Computer Security Model
* [Computer Security Model Wikipedia](https://en.wikipedia.org/wiki/Computer_security_model)

Types
* [Same Origin Policy Wikipedia](https://en.wikipedia.org/wiki/Same-origin_policy)
* [Content Security Policy Wikipedia](https://en.wikipedia.org/wiki/Content_Security_Policy)

High Risk
* [Arbitrary Code Execution Wikipedia](https://en.wikipedia.org/wiki/Arbitrary_code_execution)
* [SQL Injection Wikipedia](https://en.wikipedia.org/wiki/SQL_injection)

Medium Risk
* [Cross-Site Scripting Wikipedia](https://en.wikipedia.org/wiki/Cross-site_scripting)
* [Cross-Site Request Forgery Wikipedia](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
* [Denial of Service Attack Wikipedia](https://en.wikipedia.org/wiki/Denial-of-service_attack)

<!--
Medium
Broken authentication

Low
Sensitive data exposure
Broken session management
Unvalidated redirects/forwards
Issues requiring an uncommon configuration option

https://en.wikipedia.org/wiki/Clickjacking
https://en.wikipedia.org/wiki/Code_injection

https://en.wikipedia.org/wiki/Fully_qualified_domain_name | Fully qualified domain name - Wikipedia
-->

## OWASP

OWASP
* [OWASP](https://www.owasp.org/index.php/Main_Page) and [OWASP GitHub](https://github.com/OWASP)
* [OWASP Cheat Sheet Series](https://www.owasp.org/index.php/OWASP_Cheat_Sheet_Series) and [OWASP Cheat Sheet Series GitHub](https://github.com/OWASP/CheatSheetSeries)

Top Ten
* [OWASP Top Ten Cheat Sheet GitHub](https://github.com/OWASP/Top10)

<!--
https://teamtreehouse.com/library/owasp-top-10-vulnerabilities | OWASP Top 10 Vulnerabilities Course

API
https://github.com/OAI/OpenAPI-Specification
https://github.com/OWASP/API-Security

Application Security Verification Standard
https://github.com/OWASP/ASVS/tree/master/4.0/en | ASVS/4.0/en at master · OWASP/ASVS

Software Assurance Maturity Model
https://www.owasp.org/index.php/OWASP_SAMM_Project | OWASP SAMM Project - OWASP

https://www.owasp.org/index.php/Category:Attack
   
https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project | Category:OWASP Top Ten Project - OWASP
https://www.owasp.org/index.php/Top_10-2017_Top_10 | Top 10-2017 Top 10 - OWASP
https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf | OWASP Top 10 - 2017

https://www.owasp.org/index.php/OWASP_Testing_Guide_v4_Table_of_Contents | OWASP Testing Guide v4 Table of Contents - OWASP

https://www.owasp.org/index.php/Application_Threat_Modeling | Application Threat Modeling - OWASP

https://www.owasp.org/index.php/SQL_Injection
https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF) | Cross-Site Request Forgery (CSRF) - OWASP
https://www.owasp.org/index.php/Denial_of_Service
https://www.owasp.org/index.php/HttpOnly | HttpOnly - OWASP

Prevention
https://www.owasp.org/index.php/Injection_Prevention_Cheat_Sheet | Injection Prevention Cheat Sheet - OWASP
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)_Prevention_Cheat_Sheet | Cross-Site Request Forgery (CSRF) Prevention Cheat Sheet - OWASP

JavaScript
https://www.owasp.org/index.php/3rd_Party_Javascript_Management_Cheat_Sheet
https://www.owasp.org/index.php/AJAX_Security_Cheat_Sheet

https://www.owasp.org/index.php/OWASP_Serverless_Top_10_Project | OWASP Serverless Top 10 Project - OWASP
https://github.com/OWASP/DVSA | OWASP/DVSA: a Damn Vulnerable Serverless Application
-->

## Security- Google and Mozilla

Same Origin
* [Same-Origin Policy](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy)
* [Google HTTP Access Control (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)

Content Security Policy (CSP)
* [Google Content Security Policy (CSP)](https://developers.google.com/web/fundamentals/security/csp) and [Mozilla Content Security Policy (CSP)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)

Mixed Content
* [Google What Is Mixed Content?](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/what-is-mixed-content) and [Google Preventing Mixed Content](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/fixing-mixed-content)


<!--
## Security

[Using CORS](https://www.html5rocks.com/en/tutorials/cors/)

https://developers.google.com/web/fundamentals/security/

https://www.nist.gov/blogs/cybersecurity-insights/threat-models-differential-privacy | Threat Models for Differential Privacy | NIST
https://www.ncsc.gov.uk/whitepaper/security-architecture-anti-patterns | National Cyber Security Centre

GitHub
https://github.blog/2020-09-02-how-we-threat-model/
https://github.blog/2020-09-02-secure-your-software-supply-chain-and-protect-against-supply-chain-threats-github-blog/ | Secure at every step: What is software supply chain security and why does it matter? - The GitHub Blog

Threat Modelling
https://twitter.com/jeremyphoward/status/1097602570057482240 | Jeremy Howard on Twitter: "Great list of threat modeling experts compiled in this thread - have a look at their work and follow them if you're interested in the issues stemming from the @openai language model project. Would be great to have similar lists for medical, nuclear, etc research issues!… https://t.co/Xu6cDKyHm5"

https://github.com/magoo/minimalist-risk-management

Hacking
https://samsclass.info/123/123_F18.shtml | CNIT 123: Ethical Hacking and Network Defense -- Sam Bowne
https://samsclass.info/ | samsclass.info: Sam Bowne Class Information

Checklist
https://securitycheckli.st/ | Security Checklist
https://github.com/brianlovin/security-checklist | brianlovin/security-checklist: A checklist for staying safe on the internet
Dark PDF and light PDF

https://github.com/jacobian/infosec-engineering | jacobian/infosec-engineering: A reading list for infosec engineers
https://github.com/guardrailsio/awesome-python-security | guardrailsio/awesome-python-security: Awesome Python Security resources 🕶🐍🔐
https://github.com/drduh/macOS-Security-and-Privacy-Guide | drduh/macOS-Security-and-Privacy-Guide: A practical guide to securing macOS.

GitHub
https://www.shhgit.com/ | shhgit: find secrets in real time across GitHub, GitLab and BitBucket
https://twitter.com/wsv3000/status/1317267405106708480 | William Vincent on Twitter: "https://t.co/VY3NPtAdJV This website is amazing and scary." / Twitter

https://docs.npmjs.com/getting-started/running-a-security-audit
https://www.pagerduty.com/blog/security-training-at-pagerduty/

Pen testing 
https://imgur.com/Mr9pvq9 | Imgur: The magic of the Internet

Snyk
https://snyk.io/ | Open Source Security Platform | Snyk
https://snyk.io/blog/python-security-best-practices-cheat-sheet | Python Security Best Practices Cheat Sheet | Snyk
-->
