# Tools- Python and Django Testing and Profiling

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


## Big O Notation

* [Big O Cheat Sheet](http://www.bigocheatsheet.com)

## Django Performance, Optimization, Deployment

Django Performance and Optimization
* [Django Performance](https://docs.djangoproject.com/en/dev/topics/performance)
* [Django Database Access Optimization](https://docs.djangoproject.com/en/dev/topics/db/optimization)

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

<!--
https://testautomationu.applitools.com/ | Test Automation University | Applitools
https://testautomationu.applitools.com/unit-testing/ | Overview
https://testautomationu.applitools.com/python-tutorial/
https://testautomationu.applitools.com/learningpaths.html?id=web-ui-python-path
https://testautomationu.applitools.com/selenium-webdriver-python-tutorial/ | Selenium WebDriver with Python

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

https://testdriven.io/ | Test Driven Development Courses

Brian Okken
http://pythontesting.net/start-here/
-->


<!--
Assert

https://docs.python.org/3/reference/simple_stmts.html#the-assert-statement
-->

### Django Testing

Django Testing- Official
* [Django Testing Overview](https://docs.djangoproject.com/en/dev/topics/testing/overview)
* [Django Testing](https://docs.djangoproject.com/en/dev/topics/testing)
* [Django Testing Tools](https://docs.djangoproject.com/en/dev/topics/testing/tools)
* [Django Testing Advanced Topics](https://docs.djangoproject.com/en/dev/topics/testing/advanced)

<!--
https://docs.djangoproject.com/en/3.0/topics/testing/advanced/#using-different-testing-frameworks | Advanced testing topics | Django documentation | Django
https://docs.djangoproject.com/en/2.2/topics/testing/tools/#testcase | Testing tools | Django documentation | Django
https://docs.python.org/3/library/unittest.html#unittest.TestCase | unittest — Unit testing framework — Python 3.8.1 documentation

https://docs.python.org/3/library/unittest.html#assert-methods
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertEqual | unittest — Unit testing framework — Python 3.8.1 documentation
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertNotEqual
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertRaises

https://docs.djangoproject.com/en/2.2/topics/testing/tools/#django.test.TransactionTestCase | Testing tools | Django documentation | Django
https://docs.djangoproject.com/en/3.0/topics/checks/ | System check framework | Django documentation | Django


https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript/#javascript-tests | JavaScript | Django documentation | Django
-->

## Python Testing

Python Testing Built-In Tools
* [unittest](https://docs.python.org/3/library/unittest.html)
* [unittest.mock](https://docs.python.org/3/library/unittest.mock.html)


Python Debugger
* [bdb](https://docs.python.org/3/library/bdb.html)
* [pdb](https://docs.python.org/3/library/pdb.html)

doctest
* [doctest](https://docs.python.org/3/library/doctest.html)

## pytest

pytest 
* [pytest](http://pytest.org) and [pytest Docs](https://docs.pytest.org/en/latest)

<!--
https://github.com/pytest-dev/pytest | pytest-dev/pytest: The pytest framework makes it easy to write small tests, yet scales to support complex functional testing


https://github.com/seleniumbase/SeleniumBase | seleniumbase/SeleniumBase: ✅ Automate & test 10x faster with Selenium & pytest. Batteries included.

https://pytest-selenium.readthedocs.io/en/latest/user_guide.html

Flask
https://github.com/pytest-dev/pytest-flask | pytest-dev/pytest-flask: A set of pytest fixtures to test Flask applications


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

## Django Testing

Django
* [pytest-django PyPi](https://pypi.python.org/pypi/pytest-django) and [pytest-django Read the Docs](http://pytest-django.readthedocs.org)

Django Test Plus
* [Django Test Plus](http://django-test-plus.readthedocs.io) and [Django Test Plus GitHub](https://github.com/revsys/django-test-plus)

<!--
https://pytest-django.readthedocs.io/en/latest/database.html | Database creation/re-use — pytest-django documentation

https://readthedocs.org/projects/pytest-django/downloads/pdf/latest/

Important
https://django-test-plus.readthedocs.io/en/latest/usage.html | Usage — django-test-plus 1.0.9 documentation

https://www.revsys.com/tidbits/pytest-support-django-test-plus/ | pytest support for django-test-plus

pytest Books
https://automationpanda.com/2018/09/17/book-review-python-testing-with-pytest/ | Book Review: Python Testing with pytest | Automation Panda
https://www.packtpub.com/web-development/pytest-quick-start-guide
https://pragprog.com/book/bopytest/python-testing-with-pytest | Python Testing with pytest: Simple, Rapid, Effective, and Scalable by Brian Okken | The Pragmatic Bookshelf

https://github.com/augustogoulart/awesome-pytest | augustogoulart/awesome-pytest: A curated list of awesome pytest resources

Test Anything Protocol
https://en.wikipedia.org/wiki/Test_Anything_Protocol
https://twitter.com/mblayman/status/1222200715570970624 | Matt Layman on Twitter: "I released a new version of pytest-tap today that let's you use the Test Anything Protocol (TAP) for #pytest. This version drops support for Python 2. https://t.co/Mm7fKz0Gfg" / Twitter
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
