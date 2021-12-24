# Python and Django Tools and Deployment

<!--
## Anthony

pre-commit
https://pre-commit.ci/
https://github.com/pre-commit/pre-commit/

https://github.com/asottile/all-repos | asottile/all-repos: Clone all your repositories and apply sweeping changes.	
https://adamj.eu/tech/2020/04/02/maintaining-multiple-python-projects-with-myrepos/ | Maintaining Multiple Python Projects With myrepos - Adam Johnson


Pyenv Global
https://twitter.com/webology/status/699277088256163840

Important!
https://pyphilly.org/virtualenvwrapper-aliases-venv-users/
https://twitter.com/DawnWagesSays/status/1429843476447830016 | dawn (she/her) on Twitter: "Imma be real, I’ve been trying to phase pipenv out but I like it. Thanks to @FlipperPA , when I venv I use it like dis: https://t.co/w2OQvj1WIc" / Twitter


## Dict View

https://johnlekberg.com/blog/2020-09-19-dict-view.html | Dictionary view objects in Python

https://twitter.com/llanga/status/999318672098320384 | Łukasz Langa on Twitter: "i'm surprised dict views aren't more popular. Real world example: https://t.co/sOVvUgeJRc I think this is really elegant. For explanation read below.… https://t.co/kqXSQajFZr"


## Choices

Vinta Django Apps Checklist	
* [Vinta Django Apps Checklist](https://devchecklists.com/django-apps-checklist)	

Vinta API Checklist	
* [Vinta API Checklist](https://devchecklists.com/python-api-checklist) and [Vinta API Checklist GitHub](https://github.com/vintasoftware/python-api-checklist)

https://github.com/vintasoftware/python-api-checklist/blob/master/checklist-en.md | python-api-checklist/checklist-en.md at master · vintasoftware/python-api-checklist

https://devchecklists.com
https://devchecklists.com/django-production-launch/
https://devchecklists.com/vintas-high-quality-standards/

Check if you need a Django app or a regular Python package: Django apps need to be added to INSTALLED_APPS . Regular Python packages do not. Examples of regular Python packages:

## Eric

https://twitter.com/ehmatthes/status/1466539581436616704 | Eric Matthes on Twitter: "This is a milestone I've been looking forward to sharing. django-simple-deploy has preliminary support for Azure, which means you can deploy to Heroku or Azure with the same three steps: https://t.co/LMwY1VFaEB https://t.co/xVSFP7AK2l" / Twitter

https://ehmatthes.com/blog/simplified_heroku/ | Simplifying Django deployments on Heroku - ehmatthes.com
https://twitter.com/ehmatthes/status/1452366374353833985 | Eric Matthes on Twitter: "I've been on a years-long quest to help simplify Django deployment for small projects. I just made an app that does all of the configuration work for an initial deployment to Heroku: https://t.co/mqlrcDAbqt" / Twitter
https://github.com/ehmatthes/django-simple-deploy | ehmatthes/django-simple-deploy: A reusable Django app that configures your project for deployment
https://github.com/ehmatthes/heroku-buildpack-python | ehmatthes/heroku-buildpack-python: A demonstration version of the official Heroku buildpack for Python apps, showing how Django deployment can be further simplified.
https://twitter.com/ehmatthes/status/1454839778587725841 | Eric Matthes on Twitter: "django-simple-deploy now supports projects that use Poetry. Next I'm going to try adding an `--automate-all` flag that should reduce the entire process to three steps. Then, if possible, I'll add support for at least one other platform." / Twitter

Deployment 
Django SaaS Starter Kit
https://twitter.com/carltongibson/status/1337087410203717636 | https://twitter.com/carltongibson/status/1337087410203717636
https://docs.saaspegasus.com/
https://www.saaspegasus.com/

https://twitter.com/webology/status/1402643938842980355 | ✨ Jeff Triplett ✨ on Twitter: "If you are overwhelmed in how to deploy your Django project, please consider reaching out to @KimStacks who is working on trying to fix that. He is a solo-maker who's trying to solve this problem using your existing infrastructure (no lock-in) and is just looking for feedback." / Twitter
-->

## Awesome Python and Django

Awesome Python
* [Awesome Python GitHub](https://github.com/vinta/awesome-python) and [Awesome Python](http://awesome-python.com)
* [Awesome Pythonidae GitHub](https://github.com/svaksha/pythonidae)  
* [Awesome Pycrumbs GitHub](https://github.com/kirang89/pycrumbs)  

Awesome Django
* [Awesome Django](https://github.com/wsvincent/awesome-django)
* [Awesome Django GitLab](https://gitlab.com/rosarior/awesome-django) and [Awesome Django GitHub (Deprecated)](https://github.com/rosarior/awesome-django) 
* [Awesome Django Admin GitHub](https://github.com/originalankur/awesome-django-admin)
* [Awesome Django Rest Framework GitHub](https://github.com/nioperas06/awesome-django-rest-framework)

## Python and Django

Python
* [Python](https://www.python.org/)

Django GitHub
* [Django GitHub](https://github.com/django/django)

<!--
https://plone.org/
-->

## General Python and Django Links- Getting Started

Python Official Tutorial
* [Python Official Tutorial](https://docs.python.org/3/tutorial/) 

Django Tutorials (Official, Mozilla Developer Network and SIBTC) 
* [Django Official Tutorial](https://docs.djangoproject.com/en/2.0/intro/tutorial01)

Django Install
* [Django Install](https://docs.djangoproject.com/en/dev/topics/install)

## Design Choices

Django Architecture and Scaling
* [Shared-Nothing Architecture Wikipedia](https://en.wikipedia.org/wiki/Shared-nothing_architecture)
* [Does Django Scale?](https://docs.djangoproject.com/en/dev/faq/general/#does-django-scale)
* [Django Design Philosophies](https://docs.djangoproject.com/en/dev/misc/design-philosophies)


## Structuring Your Python Project

Kenneth Reitz- Sample Project Structure, Sample Module, and setup.py
* [Kenneth Reitz: Structuring Your Project](http://docs.python-guide.org/en/latest/writing/structure)
* [Sample Module for The Hitchhiker’s Guide to Python! GitHub](https://github.com/kennethreitz/samplemod) and [Sample Module Docs](https://github.com/kennethreitz/samplemod/tree/master/docs)
* [Repository Structure and Python](https://www.kennethreitz.org/essays/repository-structure-and-python)
* [A Human's Ultimate Guide to setup.py GitHub](https://github.com/kennethreitz/setup.py)

## Django Project Structure

Python- Django- Project Stucture
* [RevSys Recommended Django Project Layout](http://www.revsys.com/blog/2014/nov/21/recommended-django-project-layout)
* [SIBTC Starting a New Django 1.8 Project](http://simpleisbetterthancomplex.com/2015/11/30/starting-a-new-django-18-project.html)


## Django Deployment

Django Deployment
* [Deployment Checklist](https://docs.djangoproject.com/en/dev/howto/deployment/checklist)

## Django Performance, Optimization, Deployment

Django Performance and Optimization
* [Django Performance](https://docs.djangoproject.com/en/dev/topics/performance)
* [Django Database Access Optimization](https://docs.djangoproject.com/en/dev/topics/db/optimization)

<!--
Adam tip
-->

## Python Debugger and doctests

Python Debugger
* [bdb](https://docs.python.org/3/library/bdb.html)
* [pdb](https://docs.python.org/3/library/pdb.html)

doctest
* [doctest](https://docs.python.org/3/library/doctest.html)

<!--
https://docs.python.org/3/library/pprint.html | pprint — Data pretty printer — Python 3.9.5 documentation

ipdb
https://pypi.org/project/ipdb/ | ipdb · PyPI
-->

## Python Testing- unittest

Python Testing Built-In Tools
* [unittest](https://docs.python.org/3/library/unittest.html)
* [unittest.mock](https://docs.python.org/3/library/unittest.mock.html)

<!--
Assert
https://docs.python.org/3/reference/simple_stmts.html#the-assert-statement

https://docs.python.org/3/library/unittest.html#unittest.TestCase | unittest — Unit testing framework — Python 3.8.1 documentation

https://docs.python.org/3/library/unittest.html#assert-methods
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertEqual | unittest — Unit testing framework — Python 3.8.1 documentation
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertNotEqual
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertRaises
-->

### Django Testing, System Checks, Error Reporting, Exceptions

Django Testing- Official
* [Django Testing Overview](https://docs.djangoproject.com/en/dev/topics/testing/overview)
* [Django Testing](https://docs.djangoproject.com/en/dev/topics/testing)
* [Django Testing Tools](https://docs.djangoproject.com/en/dev/topics/testing/tools)
* [Django Testing Advanced Topics](https://docs.djangoproject.com/en/dev/topics/testing/advanced)

System Checks, Error Reporting, Exceptions
* [Django System Checks](https://docs.djangoproject.com/en/dev/topics/checks)
* [Django Error Reporting](https://docs.djangoproject.com/en/dev/howto/error-reporting)
* [Django Exceptions](https://docs.djangoproject.com/en/dev/ref/exceptions)

<!--
Django raises built-in Python exceptions when appropriate.

Exceptions
https://docs.python.org/3/library/exceptions.html#built-in-exceptions

https://docs.djangoproject.com/en/3.0/topics/testing/advanced/#using-different-testing-frameworks | Advanced testing topics | Django documentation | Django
https://docs.djangoproject.com/en/2.2/topics/testing/tools/#testcase | Testing tools | Django documentation | Django


https://docs.djangoproject.com/en/2.2/topics/testing/tools/#django.test.TransactionTestCase | Testing tools | Django documentation | Django


https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript/#javascript-tests | JavaScript | Django documentation | Django
-->

## Django Core Dev Security

* [Django Security](https://docs.djangoproject.com/en/dev/releases/security/)
* [How Django Discloses Security Issues](https://docs.djangoproject.com/en/dev/internals/security/#how-django-discloses-security-issues)

<!--
## Django Security Policy

https://docs.djangoproject.com/en/3.2/internals/security/
-->

### Django Security

* [Clickjacking Protection](https://docs.djangoproject.com/en/dev/ref/clickjacking/)
* [HTTP Strict Transport Security](https://docs.djangoproject.com/en/dev/ref/middleware/#http-strict-transport-security)
* [Security Middleware](https://docs.djangoproject.com/en/dev/ref/middleware/#django.middleware.security.SecurityMiddleware)


## Python and Django Links- Style

Python Style
* [PEP 0008 Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008) and [PEP 0008 Style Guide for Python Code .txt](https://hg.python.org/peps/file/tip/pep-0008.txt)
* [PEP 0257 Doc String Conventions](https://www.python.org/dev/peps/pep-0257)

Django Coding Style Guide
* [Django Coding Style Guide](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style)

Django JavaScript Style Guide
* [Django JavaScript Style Guide](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript)

## Python Non-Official Styleguides and Code Formatting

Style
* [Coding Conventions Wikipedia](https://en.wikipedia.org/wiki/Coding_conventions)
* [Programming Style Wikipedia](https://en.wikipedia.org/wiki/Programming_style)

Python- Kenneth Reitz Contributor's Guide and Style Guides
* [Kenneth Reitz: The Hitchhiker’s Guide to Python! Code Style](http://docs.python-guide.org/en/latest/writing/style)

Python- Style Guides
* [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)
* [Khan Academy Python Style Guide Python](https://github.com/Khan/style-guides/blob/master/style/python.md)
* [The Chromium Project Python Style Guide](https://www.chromium.org/chromium-os/python-style-guidelines)

<!--
https://docs.python-guide.org/#writing-great-python-code
-->

Python- PEP 8
* [Kenneth Reitz: PEP 8 — the Style Guide for Python](http://pep8.org) and [Kenneth Reitz: PEP 8 — the Style Guide for Python GitHub](https://github.com/kennethreitz/pep8.org)



## General Python and Django Links

Django Views
* [Class-Based Views](https://docs.djangoproject.com/en/dev/topics/class-based-views/)

Django ORM
* [Queries](https://docs.djangoproject.com/en/dev/topics/db/queries)

Django Request/Response

<!--
https://docs.djangoproject.com/en/2.2/_modules/django/http/request/ | django.http.request | Django documentation | Django

https://docs.djangoproject.com/en/dev/_modules/django/http/request/#HttpRequest
https://docs.djangoproject.com/en/dev/ref/request-response/#jsonresponse-objects

https://docs.djangoproject.com/en/2.1/ref/request-response/#django.http.HttpRequest.GET
https://docs.djangoproject.com/en/1.11/ref/request-response/#django.http.HttpRequest.POST
https://docs.djangoproject.com/en/1.11/ref/request-response/#django.http.QueryDict


https://docs.djangoproject.com/en/3.1/ref/request-response/
https://docs.djangoproject.com/en/3.1/ref/request-response/#module-django.http
https://docs.djangoproject.com/en/3.1/ref/request-response/#httprequest-objects
https://docs.djangoproject.com/en/3.1/ref/request-response/#httpresponse-objects
https://docs.djangoproject.com/en/3.1/ref/request-response/#jsonresponse-objects
-->

## Django Source

<!--
https://github.com/django/django/blob/master/django/core/handlers/base.py#L71 | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/core/handlers/base.py#L85 | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/urls/resolvers.py#L66 | django/resolvers.py at master · django/django
https://github.com/django/django/blob/master/django/template/context.py | django/context.py at master · django/django
https://github.com/django/django/blob/master/django/template/response.py | django/response.py at master · django/django
https://github.com/django/django/blob/master/django/http/__init__.py | django/__init__.py at master · django/django
https://github.com/django/django/blob/master/django/core/files/uploadhandler.py | django/uploadhandler.py at master · django/django

https://www.youtube.com/watch?v=tkwZ1jG3XgA | James Bennett - Django in Depth - PyCon 2015 - YouTube	
https://twitter.com/ubernostrum/status/1115023968925130752 | James Bennett on Twitter: "Let me know if you have questions. It's old/out-of-date, and tried to cover too much stuff (which is why I switched to doing an ORM-focused tutorial last year).… https://t.co/btm7lzK7rI"

Django Source Code
https://github.com/django/django/blob/master/django/__init__.py	
https://github.com/django/django/tree/master/django/apps	
https://github.com/django/django/blob/master/django/apps/config.py	
https://github.com/django/django/blob/master/django/apps/registry.py
https://github.com/django/django/blob/master/django/conf/__init__.py | django/__init__.py at master · django/django
https://github.com/django/django/blob/master/django/urls/conf.py	
https://github.com/django/django/blob/master/django/urls/resolvers.py
https://github.com/django/django/blob/master/django/middleware/common.py

https://github.com/django/django/blob/master/django/core/handlers/wsgi.py | django/wsgi.py at master · django/django
https://github.com/django/django/blob/master/django/http
https://github.com/django/django/blob/master/django/http/request.py | django/request.py at master · django/django	
https://github.com/django/django/blob/master/django/http/response.py	

https://github.com/django/django/blob/master/django/views/generic/__init__.py | django/__init__.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/base.py | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/base.py#L83 | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/detail.py | django/detail.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/list.py | django/list.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/list.py#L113	
	
https://github.com/django/django/blob/master/django/shortcuts.py
https://github.com/django/django/blob/master/django/core/exceptions.py	
	
https://github.com/django/django/tree/master/django/db/backends | django/django/db/backends at master · django/django	
https://github.com/django/django/blob/master/django/db/models/__init__.py 	
https://github.com/django/django/blob/master/django/db/models/query.py	
https://github.com/django/django/blob/master/django/db/models/query.py#L337	
https://github.com/django/django/blob/master/django/contrib/auth/base_user.py | 	
https://github.com/django/django/blob/master/django/db/models/lookups.py
-->

## Django Serialization

Python- Django- Rest Framework (Serialization/Deserialization)
* [Django Rest Framework: Tutorial 1: Serialization](http://www.django-rest-framework.org/tutorial/1-serialization)
* [Serializing Django objects](https://docs.djangoproject.com/en/dev/topics/serialization)
* [JSON](https://docs.djangoproject.com/en/dev/topics/serialization/#serialization-formats-json)

## Django Internationalization and Localization, Translation

* [Django i18n Forum](https://groups.google.com/forum/#!forum/django-i18n)  
* [Python Gettext Multilingual Internationalization Services](https://docs.python.org/2/library/gettext.html)  
* [Django Local Flavor](https://docs.djangoproject.com/en/dev/topics/localflavor)  
* [Django Local Flavor Read the Docs](https://django-localflavor.readthedocs.org/en/latest)  
* [Django Local Flavor GitHub](https://github.com/django/django-localflavor)  
* [Django Local Flavor PyPi](https://pypi.python.org/pypi/django-localflavor)  
* [Django Internationalization and Localization](https://docs.djangoproject.com/en/dev/topics/i18n)  
* [Django Internationalization and Localization, Translation](https://docs.djangoproject.com/en/dev/topics/i18n/translation) 

<!--
https://github.com/django/django-formtools
https://github.com/django/django-contrib-comments
-->

## Python and Django Geo

GeoDjango
* [GeoDjango](http://geodjango.org)  
* [GeoDjango Installation Postgresapp](https://docs.djangoproject.com/en/1.9/ref/contrib/gis/install/#postgresapp)

Python- Django- Rest Framework GIS
* [Django Rest Framework GIS API Guide Fields](http://www.django-rest-framework.org/api-guide/fields/#django-rest-framework-gis)  
* [Django Rest Framework GIS GitHub](https://github.com/djangonauts/django-rest-framework-gis)  
* [Django Rest Framework GIS PyPi](https://pypi.python.org/pypi/djangorestframework-gis)  
* [Django Rest Framework GIS Forum](https://groups.google.com/forum/#!forum/django-rest-framework-gis)  

PostGIS (Spatial Database Extender for PostgreSQL)
* [PostGIS](http://postgis.net)  
* [PostGIS Wikipedia](http://en.wikipedia.org/wiki/PostGIS)  
* [UbuntuGIS](https://wiki.ubuntu.com/UbuntuGIS)  
* [UbuntuGIS Wiki](http://trac.osgeo.org/ubuntugis/wiki)  
* [Heroku PostGIS Wiki](https://devcenter.heroku.com/articles/postgis)  

SpatiaLite (Spatial Database Extender for SQLite)
* [SpatiaLite](https://www.gaia-gis.it/fossil/libspatialite/index)  
* [SpatiaLite Downloads Page](http://www.gaia-gis.it/gaia-sins/libspatialite-sources)  
* [SpatiaLite Wikipedia](http://en.wikipedia.org/wiki/SpatiaLite)  

<!--
GIS

Important
https://simonwillison.net/2021/May/3/adding-geodjango-to-an-existing-django-project/ | Adding GeoDjango to an existing Django project

https://realpython.com/location-based-app-with-geodjango-tutorial/ | Make a Location-Based Web App With Django and GeoDjango – Real Python
https://en.wikipedia.org/wiki/Spatial_database | Spatial database - Wikipedia

https://postgis.net/docs/manual-3.0/
https://postgis.net/docs/manual-3.0/ch06.html
https://www.gaia-gis.it/fossil/libspatialite/index

GIS
https://docs.djangoproject.com/en/3.2/ref/contrib/gis/ | GeoDjango | Django documentation | Django
https://docs.djangoproject.com/en/3.2/ref/contrib/gis/tutorial/ | GeoDjango Tutorial | Django documentation | Django
-->


## Django Rest Framework

Python- Django- Rest Framework (Including Authentication and Generic Views)
* [Django Rest Framework](http://www.django-rest-framework.org) and [Django Rest Framework GitHub](https://github.com/encode/django-rest-framework) 
* [Django Rest Framework Generic Views](http://www.django-rest-framework.org/api-guide/generic-views)  
* [Django Rest Framework Authentication](http://www.django-rest-framework.org/api-guide/authentication)  

<!--
DRF
https://twitter.com/nextdayvideo/status/1363639281726623745 | Next Day Video on Twitter: "#pycascades What You Should Know About Django REST Framework - Lacey Williams Henschel https://t.co/E9pg9roNoL" / Twitter
https://speakerdeck.com/williln/what-you-should-know-about-django-rest-framework | What You Should Know About Django REST Framework - Speaker Deck
https://www.laceyhenschel.com/blog/2021/2/23/what-you-should-know-about-drf-part-2-customizing-built-in-methods | What You Should Know About DRF, Part 2: Customizing built-in methods — Lacey Williams Henschel
https://www.laceyhenschel.com/blog/2021/2/23/what-you-should-know-about-django-rest-framework-part-3-adding-custom-endpoints | What You Should Know About DRF, Part 3: Adding custom endpoints — Lacey Williams Henschel

https://www.django-rest-framework.org/tutorial/3-class-based-views/ | 3 - Class based views - Django REST framework
https://www.django-rest-framework.org/api-guide/serializers/ | Serializers - Django REST framework
https://www.django-rest-framework.org/api-guide/viewsets/#modelviewset
https://www.django-rest-framework.org/api-guide/serializers/#modelserializer

https://github.com/encode/django-rest-framework/

https://github.com/encode/django-rest-framework/issues
https://github.com/encode/django-rest-framework/projects

https://github.com/encode/rest-framework-tutorial | encode/rest-framework-tutorial
http://www.tomchristie.com/rest-framework-2-docs/api-guide
https://www.django-rest-framework.org/tutorial/1-serialization/ | 1 - Serialization - Django REST framework

https://github.com/carltongibson/rest-framework-tutorial | carltongibson/rest-framework-tutorial
https://github.com/carltongibson/rest-framework-tutorial/blob/master/docs/azure/1-vscode.md | rest-framework-tutorial/1-vscode.md at master · carltongibson/rest-framework-tutorial
https://github.com/carltongibson/rest-framework-tutorial/blob/master/docs/azure/2-appservice.md | rest-framework-tutorial/2-appservice.md at master · carltongibson/rest-framework-tutorial

https://twitter.com/carltongibson/status/1072951282502172678 | Carlton Gibson on Twitter: "Been having fun with @code for about a year and a half. I got together with @nnja to talk about using it with Django and DRF…… https://t.co/XmFcENotrc"
https://www.youtube.com/watch?list=PLlrxD0HtieHjQMK-jWHRy3aHGLhbAFqbR&time_continue=10&v=0Bk0dw2Ktbg | Python on Azure: Part 1—Building Django apps with Visual Studio Code | Azure Friday - YouTube
https://www.youtube.com/watch?list=PLlrxD0HtieHjQMK-jWHRy3aHGLhbAFqbR&v=FHJvsvbD_cQ | Python on Azure: Part 2—Deploying Django services to Azure Web Apps | Azure Friday - YouTube
-->

<!--
## DRF

DRF Example
* https://github.com/simplworld/simpl-games-api/blob/master/simpl/webhook/serializers.py

https://www.django-rest-framework.org/community/3.10-announcement/ | 3.10 Announcement - Django REST framework

DRF Resources
* https://realpython.com/django-rest-framework-quick-start/ | Django Rest Framework – An Introduction – Real Python
* https://www.django-rest-framework.org/tutorial/quickstart/ | Quickstart - Django REST framework
* https://www.django-rest-framework.org/#example | Home - Django REST framework

https://www.django-rest-framework.org/api-guide/testing/ | Testing - Django REST framework

https://www.django-rest-framework.org/api-guide/status-codes/ | Status codes - Django REST framework

Valentino
https://www.valentinog.com/blog/testing-django/ | Django Testing Cheat Sheet
https://www.valentinog.com/blog/drf/ | Tutorial: Django REST with React (and a sprinkle of testing)
https://github.com/valentinogagliardi/django-rest-react-pycon
-->

## Django Rest Framework- Extras

* [Django Rest Framework Swagger](https://github.com/marcgibbons/django-rest-swagger) 

Python- Django- Alternative Rest Framework
* [django-tastypie Read the Docs](http://django-tastypie.readthedocs.org)

<!--
https://swagger.io/docs/

https://github.com/caktus/drf-sample | caktus/drf-sample: Django REST Framework Sample
https://github.com/vintasoftware/drf-rw-serializers/

https://wsvincent.com/django-rest-framework-tutorial/ | Django Rest Framework - Blog API - William S. Vincent
https://github.com/wsvincent/rest-framework-tutorial
-->


## Django Classy

Django Classy
* [Classy Class-Based Views](http://ccbv.co.uk)
* [Classy Django Forms](http://cdf.9vo.lt) and [Classy Django Forms GitHub](https://github.com/ana-balica/classy-django-forms)
* [Classy Django REST Framework](http://cdrf.co) and [Classy Django REST Framework GitHub](https://github.com/vintasoftware/classy-django-rest-framework)


## Docs

<!--
https://swagger.io/ | API Documentation & Design Tools for Teams | Swagger

Django YAML
https://django-yamlfield.readthedocs.io/en/latest/ | django-yamlfield
https://github.com/datadesk/django-yamlfield | datadesk/django-yamlfield: A Django database field for storing YAML data

Docs
https://docutils.sourceforge.io/rst.html | reStructuredText
https://pandoc.org/

https://twitter.com/pradyunsg/status/1462521987994112002 | Pradyun Gedam on Twitter: "Oops. I'm working on a second Sphinx theme." / Twitter

Furo Theme
https://twitter.com/AdamChainz/status/1432678359276863494 | Adam Johnson on Twitter: "Just moved the Django-MySQL docs to @pradyunsg 's excellent Furo theme 😎 https://t.co/ippjR6VV4b" / Twitter
https://django-mysql.readthedocs.io/en/latest/ | Django-MySQL 4.0.0 documentation

https://twitter.com/osdotsystem/status/1462678399252451328 | Abdur-Rahmaan 🇲🇺 Janhangeer on Twitter: "Unfortunately, @pradyunsg 's Furo is the ONLY theme i found great in the whole sphinx universe. Hope it will be another gem!" / Twitter
-->


## Django Third Party Tools

### Local

<!--
https://pyphilly.org/virtualenvwrapper-aliases-venv-users/ | virtualenvwrapper Aliases for venv Users - PyPhilly: Home of Tim Allen, aka FlipperPA

Recommended by Jeff
https://github.com/direnv
https://direnv.net/ | direnv – unclutter your .profile | direnv

Recommended: pip-tools
https://github.com/jazzband/pip-tools | jazzband/pip-tools: A set of tools to keep your pinned Python dependencies fresh.
https://lincolnloop.com/blog/python-dependency-locking-pip-tools/ | Python Dependency Locking with pip-tools | Lincoln Loop
-->

### Debugging

<!--
IPDB

https://github.com/jazzband/django-debug-toolbar

Simon
https://twitter.com/simonw/status/1321612923442098177 | (26) Simon Willison on Twitter: "Just found out Jupyter is available via Homebrew: brew install jupyter I wonder if this could be a good recommended starting point for newcomers to Python? You can pip install packages for it in the right place directly in a cell using: %pip install httpx" / Twitter

https://ipython.org/ | Jupyter and the future of IPython — IPython

Django Shell Plus
https://django-extensions.readthedocs.io/en/latest/shell_plus.html | shell_plus — django-extensions 3.0.8 documentation
https://github.com/django-extensions/django-extensions | django-extensions/django-extensions: This is a repository for collecting global custom management extensions for the Django Framework.
-->

### Templates

<!--
HTMX + Django
https://twitter.com/htmx_org/status/1432498119464259585 | htmx.org on Twitter: "what's really satisfying about this is how htmx + django allows developers to a ditch complicated server side tool in favor of small, properly factored snippets of HTML templates simpler, more dynamic *and* more flexible what's not to like? 🍻 @justdjangocode" / Twitter

Django Tool
https://github.com/rtts/djhtml | rtts/djhtml: Django/Jinja template indenter

https://github.com/Riverside-Healthcare/djlint | Riverside-Healthcare/djLint: HTML Template Linter and Formatter. Use with Django, Jinja, Nunjucks and Handlebars templates.
-->

### CI/CD

<!--
https://pypi.org/project/coverage/ | coverage · PyPI
https://devguide.python.org/coverage/ | 5. Increase Test Coverage — Python Developer's Guide
-->




<!--
https://www.attrs.org/en/stable/

## Common Django Features

http://django-vanilla-views.org/ | Django Vanilla Views - Beautifully simple class based views
https://github.com/tomchristie/django-vanilla-views | tomchristie/django-vanilla-views: Beautifully simple class-based views.

http://www.discoversdk.com/blog/understanding-the-request-response-lifecycle-of-a-django-web-application | Understanding the request-response lifecycle of a Django web application | DiscoverSDK Blog

Django Request and Response Cycle
* [Django Request and Response Cycle](http://rnevius.github.io/django_request_response_cycle.png)


## F-Strings

https://speakerdeck.com/mariatta/f-strings | F-strings - Speaker Deck
https://www.pydanny.com/python-f-strings-are-fun.html | Python F-Strings Are Fun!

## Feature Flags

https://github.com/cfpb/wagtail-flags | GitHub - cfpb/wagtail-flags: Feature flags for Wagtail sites
https://github.com/cfpb/django-flags/ | cfpb/django-flags: Feature flags for Django projects

https://bullet-train.io/ | Bullet Train - Feature Flags, Feature Toggles and Remote Config - Ship features with confidence
https://github.com/search?q=django+feature+flags | Search · django feature flags
https://github.com/django-waffle/django-waffle | django-waffle/django-waffle: A feature flipper for Django
https://github.com/disqus/gargoyle | disqus/gargoyle: Feature switches in Django


django_deprecate_fields
https://twitter.com/lalongueduree/status/1418518067294900226 | Jeremy Gibson on Twitter: "If you haven't read a piece yet by my colleague @danpoirier, you really should especially if you develop with #Django. This one... django_deprecate_fields... 🤯 Truly a "I can't believe I haven't been using this before" moment. https://t.co/ArgrMXl8CK" / Twitter
https://twitter.com/CaktusGroup/status/1418316667776606215 | Caktus Group on Twitter: "By using django-add-default-value and django-deprecate-fields to simplify the migration and deployment process, you will eliminate a common #Django #deployment headache. This has been a challenge for a while now. https://t.co/Fi0j51BmmX" / Twitter

django-lifecycle
https://github.com/rsinger86/django-lifecycle/ | rsinger86/django-lifecycle: Declarative model lifecycle hooks, an alternative to Signals.
https://twitter.com/webology/status/1291058206056251393 | Jeff says, "wear a mask" 😷 on Twitter: "@andrewgodwin @carltongibson If you want to see something that's both different and lifted from Rails, check out https://t.co/nvQXTiFIkw I can't unsee them after using them in a few projects." / Twitter
https://twitter.com/carltongibson/status/1279334203457523713 | Carlton Gibson 🇪🇺 on Twitter: "Folks still using django-lifecycle? What are the thoughts Some Time Later?" / Twitter

django-allauth
https://github.com/pennersr/django-allauth | pennersr/django-allauth: Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party (social) account authentication.
https://pyphilly.org/know-thy-user-custom-user-models-django-allauth/
https://twitter.com/FlipperPA/status/1317214250193031168 | Tim A. on Twitter: "@pystar As promised, here's a blog post: https://t.co/M4I1ktg5P3" / Twitter


Django filter
https://github.com/carltongibson/django-filter | carltongibson/django-filter: A generic system for filtering Django QuerySets based on user selections
https://django-filter.readthedocs.io/en/
https://pypi.org/project/django-filter/ | django-filter · PyPI
https://pypi.org/project/djangorestframework-filters/ | djangorestframework-filters · PyPI
https://www.django-rest-framework.org/api-guide/filtering/ | Filtering - Django REST framework
https://github.com/philipn/django-rest-framework-filters | philipn/django-rest-framework-filters: Better filtering for Django REST Framework

Django Crispy Forms
http://django-crispy-forms.readthedocs.io/en/latest/ | Forms have never been this crispy — django-crispy-forms 1.0.0 documentation
https://pypi.org/project/django-crispy-forms/ | django-crispy-forms · PyPI
https://github.com/django-crispy-forms/django-crispy-forms | django-crispy-forms/django-crispy-forms: The best way to have DRY Django forms. The app provides a tag and filter that lets you quickly render forms in a div format while providing an enormous amount of capability to configure and control the rendered HTML.

https://pypi.org/project/django-countries/ | django-countries · PyPI
https://github.com/SmileyChris/django-countries#countryfield | SmileyChris/django-countries: A Django application that provides country choices for use with forms, flag icons static files, and a country field for models.


Django cities
https://github.com/coderholic/django-cities | coderholic/django-cities: Countries and cities of the world for Django projects


Model History
https://django-simple-history.readthedocs.io/en/latest/quick_start.html | Quick Start — django-simple-history 3.0.0.post23+ga63eec8 documentation
-->



## Django Performance, Optimization, Deployment, Architecture

<!--
https://djangobook.com/deploying-django/
-->

## Django Twelve Factor

<!--
https://12factor.net/config | The Twelve-Factor App
https://github.com/doismellburning/django12factor | doismellburning/django12factor: Making Django configuration more 12factor-y

Tool
https://django12factor.readthedocs.io/en/latest/
-->


## Wagtail

Wagtail
* [Wagtail](https://wagtail.io/)

<!--
Django Wagtail
https://github.com/Jean-Zombie/cookiecutter-django-wagtail | Jean-Zombie/cookiecutter-django-wagtail: Cookiecutter Django + Wagtail

Wagtail
https://wagtail.io/blog
https://github.com/wagtail/wagtail/
https://wagtail.io/packages/ | Packages | Wagtail CMS
https://wagtail.io/blog/wagtail-packages/ | Wagtail Packages | Wagtail CMS
https://github.com/vsalvino/wagtail-tutorial | vsalvino/wagtail-tutorial: Build your first simple wagtail website!
https://github.com/coderedcorp/coderedcms | coderedcorp/coderedcms: A content management system for marketing websites based on Django and Wagtail.
-->

## Eldarion and Pinax

Package Tools
* [django-appconf Read the Docs](https://django-appconf.readthedocs.io) and [django-appconf PyPI](https://pypi.org/project/django-appconf)

<!--
https://github.com/django-compressor/django-appconf | django-compressor/django-appconf: An app to handle configuration defaults of packaged Django apps gracefully
-->

Continuous Integration and Delivery
* [CircleCI](https://circleci.com)

Coverage
* [Coverage Read the Docs](http://coverage.readthedocs.org) and [Coverage Bitbucket](https://bitbucket.org/ned/coveragepy)
* [Codecov](https://codecov.io)

Testing Tools
* [Tox Read the Docs](https://tox.readthedocs.org)
* [Tox Parallel Mode](https://tox.readthedocs.io/en/latest/example/basic.html#parallel-mode)
* [Detox GitHub (Archived)](https://github.com/tox-dev/detox) and [Detox PyPi](https://pypi.python.org/pypi/detox)

<!--
Tox GitHub Action
https://github.com/tox-dev/action | tox-dev/action: A Github Action to run tox environments within Github

https://docs.codecov.io/docs/python
https://codecov.io/#features | Codecov

"[Integration with coverage.py](https://docs.djangoproject.com/en/dev/topics/testing/advanced/#topics-testing-code-coverage)."
"[Running tests using tox](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/#running-tests-using-tox)"

https://github.com/marketplace?utf8=%E2%9C%93&query=tox | GitHub Marketplace · Tools to improve your workflow
https://tox.readthedocs.io/en/latest/example/basic.html#a-simple-tox-ini-default-environments | Basic usage — tox 3.14.6.dev2 documentation

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


https://pypi.org/project/pep8/ | pep8 · PyPI

Formatting
https://pypi.org/project/black/ | black · PyPI
https://pypi.org/project/isort/ | isort · PyPI
https://github.com/PyCQA/isort | PyCQA/isort: A Python utility / library to sort imports.
https://twitter.com/webology/status/1393520619262730249 | Jeff Triplett 😷💉💉💯 on Twitter: "TIL: There are a couple of nice isort tips here that I didn't know were possible like add_imports and remove_imports which I will use Monday. 🤔" / Twitter
https://flake8.pycqa.org/en/latest/
https://launchpad.net/pyflakes/ | Pyflakes in Launchpad
https://pypi.org/project/flake8/ | flake8 · PyPI
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
http://fontawesome.io/ | Font Awesome, the iconic font and CSS toolkit
https://fontawesome.com | Font Awesome 5 | Font Awesome

https://circleci.com/blog/setting-up-continuous-integration-with-github/ | GitHub Continuous Integration - GitHub CI | CircleCI

https://github.com/CircleCI-Public/circleci-cli | CircleCI-Public/circleci-cli: Use CircleCI from the command line
https://github.com/CircleCI-Public/circleci-demo-python-django | CircleCI-Public/circleci-demo-python-django: Example Django application running on CircleCI

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

### Package Tools and Testing

<!--
attrs, pre-commit, tox, nox, flake8, check-manifest, twine, isort, seed-isort-config, black, pytest-cov, codecov action, flake8-black

Not used- but could be?
* [attrs GitHub](https://github.com/python-attrs/attrs)
* [pytest-cov Read the Docs](https://pytest-cov.readthedocs.io)

https://github.com/codecov/codecov-action | codecov/codecov-action: GitHub Action that uploads coverage to Codecov

https://github.com/pytest-dev/pytest-cov | pytest-dev/pytest-cov: Coverage plugin for pytest.

Black and single quotes
https://github.com/peterjc/flake8-black | peterjc/flake8-black: flake8 plugin to run black for checking Python coding style
https://github.com/python/black/issues/118 | Single quotes option · Issue #118 · python/black
-->

### Code Formatting Tools

Code Formatting
* [Black GitHub](https://github.com/psf/black)
* [Black Online (Playground) GitHub](https://github.com/jpadilla/black-online)
* [Black Out GitHub](https://github.com/mariatta/black_out)
* [White GitHub](https://github.com/kennethreitz/white)
* [Google YAPF](https://github.com/google/yapf)

<!--
https://black.readthedocs.io/en/stable/installation_and_usage.html | Installation and usage — Black 19.10b1.dev0+g6bedb5c.d20191029 documentation

https://github.com/bots-for-humanity/black-out

https://black.now.sh/ | Black Playground
-->

## Static Typing

Duck Typing
* [Duck Typing Wikipedia](https://en.wikipedia.org/wiki/Duck_typing)

Strong and Weak Typing
* [Strong and Weak Typing Wikipedia](https://en.wikipedia.org/wiki/Strong_and_weak_typing)
* [Type System Wikipedia](https://en.wikipedia.org/wiki/Type_system)
* [Type System- Static and Dynamic Wikipedia](https://en.wikipedia.org/wiki/Type_system#Static_and_dynamic_type_checking_in_practice)

<!--
https://realpython.com/python-type-checking/

https://en.wikipedia.org/wiki/Type_system#Static_type_checking | Type system - Wikipedia
https://en.wikipedia.org/wiki/Type_system#Dynamic_type_checking_and_runtime_type_information | Type system - Wikipedia
-->

Type Hints
* [PEP 484- Type Hints](https://www.python.org/dev/peps/pep-0484)
* [Guido van Rossum: Stanford Seminar- Optional Static Typing for Python](https://www.youtube.com/watch?time_continue=1&v=GiZKuyLKvAA)

Static Typing Tools
* [Python Mypy GitHub](https://github.com/python/mypy)
* [Python Typeshed GitHub](https://github.com/python/typeshed)
* [Dropbox: PyAnnotate GitHub](https://github.com/dropbox/pyannotate)
* [Dropbox: MyPy PyCharm Plugin](https://github.com/dropbox/mypy-PyCharm-plugin)
* [Facebook: Pyre Check GitHub](https://github.com/facebook/pyre-check)
* [Google: Pytype GitHub](https://github.com/google/pytype)
* [Instagram: Monkey Type GitHub](https://github.com/Instagram/MonkeyType)
* [Microsoft: Pyright GitHub](https://github.com/Microsoft/pyright)

Django Static Typing Tools
* [Typed Django](https://github.com/typeddjango)
* [DEP Draft for Django Type Checking](https://github.com/django/deps/pull/65)

<!--
https://dustingram.com/talks/2020/03/19/static-typing-in-python/

https://github.com/typeddjango/django-stubs | typeddjango/django-stubs: PEP-484 stubs for Django

Encode Typesystem
https://twitter.com/webology/status/1227286423109279744
https://github.com/encode/typesystem | encode/typesystem: A type system library for Python.

http://mypy-lang.org/
https://github.com/machinalis/mypy-django

machine verified documentation
https://twitter.com/pganssle/status/1180224777350520835

https://blogs.dropbox.com/tech/2019/09/our-journey-to-type-checking-4-million-lines-of-python/

Guido- Type Annotations
https://us.pycon.org/2016/schedule/presentation/2266/

http://mypy.readthedocs.io
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


## Python and Django Trends

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

Rust
https://hacks.mozilla.org/2016/11/rust-and-the-future-of-systems-programming/ | Rust and the Future of Systems Programming - Mozilla Hacks - the Web developer blog
https://slides.com/raiderrobert/rust-borrowing-pytn#/11 | Rust: Borrowing
https://bitbucket.org/blog/why-rust | Why we chose Rust as our programming language
https://drewdevault.com/2019/03/25/Rust-is-not-a-good-C-replacement.html | Rust is not a good C replacement | Drew DeVault’s Blog
https://developers.redhat.com/blog/2017/11/16/speed-python-using-rust/ | Speed up your Python using Rust - Red Hat Developer Blog

PyOxidizer- Python and Rust
https://twitter.com/andrewgodwin/status/1143982061524418560 | Twitter
https://twitter.com/di_codes/status/1143973324961304576
https://gregoryszorc.com/blog/2019/06/24/building-standalone-python-applications-with-pyoxidizer/ | Gregory Szorc's Digital Home | Building Standalone Python Applications with PyOxidizer
https://twitter.com/indygreg/status/1143187250743668736 | indygreg on Twitter: "I'm excited to announce the initial release of PyOxidizer - a utility for producing standalone Python applications and which empowers Python and Rust to leverage each other! https://t.co/qZ5Wpjthkn"
https://pyoxidizer.readthedocs.io/en/latest/comparisons.html

Pyodide/Web Assembly
https://github.com/iodide-project/pyodide | iodide-project/pyodide: The Python scientific stack, compiled to WebAssembly
https://hacks.mozilla.org/2019/04/pyodide-bringing-the-scientific-python-stack-to-the-browser/ | Pyodide: Bringing the scientific Python stack to the browser - Mozilla Hacks - the Web developer blog
https://github.com/wasmerio/python-ext-wasm | wasmerio/python-ext-wasm: 🐍🕸 Python extension to run WebAssembly binaries.
https://twitter.com/wasmerio/status/1146477876151115776 | Wasmer on Twitter: "🔥 This is BIG. Using Wasmer 0.5.2 you can run the #Python interpreter ported to #WebAssembly (based on Pyodide) $ wasmer self-update $ wapm install python https://t.co/Oj9RryDrs5… https://t.co/WYMPMDJbNN"

https://twitter.com/raymondh/status/1104802401326755840 | Raymond Hettinger on Twitter: "An emergent problem is that #Python was designed around being launched from a command-line by people who are experienced shell users. Ideally, we should be able to do everything important from the Python interactive prompt, including using pip and changing/setting virtual envs.… https://t.co/vO1frJcTzi"
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

### WSGI

Common Gateway Interface and WSGI (Web Server API)
* [Common Gateway Interface Wikipedia](https://en.wikipedia.org/wiki/Common_Gateway_Interface)
* [Web Server Gateway Interface Wikipedia](http://en.wikipedia.org/wiki/Web_Server_Gateway_Interface)  

Python- PEP 3333 (Python Web Server Gateway Interface)
* [PEP 3333](https://www.python.org/dev/peps/pep-3333) 

WSGI
* [Gunicorn (Python WSGI HTTP Server for UNIX)](http://gunicorn.org), [Gunicorn Python Warehouse](https://warehouse.python.org/project/gunicorn), and [Gunicorn GitHub](https://github.com/benoitc/gunicorn)  
* [WSGI Read the Docs](https://wsgi.readthedocs.io)
* [uWsgi GitHub](https://github.com/unbit/uwsgi) and [uWsgi Docs](http://uwsgi-docs.readthedocs.org/en/latest)
* [uWSGI: Setting up Django and your web server with uWSGI and nginx](https://uwsgi-docs.readthedocs.io/en/latest/tutorials/Django_and_nginx.html)

<!--
Benchmarks and Specifications
https://www.python.org/dev/peps/pep-0249/ | PEP 249 -- Python Database API Specification v2.0 | Python.org
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
